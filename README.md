# Misc

Assorted small projects.

## Cat Coat Genetics Calculator

`cat-genetics-calculator.html` — a single-file, zero-dependency interactive calculator for cat coat
genetics. Set the sex (XX, XY, or XXY for the rare tortoiseshell tom) and the full genotype at every
coat locus (Colourpoint C incl. Mocha, Agouti A, Orange O, Extension E, Brown B, Dilution D,
Dilute-Modifier, Silver I, White W/KIT, Tabby Mc/Sp/Ta/Wb, hair length, the KRT71 Selkirk/Devon/Sphynx
series, Cornish rex, dominant hairless, ear curl) and it derives the breeder-style phenotype name (e.g.
"Chocolate Mink & White (tuxedo)"), the carried recessives (including those hidden under Dominant White
or albinism), warnings (Wd deafness, Hp/Hp ectodermal dysplasia), and a live SVG portrait of the cat.

Naming follows the A genotype rather than what merely shows: red fur always shows tabby, but an a/a red
is still a solid Red, a Red Point (not Lynx), and a Red Smoke (not Cameo). The Mocha allele follows Yu,
Grahn & Lyons 2019: co-dominant with Burmese sepia (cb/cm) and dominant over Siamese (cs/cm).

**Litter mode** crosses a fully genotyped queen and tom (XY, or an XY/XY chimera with a chosen germline
line) and lists every kitten look they can produce with exact odds (as fractions and percentages), split by
sex. Clicking a kitten opens the genotypes behind that look: gene-by-gene odds given the look (a black kitten
from two dilute carriers is D/d 2/3), what it carries, health warnings, every full genotype combination that
produces it, and an Open button that loads any one of them into the single-cat view. Pairing-level warnings
(e.g. 1/4 Wd/Wd) sit above the kittens. `cross()` is pure and exact: genotypes at each locus are grouped
into classes that always name the same, so even an every-gene-heterozygous cross enumerates in well under
a second, and it matches brute-force enumeration exactly.

The portrait (`CatArt.catSVG`) is also a pure function of the phenotype descriptor. It draws a
three-quarter seated cat and places every marking anatomically: the forehead M, cheek lines,
necklaces, leg bars, tail rings, and a flank pattern per tabby type (spots are literally broken
mackerel stripes). Tortoiseshell patches come from thresholded noise, larger on calicos. White
spotting grows up from the paws and belly. Points follow the cool extremities, and long, rex and
hairless coats each change the outline and texture.

The genetics engine (`computePhenotype`) and the litter engine (`cross`) are pure functions with no DOM
dependencies, and the in-page self-tests check textbook ratios (9:3:3:1, Tonkinese 1:2:1, tortie × black by sex).

The file is authored as a claude.ai Artifact page: it intentionally has no `<html>`/`<head>`/`<body>`
wrapper (the artifact host supplies that skeleton) and is theme-aware (light/dark). It also opens
fine as a raw file in a browser.

## Cutout Bench (background remover)

`background-remover.html` — a single-file, zero-dependency tool that makes the background of an illustration
transparent. Drop in images (picker, drag and drop, or paste), get PNGs back, singly or as a zip. Everything runs in the
browser; nothing is uploaded.

It is built for flat-background art rather than photos, and has two methods, picked per image automatically:

- **Flat background.** The background colour is read from the border pixels, and everything within *Tolerance* of it that
  connects to the image edge is removed. Enclosed gaps (the hole in a loop, the space between an arm and a body) can be
  removed too; that is off by default on white and black backgrounds, where eye-whites and ink often match the background.
  Edge pixels are un-mixed against the background (`C = aF + (1-a)B`, with `F` taken from the nearest solid interior pixels),
  which removes the coloured halo instead of just feathering it.
- **Outline matches it.** For ink drawn on a background of the same colour (black linework on black), the outline can't be
  found by colour, and a flood from the edges pours into the interior linework through it. Instead the fill is traced, grown by
  *Outline width* with an exact Euclidean distance transform, and everything the grown shape encloses is kept, so interior ink
  survives. The contour is anti-aliased from the distance field.

The method is chosen by measuring how much background-coloured area deep inside the subject's silhouette leaks out to the image
edge: near zero for flat art, a few percent or more for outline-on-matching-background art. Sealed holes don't count, so a donut
stays a donut.

Touch-ups replay on top of the automatic pass whenever a setting changes: tap a region to drop or restore it, or paint with the
Erase and Restore brushes. *Stray bits* drops loose fragments, such as pieces of a faint background pattern.

The algorithm (`Cutout`) is a set of pure functions on RGBA buffers with no DOM dependencies, and the in-page self-tests check
it on synthetic images. Inside a claude.ai Artifact it saves through the viewer's `downloads` capability; opened as a plain file
it falls back to an ordinary download. Like the calculator, it is authored as an Artifact page with no `<html>` wrapper.

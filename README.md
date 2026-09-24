# Misc

Assorted small projects.

## Cat Coat Genetics Calculator

`cat-genetics-calculator.html` — a single-file, zero-dependency interactive calculator for cat coat
genetics. Set the full genotype at every coat locus (Colourpoint C, Agouti A, Orange O, Extension E,
Brown B, Dilution D, Dilute-Modifier, Silver I, White W/KIT, Tabby Mc/Sp/Ta/Wb, hair length, rex and
hairless genes, ear curl) and it derives the breeder-style phenotype name (e.g. "Chocolate Mink &
White (tuxedo)"), the carried recessives, warnings (Wd deafness, Hp/Hp ectodermal dysplasia), and a
live SVG portrait of the cat.

The portrait (`CatArt.catSVG`) is also a pure function of the phenotype descriptor. It draws a
three-quarter seated cat and places every marking anatomically: the forehead M, cheek lines,
necklaces, leg bars, tail rings, and a flank pattern per tabby type (spots are literally broken
mackerel stripes). Tortoiseshell patches come from thresholded noise, larger on calicos. White
spotting grows up from the paws and belly. Points follow the cool extremities, and long, rex and
hairless coats each change the outline and texture.

The genetics engine (`computePhenotype`) is a pure genotype-to-phenotype function with no DOM
dependencies, so a future two-parent offspring (Punnett) calculator can reuse it directly.

The file is authored as a claude.ai Artifact page: it intentionally has no `<html>`/`<head>`/`<body>`
wrapper (the artifact host supplies that skeleton) and is theme-aware (light/dark). It also opens
fine as a raw file in a browser.

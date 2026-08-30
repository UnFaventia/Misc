# Misc

Assorted small projects.

## Cat Coat Genetics Calculator

`cat-genetics-calculator.html` — a single-file, zero-dependency interactive calculator for cat coat
genetics. Set the full genotype at every coat locus (Colourpoint C, Agouti A, Orange O, Extension E,
Brown B, Dilution D, Dilute-Modifier, Silver I, White W/KIT, Tabby Mc/Sp/Ta/Wb, hair length, rex and
hairless genes, ear curl) and it derives the breeder-style phenotype name (e.g. "Chocolate Mink &
White (tuxedo)"), the carried recessives, warnings (Wd deafness, Hp/Hp ectodermal dysplasia), and a
live stylized SVG portrait of the cat.

The genetics engine (`computePhenotype`) is a pure genotype-to-phenotype function with no DOM
dependencies, so a future two-parent offspring (Punnett) calculator can reuse it directly.

The file is authored as a claude.ai Artifact page: it intentionally has no `<html>`/`<head>`/`<body>`
wrapper (the artifact host supplies that skeleton) and is theme-aware (light/dark). It also opens
fine as a raw file in a browser.

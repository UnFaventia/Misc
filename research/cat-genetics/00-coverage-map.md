# Coverage map & roadmap seeds

> **What this is:** every topic in the research set, held up against what `cat-genetics-calculator.html` actually does today, then grouped by *kind* of work. It's the raw material for the expansion roadmap, not the roadmap itself. More research is still coming, and the tiering at the bottom is a first draft.
> **Related:** [README](README.md) · [inbox](inbox.md)

## Legend

| Mark | Meaning |
|---|---|
| ✅ | Modelled: the calculator produces it (the name may differ slightly) |
| 🏷️ | Naming gap: the genetics are modelled, this name or synonym isn't produced |
| 🟡 | Partial |
| ❌ | Not modelled: needs a new gene, allele or feature |
| 📖 | Descriptive: a show term, quality grade or polygenic expression, not a genotype |
| 🚫 | Not heritable |
| ⚠️ | The sources conflict with each other, or with the calculator |

## Coverage by area

The four layer columns are the calculator's own: **engine** (`computePhenotype`), **naming** (`describe`), **portrait** (`CatArt.catSVG`), **litter** (`cross`).

| Area | Engine | Naming | Portrait | Litter | Evidence quality in the notes | File |
|---|---|---|---|---|---|---|
| Base colours: O, B, D, Dm, E (amber/russet/carnelian) | ✅ | 🏷️ about half the names in the source tables are dialect synonyms | ✅ | ✅ | Cloned genes (Dm uncloned) | [01](01-colour-names.md) |
| Tabby patterns: Mc, Sp, Ta | ✅ | 🏷️ Oyster, "Unpatterned", bare "Spotted" | ✅ | ✅ | Taqpep/DKK4 cloned; Sp uncloned | [02](02-tabby-patterns.md) |
| Wild-derived & breed patterns: marble, rosette, clouded, braided, sokoke, charcoal | ❌ | ❌ | ❌ | ❌ | Mostly descriptive. **APb charcoal is a lead** | [02](02-tabby-patterns.md) |
| Silver / golden / tipping ladder | 🟡 one "Shaded" step | 🏷️ Shell/Smoke Cameo etc. 🟡 the pattern word is dropped on golden/shaded ticked | 🟡 | ✅ | `I`, `Wb` uncloned; tipping depth undescribed genetically | [03](03-silver-golden-shading.md) |
| Tortie / calico / torbie | ✅ | 🏷️ Torbico, Parti-colour, Burmese "Brown Tortie" | ✅ | ✅ | X-linked O, solid | [04](04-tortie-white-van.md) |
| White spotting grades | 🟡 7 steps vs the diagram's 10; no grade-10 Ws white | 🏷️ Seychellois, Cap & saddle, Magpie | ✅ | ✅ (range naming) | KIT cloned; amount polygenic. ⚠️ the diagram suggests a **separate locket/belly-spot gene** | [04](04-tortie-white-van.md) |
| Mitted / Ragdoll / Snowshoe white, laces | 🟡 only Birman `wg` | ❌ | 🟡 | 🟡 | Uncharacterised in the notes | [04](04-tortie-white-van.md) |
| Roan / tweed | ❌ | ❌ | ❌ | ❌ | Descriptive | [04](04-tortie-white-van.md), [10](10-rare-and-future.md) |
| C locus: point, mink, sepia, mocha, albino | ✅ | 🏷️ Natural, Champagne, Platinum, Honey, Frost, Flame, Oyster, Pastel, Snow Tiger | ✅ (fixed contrast) | ✅ | TYR cloned. ⚠️ **Mocha dominance**: the diagram says co-dominant with cs; the calculator follows Yu, Grahn & Lyons 2019 (dominant over cs) | [05](05-colourpoint-mink-sepia-mocha.md) |
| Age & temperature effects (points darken, kittens born blue/dark) | ❌ | ❌ | ❌ | — | Well described, environmental | [05](05-colourpoint-mink-sepia-mocha.md), [06](06-eye-colour-and-shape.md) |
| Eye colour | ❌ | ❌ | 🟡 rule-based heuristic | ❌ | Unstudied genetically, except blue | [06](06-eye-colour-and-shape.md) |
| Odd eyes / dichroic | 🟡 Wd only (portrait) | ❌ | 🟡 | ❌ | Mechanism described | [06](06-eye-colour-and-shape.md) |
| **Dominant Blue Eye (PAX3)** | ❌ | ❌ | ❌ | ❌ | **Strong:** 3 alleles sequenced, lineages typed, homozygote outcomes recorded | [07](07-dominant-blue-eye.md) |
| Pink-eyed dilution | ❌ | ❌ | ❌ | ❌ | One 1961 report, Donskoy reappearance | [06](06-eye-colour-and-shape.md), [10](10-rare-and-future.md) |
| Conformation: body, face, ear set, eye shape | ❌ | ❌ | 🟡 the foreign body is tied to coat texture | — | Polygenic / selection | [08](08-conformation.md) |
| **Toyger rounded ears (GDF7)** | ❌ | ❌ | ❌ | ❌ | **Strong:** recessive deletion, DNA test | [09](09-ears-skull-and-brain.md) |
| Burmese head defect (ALX1) | ❌ | ❌ | ❌ | ❌ | Gene named; inheritance not in the notes (lead) | [09](09-ears-skull-and-brain.md) |
| Chimeras & mosaics | 🟡 XXY, XY/XY | ✅ | ✅ | ✅ XY/XY germline | Descriptive (quadricolour, other tricolours) | [10](10-rare-and-future.md) |
| Future / hypothetical colours | ❌ | ❌ | ❌ | ❌ | Speculative by definition | [10](10-rare-and-future.md) |
| Health warnings | 🟡 Wd, Hp/Hp | — | — | 🟡 the same two | See index | [11](11-health-and-welfare.md) |

## The gaps, grouped by kind of work

### A. Naming dialect layer (no genetics changes)
The biggest gap by row count, and the cheapest to close. Every 🏷️ in files 01–05 lands here.

- **Alias sources already transcribed:**
  - the Equivalent Names Table (Sepia/Mink/Pointed/Abyssinian/Australian Mist columns)
  - American Burmese/Tonkinese terms (Sable, Natural, Champagne, Platinum, Honey)
  - Oriental (Ebony, Chestnut, Lavender)
  - Abyssinian/Somali (Usual, Ruddy, Tawny, Sorrel, "sex-linked" red/cream)
  - Australian Mist (Brown, Gold, Peach)
  - Egyptian Mau, Ocicat and Bengal breed terms
  - Turkish Van (Auburn)
  - Seychellois grade names
  - historic cameo synonyms (Shell/Shaded/Smoke Cameo, Shell Dilute Tortoiseshell)
  - archaic point names (Oyster, Pastel, Snow Tiger, Frost, Flame)
  - historic self names (Beige, Light Brown, Light Lilac, Yellow)
- **Shape:** key on the descriptor the engine already builds (colour key × point class × agouti/pattern × shading × tortie), not on the output string.
  - *Sable*, *Seal* and *Natural* are one pigment differing only at C, so the key has to include C.
- **Collisions to respect:** Brown, Gold/Golden, Mink, Peach, Sorrel/Red, Honey, Bronze (see [01 → Name collisions](01-colour-names.md#name-collisions)).
- **Related naming bugs or decisions** already visible in the current output:
  - golden/shaded **ticked** cats lose "ticked" from the name
  - "Torbie" is never used on shaded coats
  - the **calico threshold**: the calculator says "Calico" only from tuxedo up; the sources say any tortie-and-white
  - "Chinchilla/Shell" (longhair) vs "Tipped" (shorthair) could be chosen off the `L` locus

### B. New loci with strong evidence (Mendelian, testable)
| Candidate | Why it's worth it | Notes |
|---|---|---|
| **DBE (PAX3)** with `ALT`, `CEL`, `RE` (+ `?`) | Best-documented gap in the notes; uses litter-mode pairing warnings heavily | Needs the eye model (D) first. No penetrance numbers, so outcomes stay qualitative ([07](07-dominant-blue-eye.md#modelling-notes-for-the-calculator)) |
| **GDF7** rounded-ear deletion | Recessive, tested, visible marker, hard welfare warning | Portrait: small rounded ears + domed head ([09](09-ears-skull-and-brain.md#modelling-notes)) |
| *Lead:* **APb** (Asian leopard cat agouti, Bengal charcoal) | Would be the first wild-derived pattern gene with a Mendelian handle | Verify before building ([02](02-tabby-patterns.md#source-quirks--open-questions)) |
| *Lead:* **ALX1** Burmese head defect | Two-tier het/hom phenotype | Inheritance not in the notes ([09](09-ears-skull-and-brain.md)) |
| *Lead:* a second albino allele (`ca` blue-eyed vs `c` pink-eyed) | Would make blue- vs pink-eyed albino genotype-driven | The mocha diagram writes `ca` ([06](06-eye-colour-and-shape.md#albinism)) |

### C. Refinements to loci the calculator already has
- **White spotting:**
  - adopt or map the diagram's **10-grade** scale (proposed mapping in [04 → Grade scale → calculator](04-tortie-white-van.md#grade-scale--calculator))
  - add a **grade-10 Ws/Ws "white from spotting"** with a hearing note (kitten smudge → usually hearing)
  - add a warning that grade 2–3 lockets/belly spots **may be a different gene** and won't breed up
- **Tipping depth:** shell → shaded as a polygenic *range*, the way white grade already works, rather than new alleles.
- **Mocha:** decide on the cs/cm question. Keep Yu 2019 (the calculator's current choice) and note the alternative, or allow a distinct Siamocha.
- **Peterbald** brush/flock/velour grades of `Hp/hp` (naming plus portrait texture).

### D. Phenotype layers (not genes)
- **Eye-colour model:** a range by genotype plus a pedigree overlay. It's the prerequisite for DBE and odd eyes ([06 → Modelling notes](06-eye-colour-and-shape.md#modelling-notes)).
- **Age & temperature:**
  - kittens: blue eyes, pale points, amber/russet born dark
  - adults: darker pointed bodies
  - warm/cool: point intensity, and Sia-/Bur-mocha variation
- **Type & breed presets:** body (5 steps), face (7), ear set (4), eye shape (8). A preset can also choose a naming dialect and an eye standard ([08](08-conformation.md#modelling-notes)).

### E. Health & warnings
All consolidated in [11](11-health-and-welfare.md), with a candidate list of new pairing warnings: DBE × DBE, CEL × ALT, RE × RE, GDF7 carrier × carrier, `Ws/Ws` high white.

### F. Edge cases & sandbox
- **XX/XX chimera:** a natural extension of the existing XY/XY machinery, and the explanation for quadricolours ([10](10-rare-and-future.md#chimeras--mosaics-what-the-calculator-does-and-could-do)).
- **Hypotheticals behind a toggle:** black-and-tan, pink-eyed dilution, satin, banded/belted.
- **Wild-derived patterns** as descriptive flags until a gene exists.

## Roadmap seeds: a first-pass tiering (my opinion, to argue with later)

| Tier | Work | Why here |
|---|---|---|
| **1 — cheap, visible** | Naming dialect layer (A) · ticked/torbie naming fixes · white-grade mapping + Ws hearing note (C) | No new genetics, touches the most rows, and makes every later feature read correctly |
| **2 — the headline gene** | Eye-colour model (D) → **DBE** (B) | DBE is the most interesting gap in the notes, and it can't be built without eyes |
| **3 — welfare genes** | **GDF7**, then ALX1 once verified (B, E) | Small engine changes, high information value, reuse the warning machinery |
| **4 — portrait depth** | Age/temperature (D) · tipping-depth range (C) · XX/XX chimera (F) | Visual payoff, moderate effort |
| **5 — type layer** | Body/face/ear presets (D) | Biggest portrait refactor; mostly non-genetic |
| **Parked** | Wild-derived patterns, hypothetical alleles (F) | Weak evidence; sandbox only if wanted |

## Decisions that are yours

1. **Which registries' dialects?** CFA, TICA, GCCF, FIFe or WCF. The notes mix American and British terms freely.
2. **Calico threshold:** keep "Calico from tuxedo up", or follow the sources ("any tortie-and-white")?
3. **Mocha cs/cm:** stick with Yu 2019 (dominant over cs), or model the diagram's co-dominant Siamocha?
4. **Hypotheticals sandbox:** yes or no?
5. **Scope creep:** do skeletal and shape traits (fold, Manx, munchkin, radial hypoplasia) belong in a *coat* calculator?

## Leads I added that aren't in your notes

All of these are marked in their files as *lead / verify*. None was used to fill a source table.

| Lead | File |
|---|---|
| APb Asian-leopard-cat agouti allele as the cause of Bengal charcoal (Gershony et al. 2014) | [02](02-tabby-patterns.md) |
| Egyptian Mau "bronze" being black-based rather than chocolate | [02](02-tabby-patterns.md) |
| Two albino alleles (`ca` / `c`) | [06](06-eye-colour-and-shape.md) |
| ALX1 "Burmese head defect": homozygous lethal, heterozygote short face | [09](09-ears-skull-and-brain.md) |
| LYST as the Chediak-Higashi gene in other species | [11](11-health-and-welfare.md) |
| Fold / Manx / Bobtail / Munchkin / Polydactyly / LaPerm as single-gene shape/coat traits | [08](08-conformation.md) |

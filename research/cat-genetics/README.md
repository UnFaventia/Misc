# Cat genetics research

Sorted research notes for expanding [`cat-genetics-calculator.html`](../../cat-genetics-calculator.html).

These started as a pile of screenshots, diagrams and pasted articles. They're now split by topic, and every row is tagged with its genotype in the calculator's own notation and with whether the calculator already handles it.

**Start with [00 — Coverage map & roadmap seeds](00-coverage-map.md).** It's the one-page answer to "what have we got, what's missing, and what kind of work is each gap".

## Files

| # | File | What's in it |
|---|---|---|
| 00 | [Coverage map & roadmap seeds](00-coverage-map.md) | Every area vs the calculator's four layers; gaps grouped by kind of work; draft tiering; decisions that are yours; leads I added |
| 01 | [Colour names & synonyms](01-colour-names.md) | Self/solid, ticked and tabby colour tables; the Equivalent Names Table; colour glossary; **name collisions** |
| 02 | [Tabby patterns & breed pattern terms](02-tabby-patterns.md) | The tabby-pattern table, breed-specific spotted/tabby terms (Mau, Ocicat, Bengal, Mist, Spangled, American Lynx), pattern → locus map |
| 03 | [Silver, golden, tipped, shaded & smoke](03-silver-golden-shading.md) | The tipping ladder, silver/golden ticked, cameo synonym formulas, golden group, Chausie silver tipped |
| 04 | [Tortoiseshell, bicolour, white spotting & van](04-tortie-white-van.md) | Broken colours, ticked torties, **white-spotting grades 1–10** and the mapping to the calculator's 7 steps, van/Seychellois, mitted & Ragdoll |
| 05 | [Colourpoint, mink, sepia & mocha](05-colourpoint-mink-sepia-mocha.md) | Point types and colours, lynx/tortie/torbie/silver points, Tonkinese mink colours, the mocha triangle |
| 06 | [Eye colour & eye shape](06-eye-colour-and-shape.md) | The colour continuum, what's genetic vs selected, odd and dichroic eyes, albinism, pink-eyed dilution, eight eye shapes |
| 07 | [Dominant Blue Eye (DBE)](07-dominant-blue-eye.md) | The three PAX3 alleles (ALT/CEL/RE), lineages, homozygote outcomes, Ojos Azules, Altai history |
| 08 | [Conformation](08-conformation.md) | Body, face and ear-set types; abnormalities; registry variation; the full conformation glossary, grouped |
| 09 | [Ears, skull & brain](09-ears-skull-and-brain.md) | The Toyger GDF7 rounded-ear brain malformation; brachycephaly; Burmese ALX1 |
| 10 | [Rare & future colours](10-rare-and-future.md) | The future-colours table, scattered rarities, chimeras and mosaics |
| 11 | [Health & welfare index](11-health-and-welfare.md) | Every health-linked trait in one table, with candidate litter-mode warnings |
| — | [Inbox](inbox.md) | Where new research lands before it's sorted |

## How each topic file is laid out

1. **Header**: sources, a one-line calculator status, related files.
2. **At a glance**: the headline takeaways.
3. **Tables** that keep the source's wording, plus two added columns:
   - **Genotype**, in calculator notation
   - **Calculator**, a status mark plus the name the calculator generates today
4. **Modelling notes**: how the material fits the engine. Suggestions are labelled as such.
5. **Source quirks & open questions**: contradictions, typos, blank cells, and claims worth verifying.

Status marks: ✅ modelled · 🏷️ naming gap · 🟡 partial · ❌ not modelled · 📖 descriptive · 🚫 not heritable · ⚠️ sources conflict. Full legend in [00](00-coverage-map.md#legend).

## Notation crib (matches the calculator)

| Locus | Alleles |
|---|---|
| `O` (X-linked) | `O` red · `o` non-red · `O/o` tortie |
| `C` | `C` full · `cb` sepia · `cs` point · `cm` mocha · `c` albino |
| `A` | `A` agouti · `a` non-agouti |
| `E` | `E` · `ea` amber · `er` russet · `ec` carnelian |
| `B` | `B` black · `b` chocolate · `bl` (b′) cinnamon |
| `D` | `D` dense · `d` dilute |
| `Dm` | dilute modifier (caramel; needs `d/d`) |
| `I` | silver |
| `W` | `Wd` dominant white · `Ws` spotting · `w` · `wg` Birman gloves |
| Pattern | `Mc`/`mc` mackerel/classic · `Sp` spotted · `Ta` ticked · `Wb` wide band |
| Coat | `L`/`l` · KRT71 `Se`/`re`/`hr` · `R` Cornish · `Hp` Peterbald · `Cu` curl |

`-` means any allele (`A/-`). A trailing `?` marks a best guess.

## Sources

**Main source:** Sarah Hartwell, messybeast.com. Plain-English colour & pattern guide; *Eye Colours*; *Bicolours and Eye Colours* (2017); blue-eyed breeds and Altai pages; *Small Rounded Ears Mutation* (2016–2023); *Plain English Guide to Conformation*. The white-spotting, eye-colour, eye-shape, body-type, Russian Topaz and mocha diagrams are from the same site.

**Papers and books:**
- Abitbol M et al. (2024) *Animals* 14(13):1845, doi:10.3390/ani14131845. DBE.
- Keating MK et al. (2016) *J Vet Intern Med* 30(2):617–626. Toyger neurological syndrome.
- Yu Y et al. (2020) *Genes* 11:672. GDF7.
- Todd NB (1961) *J Hered* 52:202. Pink-eyed dilution.
- Frances Simpson (1903) *The Book of the Cat*. Silver eye colour.

**Photos:** Greer Stothers (2013), Pangur the albino Oriental Longhair.

The screenshots and photos themselves aren't committed. Everything in them is transcribed into the tables.

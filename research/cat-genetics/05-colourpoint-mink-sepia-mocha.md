# Colourpoint, mink, sepia & mocha (the C locus)

> **Sources:** messybeast.com colour & pattern guide (Sarah Hartwell), user screenshots — Colourpoints (header, point types, point colours, lynx / tortie / tabby tortie / silver tabby points), Mink Colours (Tonkinese), the Equivalent Names Table (Sepia, Mink and Pointed columns only), plus the Mocha / Siamese / Tonkinese / Burmese colour-restriction diagram, almost certainly from Schar & Hartwell 2023 · Doug Schar & Sarah Hartwell, *Mocha Genetics — Interaction with Siamese and Burmese Colour Restriction* (messybeast.com, 2023) · Yu Y, Grahn RA, Lyons LA, *Mocha tyrosinase variant: a new flavour of cat coat coloration*, Anim Genet 2019;50(2):172–175, doi:10.1111/age.12765, PMC6590430 (checked against the full text).  
> **Calculator status:** C series is modelled (C > cb > cs > c, plus cm "mocha"); every colour × point-pattern row is reproducible, and the gaps are registry naming dialects, point/body change with age and temperature, and a distinct Siamocha phenotype.  
> **Images** (all messybeast.com; credits in [img/README](img/README.md)): [colour-guide-06-silver-formulas-golden-colourpoints.png](img/colour-guide-06-silver-formulas-golden-colourpoints.png) · [colour-guide-07-colourpoints-tortie-points-mink.png](img/colour-guide-07-colourpoints-tortie-points-mink.png) · [colour-guide-08-tortie-lynx-points-mink-van-mitted.png](img/colour-guide-08-tortie-lynx-points-mink-van-mitted.png) · [colour-guide-09-van-mitted-equivalent-names-future.png](img/colour-guide-09-van-mitted-equivalent-names-future.png) · [mocha-colour-restriction-triangle.jpg](img/mocha-colour-restriction-triangle.jpg)  
> **Related:** [README](README.md) · [Coverage map](00-coverage-map.md) · [Colour names](01-colour-names.md) · [Tabby patterns](02-tabby-patterns.md) · [Silver, golden & shading](03-silver-golden-shading.md) · [Tortie, white & van](04-tortie-white-van.md) · [Eye colour & shape](06-eye-colour-and-shape.md) · [Dominant blue eye](07-dominant-blue-eye.md) · [Rare & future](10-rare-and-future.md)

## At a glance

- The C (tyrosinase) locus is fully modelled: `C`, `cb` (sepia), `cs` (point), `cm` (mocha), `c` (albino). Generated names are colour word + optional modifier + point word, e.g. "Seal Point", "Seal Lynx Point", "Blue Tortie Point", "Seal Torbie Point", "Seal Mink", "Seal Sepia", "Seal Mocha", "Seal Sepia-Mocha".
- Nearly every "colour × point pattern" row in the source (solid, lynx, tortie, tabby tortie, silver tabby) is ✅ because the engine composes the name from the colour genes, the A locus and the tortie state. The ✅ rows differ from the source only in wording (e.g. "Lynx" vs "Tabby", "Torbie" vs "Tabby Tortoiseshell").
- The real gaps are naming dialects (Frost, Flame, Champagne, Honey, Natural, Platinum, Sable, Oyster, Pastel, Snow Tiger), tipped/shaded/chinchilla depth on points, and anything environmental or age-related (paler kitten points, darker adult bodies, temperature, fever, bandaging).
- ⚠️ **Mocha × Siamese: the calculator is out of step with the breeder evidence.** Schar & Hartwell 2023 say Mocha is "incompletely co-dominant" to both `cs` and `cb`, and that a `BB cmcs DD` cat "looks like an off-colored Siamese". The calculator makes `cm` dominant over `cs`, so `cs/cm` comes out as plain mocha. That rests on Yu 2019's "likely dominant to the Siamese allele", but Yu's own summary calls the cb/cs interactions "unclear". See [Bangkok-Mocha](#bangkok-mocha-schar--hartwell-2023).
- Eye colour by C genotype is a calculator convention; the sources here say mink cats can have blue, aqua or blue-green eyes.

*Genotype shorthand for every table below: unless a row says otherwise, assume non-red (`o`), `E/E`, `i/i`, `dm/dm`, `wb/wb`, `w/w`. `a/a` = solid points, `A/-` = agouti (tabby shows), `-` = any allele. A trailing "?" marks my best guess.*

## Colourpoints

Often called the Siamese or Himalayan pattern (after Himalayan rabbits); pointed cats have the colourpointed coat plus blue eyes, are slow to develop full body and point colour (kittens and young cats have paler points or markings, older cats have darker bodies), and temperature drives the colour: the coldest areas (ears, legs, tail) are darkest, and environment temperature, a fever or even bandaging an injured leg will alter it. The source lists these possible point patterns:

| Name | Source description | Genotype | Calculator |
|---|---|---|---|
| Solid Point | points are of solid colour e.g. seal (dark brown), blue (grey) | `cs/cs a/a` + colour genes | ✅ "Seal Point", "Blue Point", etc. (colour word + "Point") |
| Lynx/Tabby Point | points have tabby markings | `cs/cs A/-` + colour genes | ✅ "Seal Lynx Point" (the calculator says "Lynx", never "Tabby Point"; mackerel/classic/etc. under the points appears only as a note, not in the name) |
| Tortie Point | points have tortoiseshell (multicolour) markings | `cs/cs O/o a/a` + colour genes (female, XXY or XY/XY only) | ✅ "Seal Tortie Point" |
| Abyssinian/Ticked Tabby Point | points are ticked (i.e. agouti) | `cs/cs A/- Ta/-` | 🏷️ Ta is modelled but the name stays "Seal Lynx Point"; the calculator only adds the note "Pattern under the points: ticked." |
| Oyster Point | Old CFA term for Frost/Lilac/Lavender Point | `cs/cs a/a b/b d/d` | 🏷️ calculator generates "Lilac Point"; "Oyster" is not produced |
| Pastel Point | Old term for chinchilla/shaded silver tipped points (pale colour on silvery background) (Tipped Siamese) | `cs/cs A/- I/- Wb/-` ? | 🏷️ silver + Wide Band + agouti is modelled and comes out as "Seal Silver Shaded Lynx Point"; "Pastel" is not produced and chinchilla / tipped / shaded depth is not distinguished |
| Shadow/Smoke Points | shaded points, shadowy tabby markings (darker version of chinchilla) | `cs/cs I/- a/a` (smoke reading) or `cs/cs A/- I/- Wb/-` (shaded reading) ? | 🟡 the smoke reading is modelled as "Seal Smoke Point"; the shaded reading as "Seal Silver Shaded Lynx Point"; the name "Shadow" and its degree relative to chinchilla are not |
| Snow Tiger | alternate term for Lynx/Tabby Points | `cs/cs A/-` + colour genes | 🏷️ calculator generates "Seal Lynx Point"; "Snow Tiger" is not produced |
| Bicolour Point | Colour point with white markings on the coloured areas (present, but less apparent, on the body) e.g. white paws. | `cs/cs Ws/-` (amount polygenic) or `cs/cs wg/wg` (gloves only) ? | 🟡 white on a pointed cat is modelled ("Seal Point & White (bicolor)", or "(gloves)" for wg/wg) but the "Bicolour Point" name and the Ragdoll bicolour / mitted patterns are not; see [04-tortie-white-van.md](04-tortie-white-van.md) |

## Point Colours

The colour names for solid-pointed cats, listed alphabetically in the source with the usual body and point description.

| Name | Source description | Genotype | Calculator |
|---|---|---|---|
| Apricot Point | Pinkish brown points | `cs/cs a/a O d/d Dm/-` ? | ✅ "Apricot Point" ("Apricot Lynx Point" if A/-); in the calculator apricot is dilute red + Dm, and "pinkish brown" is an odd fit for that, hence the ? |
| Blue Point | bluish white body, slate blue points | `cs/cs a/a B/- d/d` | ✅ "Blue Point" |
| Caramel Point | cafe-au-lait colour points (dilute + dilute modifier) | `cs/cs a/a b/b d/d Dm/-` ? | ✅ "Caramel (Taupe) Point" (lilac-based); a blue-based cat gives "Blue-Caramel Point". The source does not say which base. |
| Chocolate Point | ivory body, milk chocolate points | `cs/cs a/a b/b D/-` | ✅ "Chocolate Point" |
| Cinnamon Point | milk-chocolate colour points | `cs/cs a/a bl/bl D/-` | ✅ "Cinnamon Point" |
| Cream (Ivory) Point | creamy white body, buff-cream points. | `cs/cs a/a O d/d` | ✅ "Cream Point" ("Ivory" not produced) |
| Fawn (Light Lilac) Point | Hot cream points | `cs/cs a/a bl/bl d/d` | ✅ "Fawn Point" ("Light Lilac" not produced) |
| Lavender Point | pinkish lilac points | `cs/cs a/a b/b d/d` | 🏷️ calculator generates "Lilac Point"; "Lavender" is not produced |
| Lilac (Frost) Point | glacial white body, frosty pinkish grey points | `cs/cs a/a b/b d/d` | ✅ "Lilac Point" ("Frost" not produced) |
| Red (Flame) Point | creamy white body, deep orange to red points | `cs/cs a/a O` | ✅ "Red Point" ("Red Lynx Point" if A/-; "Flame" not produced) |
| Seal Point | cream/pale fawn body, deep seal brown points | `cs/cs a/a B/- D/-` | ✅ "Seal Point" |

## Lynx (Tabby) Points

As well as solid colours on the points there are tabby (lynx) and tortoiseshell points, which can be hard to tell apart without knowing the colours of the cat's ancestors.

| Name | Source description | Genotype | Calculator |
|---|---|---|---|
| Seal Tabby Point/Seal Lynx Point | cream/fawn body, points brown with seal brown bars. | `cs/cs A/- B/- D/-` | ✅ "Seal Lynx Point" |
| Blue Tabby Point/Blue Lynx Point | bluish white body, points deep blue on pale blue. | `cs/cs A/- B/- d/d` | ✅ "Blue Lynx Point" |
| Caramel Tabby Point/Caramel Lynx Point | _(blank in source)_ | `cs/cs A/- b/b d/d Dm/-` ? | ✅ "Caramel (Taupe) Lynx Point" (lilac-based; blue-based gives "Blue-Caramel Lynx Point") |
| Chocolate Tabby Point/Chocolate Lynx Point | ivory body, points warm milk chocolate on paler background | `cs/cs A/- b/b D/-` | ✅ "Chocolate Lynx Point" |
| Cinnamon Tabby Point/Cinnamon Lynx Point | _(blank in source)_ | `cs/cs A/- bl/bl D/-` | ✅ "Cinnamon Lynx Point" |
| Lilac (Frost) Tabby Point/Lilac (Frost) Lynx Point | glacial white body, points frosty grey with pinkish points | `cs/cs A/- b/b d/d` | ✅ "Lilac Lynx Point" ("Frost" not produced) |
| Red (Flame) Tabby Point/Red Lynx Point | white body, points deep red bars red. | `cs/cs A/- O` | ✅ "Red Lynx Point" (the name needs A/-; a/a red gives "Red Point" even though the tabby still shows) |
| Cream Tabby Point/Cream Lynx Point | white body, points buff bars on pale cream. | `cs/cs A/- O d/d` | ✅ "Cream Lynx Point" |

## Tortoiseshell Points

Tortie points are pointed cats whose points carry a black-based colour patched with red and/or cream (female, or a rare XXY or chimera male).

| Name | Source description | Genotype | Calculator |
|---|---|---|---|
| Seal Tortoiseshell Point | body creamy white, points seal brown patched with red and/or cream | `cs/cs O/o a/a B/- D/-` | ✅ "Seal Tortie Point" |
| Blue Tortoiseshell Point/Blue Cream Point | body bluish white/creamy white, points slate blue patched with cream. | `cs/cs O/o a/a B/- d/d` | ✅ "Blue Tortie Point" ("Blue Cream Point" not produced; pointed torties are named by the eumelanin patch, so the "Blue-Cream" wording is bypassed) |
| Chocolate Tortoiseshell Point/Chocolate Cream Point | ivory body, points milk chocolate patched with red and/or cream | `cs/cs O/o a/a b/b D/-` | ✅ "Chocolate Tortie Point" |
| Lilac (Frost) Tortoiseshell Point/Lilac Cream Point | glacial white body, frosty pinkish grey points patched with cream. | `cs/cs O/o a/a b/b d/d` | ✅ "Lilac Tortie Point" |

## Tabby Tortoiseshell (Tortie Lynx) Points

Tortoiseshell points that also carry tabby barring; the engine calls these "Torbie" points.

| Name | Source description | Genotype | Calculator |
|---|---|---|---|
| Seal Tabby Tortoiseshell Point/Seal Tortie Lynx Point | body cream/pale fawn, points brown with seal brown markings and red and/or cream markings. | `cs/cs O/o A/- B/- D/-` | ✅ "Seal Torbie Point" |
| Blue Tabby Tortoiseshell Point/Blue Tortie Lynx Point | bluish white body, points pale blue with slate blue markings with patches of cream. | `cs/cs O/o A/- B/- d/d` | ✅ "Blue Torbie Point" |
| Caramel Tabby Tortoiseshell Point/Caramel Tortie Lynx Point | _(blank in source)_ | `cs/cs O/o A/- b/b d/d Dm/-` ? | ✅ "Caramel (Taupe) Torbie Point" |
| Chocolate Tabby Tortoiseshell Point/Chocolate Tortie Lynx Point | body ivory, points pale chocolate barred with warm milk chocolate with red and/or cream patches. | `cs/cs O/o A/- b/b D/-` | ✅ "Chocolate Torbie Point" |
| Cinnamon Tabby Tortoiseshell Point/Cinnamon Tortie Lynx Point | _(blank in source)_ | `cs/cs O/o A/- bl/bl D/-` | ✅ "Cinnamon Torbie Point" |
| Lilac (Frost) Tabby Tortoiseshell Point/Lilac (Frost) Tortie Lynx Point | _(blank in source)_ | `cs/cs O/o A/- b/b d/d` | ✅ "Lilac Torbie Point" |

## Silver Tabby Points

A relatively recent experimental development is the silver tabby point, and silver tabby tortoiseshells are possible and would use the same naming formula.

| Name | Source description | Genotype | Calculator |
|---|---|---|---|
| Blue Silver Tabby Point | points silvery with slate blue barring | `cs/cs A/- I/- B/- d/d` | ✅ "Blue Silver Lynx Point" |
| Seal Silver Tabby Point | points silvery with seal barring | `cs/cs A/- I/- B/- D/-` | ✅ "Seal Silver Lynx Point" |
| Red Silver Tabby Point | points silvery with red markings | `cs/cs A/- I/- O` | ✅ "Cameo Lynx Point" (the calculator's cameo wording for silver red; "Red Silver" not produced) |
| Cream Silver Tabby Point | points silvery with cream markings | `cs/cs A/- I/- O d/d` | ✅ "Dilute Cameo Lynx Point" |

## Mink Colours (Tonkinese)

Minks are pointed cats with much darker bodies and less (though still apparent) contrast between body and points, a halfway-house between solid colour (Burmese) and colourpoint (Siamese); in theory Tonkinese occur in versions of all Burmese colours (the parenthetical names below are the Burmese equivalents), mink cats have blue, aqua or blue-green eyes, in Australia Tonkinese come in spotted, tabby, ticked, tortie and tortie-tabby varieties and in the silver series, and many registries use the Oriental or Burmese colour name rather than "mink".

| Name | Source description | Genotype | Calculator |
|---|---|---|---|
| Blue Mink | Ash blue (with warm fawn tones) body, medium/slate blue points. | `cb/cs a/a B/- d/d` | ✅ "Blue Mink" |
| Champagne Mink | (Chocolate) buff cream/light tan body, points golden tan to milk chocolate (American term) | `cb/cs a/a b/b D/-` | 🏷️ calculator generates "Chocolate Mink"; "Champagne" is not produced |
| Honey Mink | (Cinnamon) (American term) | `cb/cs a/a bl/bl D/-` | 🏷️ calculator generates "Cinnamon Mink"; "Honey" is not produced |
| Natural Mink | (Black/Seal) Medium brown body, deep seal brown points. (American term) | `cb/cs a/a B/- D/-` | 🏷️ calculator generates "Seal Mink"; "Natural" is not produced |
| Platinum Mink | (Lavender/Lilac) Pale silver/pearly grey body (with light fawn tones), points pale dove grey to light taupe grey (American term) | `cb/cs a/a b/b d/d` | 🏷️ calculator generates "Lilac Mink"; "Platinum" is not produced |
| Red Mink | Pale red body, darker red points with ghost tabby markings | `cb/cs a/a O` | ✅ "Red Mink" (red shows ghost tabby even on a/a; A/- gives "Red Lynx Mink") |
| Cinnamon Mink | _(blank in source)_ | `cb/cs a/a bl/bl D/-` | ✅ "Cinnamon Mink" |
| Fawn Mink | A "hotter version" of cream. | `cb/cs a/a bl/bl d/d` | ✅ "Fawn Mink" |
| Cream Mink | _(blank in source)_ | `cb/cs a/a O d/d` | ✅ "Cream Mink" |

## Sepia / Mink / Pointed Names

The three relevant columns of the source's Equivalent Names Table, set beside its Full Expression column; the C genotype for each column is `cb/cb`, `cb/cs`, `cs/cs`. In the Calculator column ✅ means every name in the row is generated, 🏷️ means the colour is modelled but at least one listed name (Sable, Natural, Champagne, Platinum, Honey) is not. The table's Abyssinian/Somali and Australian Mist columns are not transcribed here.

| Full Expression | Genotype (body colour) | Sepia (Burmese) `cb/cb` | Mink (Tonkinese) `cb/cs` | Pointed (Siamese) `cs/cs` | Calculator |
|---|---|---|---|---|---|
| Black/Brown (in tabbies)/Ebony | `B/- D/-` | Brown/Sable/Seal Sepia | Sable/Natural Mink | Sable/Seal | 🏷️ "Seal Sepia" / "Seal Mink" / "Seal Point"; Brown, Sable, Natural and Ebony are not produced |
| Blue | `B/- d/d` | Blue/Blue Sepia | Blue | Blue | ✅ "Blue Sepia" / "Blue Mink" / "Blue Point" |
| Chocolate/Chestnut/Brown | `b/b D/-` | Chocolate/Champagne Sepia | Chocolate/Champagne Mink | Chocolate | 🏷️ "Chocolate Sepia" / "Chocolate Mink" / "Chocolate Point"; Champagne and Chestnut are not produced |
| Lilac/Lavender/Frost | `b/b d/d` | Lilac/Platinum Sepia | Lilac/Platinum Mink | Lilac/Platinum | 🏷️ "Lilac Sepia" / "Lilac Mink" / "Lilac Point"; Lavender, Frost and Platinum are not produced |
| Cinnamon | `bl/bl D/-` | Cinnamon/Cinnamon Sepia | Cinnamon/Honey Mink | Cinnamon | 🏷️ "Cinnamon Sepia" / "Cinnamon Mink" / "Cinnamon Point"; Honey is not produced |
| Fawn/Light Lilac | `bl/bl d/d` | Fawn/Fawn Sepia | Fawn | Fawn | ✅ "Fawn Sepia" / "Fawn Mink" / "Fawn Point" ("Light Lilac" in the first column is not produced) |
| Red | `O` | Red/Red Sepia | Red | Red | ✅ "Red Sepia" / "Red Mink" / "Red Point" |
| Cream | `O d/d` | Cream/Cream Sepia | Cream | Cream | ✅ "Cream Sepia" / "Cream Mink" / "Cream Point" |

## The Mocha Triangle

A diagram arranging the three classic colour restrictions (Siamese, Tonkinese, Burmese) around the three mocha-allele phenotypes, with double-headed arrows joining Siamese–Tonkinese, Tonkinese–Burmese, Siamese–Siamocha, Siamocha–Mocha, Mocha–Burmocha and Burmocha–Burmese (the diagram does not say what the arrows mean).

| Name | Source description | Genotype | Calculator |
|---|---|---|---|
| Siamese colour restriction | _(blank in source; label and genes only)_ | `cs/cs` or `cs/c` (the diagram writes "cs/cs or cs/ca") | ✅ "Seal Point" |
| Tonkinese (Mink) colour restriction | _(blank in source; label and genes only)_ | `cb/cs` | ✅ "Seal Mink" |
| Burmese colour restriction | _(blank in source; label and genes only)_ | `cb/cb` | ✅ "Seal Sepia" |
| Siamocha | _(blank in source; label and genes only)_ | `cs/cm` | ⚠️ genotype is accepted but shown as plain "Seal Mocha" (calculator makes cm dominant over cs, same contrast as cm/cm). Schar & Hartwell 2023 describe it as an intermediate that "looks like an off-colored Siamese" |
| Burmocha | _(blank in source; label and genes only)_ | `cb/cm` | ✅ "Seal Sepia-Mocha" ("Burmocha" / "Bur-Mocha" not produced) |
| Mocha | _(blank in source; label and genes only)_ | `cm/cm` | ✅ "Seal Mocha" |

Text in the diagram (close to verbatim):

> DNA analysis shows that Mocha is an allele at the cs/cb locus and is therefore co-dominant with Burmese and Siamese colour restriction. Mocha x Mink will give both Sia-Mocha and Bur-Mocha patterns.
>
> Sia-mocha & Bur-mocha colour and contrast varies according to temperature, season and random gene expression.
>
> cm/cm cat may have pink noses (the first cats studied had pink noses, but later imports did not).
>
> Note: The names Sia-Mocha & Bur-Mocha are informal. The gene symbol cm is also informal.

## Bangkok-Mocha (Schar & Hartwell 2023)

> **Source:** Doug Schar & Sarah Hartwell, *Mocha Genetics — Interaction with Siamese and Burmese Colour Restriction* (messybeast.com, 2023).
> - **Who:** Doug Schar runs the *Bangkok Mocha Cats* website. He has imported, tested and worked with over 60 cats from Thailand over 15 years, and is collecting photos of mocha cats at various ages.
> - **Cross-checked against:** Yu, Grahn & Lyons 2019, the paper that identified the variant: a 111-bp in-frame TYR deletion, `c.820_936delinsAATCTC`, segregating in a 12-cat Burmese pedigree.

### Naming
- **"Bangkok-Mocha":** Doug's preferred name, which Hartwell's article adopts. The first three cats were found **on a dock in Bangkok**, and he wants that origin reflected in the gene's name. The labs competed in secrecy to be first to identify the gene and develop a test.
- **The article's colour synonyms:**
  - genetic black = **Sable** (Burmese, USA) / **Brown** (Burmese, UK & Europe) / **Seal** (Siamese)
  - chocolate = **champagne**
  - lilac = **platinum**

### Genotypes, in the article's symbols

| Genotype | Article name | Calculator today |
|---|---|---|
| `C/` | Full colour | ✅ |
| `cb/cb`, `cb/ca` | Burmese colour restriction | ✅ "… Sepia" (the calculator writes `c` for `ca`) |
| `cb/cm` | Burmese-Mocha | ✅ "… Sepia-Mocha" |
| `cb/cs` | Tonkinese colour restriction | ✅ "… Mink" |
| `cm/cm` | Mocha colour restriction | ✅ "… Mocha" |
| `cs/cm` | **Siamese-Mocha** | ⚠️ named "… Mocha"; the calculator treats `cm` as dominant over `cs` |
| `cs/cs`, `cs/ca`, `cs/c` | Siamese colour restriction | ✅ "… Point" |
| `ca/ca` | **Blue-eyed albino** | 🟡 the calculator has a single albino allele `c` |
| `c/c` | **Pink-eyed albino** | 🟡 same |

### Dominance: what each source actually says
- **Schar & Hartwell 2023:** "Mocha is on the same locus as cs and cb. It is **incompletely co-dominant to each of those**. The diagram below shows the co-dominance but the actual intermediate mocha colours are variable."
- **Doug's breeding results** (cs/cm in sable, blue, chocolate/champagne and platinum/lilac; cb/cm in all four; cm/cm "soon" in all four):
  - "a BB cmcb dd is indistinguishable from a BB cbcb dd": blue Burmese-Mocha looks like blue Burmese.
  - "a BB cmcs DD looks like an **off-colored Siamese**."
  - Apart from the sable/brown cm/cm (`BB cmcm DD`), the gene only slightly modifies the colour, sometimes imperceptibly "even when you know that cat has Bangkok-Mocha". That's why it went undetected for so long.
  - The sable Burmese-Mocha is highly variable and "could easily pass as a light sable (Brown) Burmese".
- **Yu, Grahn & Lyons 2019** (full text):
  - Mocha is **recessive to C**.
  - Mocha is "likely co-dominant to the Burmese allele and temperature sensitive".
  - It is "**also likely dominant to the Siamese (cs) allele**": inferred cm/cs cats "displayed the mocha coloration instead of the otherwise expected Siamese coloration".
  - **But** the summary says "interactions with the cb and cs alleles are unclear due to the temperature-sensitivity of the alleles", and "not all allelic combinations have been observed".
  - The paper writes the series as `C > cb = cs > c, c2`.
- **Verdict:** the calculator took Yu's hedged "likely dominant" as settled. The breeder with the most cs/cm cats says intermediate, leaning Siamese. Both messybeast sources agree with him.

### Eyes, nose & paw pads
- **"Diamond eye":** the one constant across cm/cm, cs/cm and cb/cm is **luminescent eyes**. The Thai term is "diamond eye": they sparkle and look backlit, and others describe them as "liquid mercury". The effect is present in all the cats but doesn't always show in photos. Doug: "it always makes the eye color pop".
- **Eye colour itself varies.** The sable Burmese-Mocha shows "great diversity in eye colour". Yu 2019: "Mocha cats have aqua eye coloration and pink nose leather and paw pads."
- **Nose:** in cm/cm, **the pink nose and pink paw pads are strictly a kitten thing**. The nose darkens to brown with age and the pads turn brownish. "The oddly brown nose is a characteristic feature of the adult cats", whatever their tone of mocha, from reddish to blondish.

### Breeding & history
- **Rarity:** cm/cm is rare in Thailand, and a dilute cm/cm "even greater unlikelihood". Doug suspects he may be making the first dilute Bangkok-Mochas that have ever existed.
- **Caution:**
  - No physical abnormalities have been detected in cm/cm so far, "but I have my eyes wide open".
  - From his parrot-breeding days: "never breed a mutation bird to mutation bird". He admits it's "a huge leap" to cats.
  - He suggests producing cm/cm through **`cb/cm × cs/cm`** or **`C/cm × cb/cm`** rather than cm/cm × cm/cm ("all theoretical"). *My arithmetic:* both crosses give ¼ cm/cm. The first also gives ¼ each cb/cs, cb/cm and cs/cm; the second ¼ each C/cb, C/cm and cb/cm. Litter mode already computes this.
- **Early Burmese:** Doug writes, "When I read the early books on the breed, in the Harrison Weir time frame, it seems initially the Burmese standard was for blue eyes and then it was changed to yellow eyes. I have a feeling the cm gene was floating around in the early imports."
- **Colour breeding and closed gene pools** (the Korat story, CFA's import rules): see [11](11-health-and-welfare.md#colour-breeding--closed-gene-pools).

## Glossary

| Name | Source description | Genotype | Calculator |
|---|---|---|---|
| Sepia (Burmese Colour Restriction) | Burmese-type colour restriction where the legs, head and tail are slightly darker than the body. | `cb/cb` (the calculator also treats `cb/c` as sepia) | ✅ "Sepia" (low-contrast points) |
| Mink (Colour Restriction) | Intermediate between sepia and pointed; the points (face, legs, tail) are a darker version of main body colour. | `cb/cs` | ✅ "Mink" |
| Colourpointed | The 'Himalayan' pattern with a pale body and darker legs, tail and ears, as seen in the Siamese. | `cs/cs` (or `cs/c`) | ✅ "Point" |
| MASK | darker colour covers the face, including whisker pads, and may be connected to the ears by tracings. | descriptive; extent is not a single genotype | 📖 show term; the calculator has one contrast value per C class and no mask / tracing extent |
| HOOD | a coloured mask extending to the base of the ear forming a hood of colour, i.e. no pale area between the top of the eyes and the front of the ears. | descriptive; extent is not a single genotype | 📖 show term; not modelled as a distinct feature |
| POINTS | the extremities of a cat's body: the mask, ears, tail and feet. | descriptive (anatomical term) | 📖 not a genotype |

## Modelling notes

- **How names are built (from the engine).** Colour word from the eumelanin patch (black becomes "Seal" on any pointed cat, but not on solid cats), then silver / shading words, then a modifier (`Lynx` for A/-, `Tortie` for O/o a/a, `Torbie` for O/o A/-), then the point word (`Point`, `Mink`, `Sepia`, `Sepia-Mocha`, `Mocha`). Pointed torties bypass the usual "Blue-Cream" style names, so "Blue Tortie Point" is what you get rather than "Blue Cream Point".
- **Pure naming dialect (genetics already modelled, name not produced).** Frost, Flame, Ivory and Light Lilac (parenthetical glosses); Lavender; Champagne, Honey, Natural and Platinum (the source marks these as American terms); Sable and Brown in the Equivalent Names Table; Oyster (old CFA), Pastel and Snow Tiger; the "Tabby Point" wording (the engine says "Lynx"); "Blue Cream Point"; "Red Silver" (the engine says "Cameo"). My inference: one registry/breed dialect layer that remaps generated names (e.g. "Seal Mink" to "Natural Mink" under CFA, "Chocolate Mink" to "Champagne Mink") would cover all of these without touching the genetics.
- **Silver, tipped and shaded points.** The calculator's shading is a single on/off Wide Band (`Wb`), so Pastel (chinchilla / tipped / shaded) and Shadow cannot be told apart, and the Pastel / Shadow genotypes above are my guesses. Silver tortie points are covered by the formula the source mentions: "Seal Silver Torbie Point".
- **Ticked and spotted points.** `Ta` and `Sp` are modelled, but on a pointed cat they appear only in the note "Pattern under the points: …", not the name. The same holds for the Australian Tonkinese varieties (spotted, tabby, ticked, tortie, tortie-tabby, silver): all are expressible with existing loci, with names like "Seal Torbie Mink" or "Seal Silver Lynx Mink".
- **Red and cream points.** The engine names by the A genotype, not by whether tabby shows, so "Red Point" (a/a) and "Red Lynx Point" (A/-) are different names for cats whose ghost tabby markings both show. The source's separate "Red (Flame) Point" and "Red Lynx Point" rows map to those two.
- **Age and temperature (portrait feature idea, my suggestion).** The source says points are paler on kittens, bodies darken with age, and temperature, fever or bandaging change the colour. The calculator treats this only in text; the portrait paints a fixed body paling per C class and points at an opacity equal to the contrast value. A possible feature is an age and warm / cool slider that shifts body and point tone (age and seasonal change are phenotypic; fever and bandaging are 🚫 not heritable, so display-only). The diagram adds that Sia-Mocha and Bur-Mocha vary with temperature, season and "random gene expression".
- **Bicolour Point and Ragdoll patterns.** "Bicolour Point" (this file) and the later Mitted & Ragdoll table are white-spotting questions and live in [04-tortie-white-van.md](04-tortie-white-van.md). The nearest thing the calculator has is `Ws` or `wg/wg` on a `cs/cs` cat, which names as "Seal Point & White (…)".
- **Eye colour.** The calculator paints pointed cats blue, sepia chartreuse and mink / sepia-mocha / mocha aqua, keyed off the C genotype. The sources here say pointed cats have blue eyes and mink cats have blue, aqua or blue-green eyes, so mink's single "aqua" is a simplification, and nothing in these screenshots gives sepia or mocha eye colour. See [06-eye-colour-and-shape.md](06-eye-colour-and-shape.md); blue eyes from white / dominant-white are a separate mechanism ([07-dominant-blue-eye.md](07-dominant-blue-eye.md)).
- **Mocha crosses.** Mocha × Mink (`cm/cm` × `cb/cs`) gives `cb/cm` and `cs/cm`, which the engine names "Seal Sepia-Mocha" and "Seal Mocha". The diagram expects Bur-Mocha and Sia-Mocha, so the cb/cm half matches and the cs/cm half does not (see quirks).
- **Proposed correction (my suggestion, based on Schar & Hartwell 2023):**
  - Give `cs/cm` its own C class, **Siamese-Mocha**. Its contrast should sit between point (1) and mocha (.3), leaning Siamese, since it "looks like an off-colored Siamese". Name it "Seal Siamese-Mocha" in parallel with "Seal Sepia-Mocha".
  - Replace the "cm is dominant over cs" note with one citing both readings.
  - **Also:** the cm/cm portrait nose should be brown in adults (pink in kittens), and all three mocha classes could carry a "diamond eye" note.
  - **Possible second step:** split the albino allele into `ca` (blue-eyed) and `c` (pink-eyed). Yu 2019 also lists two albino variants, which it calls `c` and `c2`.
- **My reading of the diagram's illustrations.** Siamocha is drawn palest (cream with light tan points), Mocha light tan, Burmocha mid-brown, Burmese dark brown. The calculator's body-paling order (mocha .42, sepia-mocha .5, sepia .6) fits Mocha, Burmocha and Burmese, but cs/cm is forced to the Mocha value, so Siamocha cannot be drawn.
- **Not modelled.** Pink noses on cm/cm cats (❌; the portrait derives nose colour from coat pigment). Albino `c` appears in the calculator as a carrier allele (`cs/c`, `cb/c`) or as `c/c` masking everything; the diagram mentions albino only in "cs/ca".

## Source quirks & open questions

- **Mocha dominance: now weighed (see [Bangkok-Mocha](#bangkok-mocha-schar--hartwell-2023)).** The diagram and Schar & Hartwell 2023 both say `cm` is (incompletely) co-dominant with `cs`, so `cs/cm` is an intermediate Siamese-Mocha. The calculator says `cm` is dominant over `cs`, citing Yu 2019. Yu's discussion does say "likely dominant to the Siamese (cs) allele", but its summary says the interactions are "unclear". **Two sources plus a breeder's direct results against one hedged inference.** I'd treat the calculator as the one to change.
- **Albino symbols.** The diagram and the 2023 article write `ca` (blue-eyed albino) and `c` (pink-eyed albino). Yu 2019 lists two albino variants as `c` and `c2`. The calculator has one `c`. Whether the article's `ca`/`c` are Yu's `c`/`c2` isn't stated.
- **Informal names.** The diagram labels use one word ("Siamocha", "Burmocha"), while its text uses "Sia-Mocha" and "Bur-Mocha". The 2023 article uses **Siamese-Mocha / Burmese-Mocha / Bangkok-Mocha**. The diagram itself says these names and the symbol `cm` are informal.
- **Pink noses: resolved.** "The first cats studied had pink noses, but later imports did not" was an **age effect**. Per Schar & Hartwell 2023, pink noses and paw pads are kitten-only in cm/cm, and adults have a characteristic brown nose. Yu 2019's "pink nose leather and paw pads" is consistent with that if it describes young cats.
- **"Blue" or lilac?** The 2023 article says "a (bb cmcm dd) cat would be an even greater unlikelihood. In other words, I may be making the first **blue** Bangkok Mochas". But `bb dd` is lilac/platinum; blue is `B- dd`. Either the genotype has a typo for `BB`, or "blue" is used loosely.
- **Blank descriptions (7).** Caramel and Cinnamon in the Lynx table; Caramel, Cinnamon and Lilac (Frost) in the Tabby Tortoiseshell table; Cinnamon Mink and Cream Mink.
- **Typos and awkward wording.** "Torrtie" in the Cinnamon tortie lynx row was corrected silently. Red Lynx reads "points deep red bars red" and Lilac Lynx "points frosty grey with pinkish points" as in the source; the intended meaning is not certain.
- **Same genotype, several rows.** Lilac (Frost) Point, Lavender Point and Oyster Point are all lilac points (the Equivalent Names Table lists "Lilac/Lavender/Frost"), and Snow Tiger is Lynx Point. Honey Mink and Cinnamon Mink are the same colour (the Equivalent Names Table gives "Cinnamon/Honey Mink"), and the Mink table gives Natural, Champagne and Platinum names but has no plain "Seal", "Chocolate" or "Lilac" Mink rows.
- **Near-identical descriptions.** Chocolate Point ("ivory body, milk chocolate points") and Cinnamon Point ("milk-chocolate colour points") are barely distinguished. Fawn Point is "Hot cream points" and Fawn Mink a "hotter version" of cream; whether "Light Lilac" is a true synonym of fawn is unclear, since the calculator derives fawn from `bl/bl d/d`, not from lilac.
- **Apricot Point.** "Pinkish brown points" does not obviously describe a red-based colour, so the Apricot genotype (dilute red + Dm) comes from the calculator's own definition, not from the source. The source also does not say whether Caramel Point is lilac-based or blue-based.
- **"Ticked (i.e. agouti)".** The source treats ticked and agouti as the same thing for Abyssinian points; in the calculator `A` lets tabby show and `Ta` is a separate dominant ticking gene.
- **Pastel / Shadow wording.** Pastel mixes "chinchilla", "shaded silver" and "tipped"; Shadow/Smoke says "shaded points, shadowy tabby markings", which could mean smoke (non-agouti silver) or a shaded agouti. Both genotypes above are guesses.
- **Uneven colour coverage.** The Tortoiseshell Points table lists four colours but the Tabby Tortoiseshell table lists six (adding Caramel and Cinnamon); the Silver Tabby Points table has only Blue, Seal, Red and Cream. The calculator can name all of them.
- **Experimental silver points.** The source calls silver tabby points "a relatively recent experimental development", so registry acceptance of those names is worth checking before presenting them as established.

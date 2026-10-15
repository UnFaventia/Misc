# Colour names & synonyms

> **Sources:** messybeast.com colour & pattern guide (Sarah Hartwell), user screenshots — Self/Solid Colours (+ note), Ticked/Agouti Colours, Tabby Colours, Equivalent Names Table; the plain-English colour glossary supplied with the brief; a few rows from the Breed-Specific Tabby/Spotted Terms and Future Colour Possibilities tables are cited in "Name collisions" only.  
> **Calculator status:** The base colour set (O, B/b/bl, D/d, Dm, E-series amber/russet, I, Wb, Ta, C-series) is fully modelled; roughly half the names in these tables are synonyms or breed/registry dialect names the engine never emits.  
> **Related:** [README](README.md) · [Coverage map](00-coverage-map.md) · [Tabby patterns](02-tabby-patterns.md) · [Silver, golden & shading](03-silver-golden-shading.md) · [Tortie, white & van](04-tortie-white-van.md) · [Colourpoint, mink, sepia & mocha](05-colourpoint-mink-sepia-mocha.md) · [Rare & future colours](10-rare-and-future.md)

## At a glance

- 81 rows transcribed: Self/Solid 36, Ticked/Agouti 21, Tabby Colours 16, Equivalent Names 8 (plus a 6-term glossary and a name-collisions table).
- Every real colour here reduces to a combination the calculator already has: red/cream from O, the eumelanin colours from B × D, caramel/taupe/apricot from Dm, amber/russet from the E series, silver/golden from I and Wb. No new locus is needed for the colour names themselves.
- Naming gaps dominate: 16 of 36 Self rows, 9 of 21 Ticked rows and 1 Tabby row are synonyms the engine does not emit (Sable, Champagne, Platinum, Ebony, Usual, Sorrel, Beige, Frost, Lavender…). A breed/registry "dialect" layer would cover them; the Equivalent Names table is ready-made data for it.
- The only true modelling gaps are the experimental shimmer Black ticked, hybrid-breed "tawny", breed ground colours (Singapura "ivory", Manilla "sandy-golden"), Suqutranese sparkle bands and Golden-tabby vs Golden-shaded tipping degree.
- Names collide heavily across breeds and tables (Brown, Gold/Golden, Honey, Sorrel/Red, Peach, Mink, Sable…); see "Name collisions".
- Genotype cells use the calculator's symbols; "-" = any allele. Non-red colours assume non-orange (o) and full colour (C/-) unless a C genotype is shown; Dm is written only where caramel is meant (otherwise assume dm/dm).

## Self/Solid Colours

Colours have different names in different countries and breeds, and breeds or countries may use the same name for different colours; this section describes the basic colours as non-specifically as possible.

| Name | Source description | Genotype | Calculator |
|---|---|---|---|
| Albino | White due to lack of pigmentation i.e. white with pale blue eyes; the most extreme form of albino is a cat with pink eyes. Most blue-eyed white cats are NOT albino. | c/c (C locus; hides every other colour gene) | ✅ "Albino" (sub-line shows the masked colour) |
| Amber (Norwegian Forest Cat) | Bright apricot to cinnamon, with brown nose leather, paw pads and eye rims. Kittens are born dark/black and brighten as they mature. | ea/ea a/a D/- (B locus hidden beneath) | ✅ "Amber" |
| Apricot | Pink-brown or hot cream, with a metallic sheen due to cream + dilute modifier. | O, d/d Dm/- | ✅ "Apricot" |
| Beige | Old term for Fawn | a/a bl/bl d/d | 🏷️ emits "Fawn" |
| Black | Jet-black, called Ebony in Foreigns/Orientals | a/a B/- D/- | ✅ "Black" |
| Blue | Blue-grey; the dilute of black | a/a B/- d/d | ✅ "Blue" |
| Brown | Old term for Chocolate. Burmese "Brown" ("Sable" in America) and Siamese "Seal" are equivalent to black. | Two senses: a/a b/b D/- (old term = chocolate); a/a B/- D/- (Burmese "Brown", Siamese "Seal" = genetically black, on cb/cb or cs/cs) | 🏷️ emits "Chocolate" for the old sense; black on cb/cb is "Seal Sepia", on cs/cs "Seal Point" |
| Caramel | Blue/Lilac/Fawn + Dilute Modifier. Cafe-au-lait colour (biscuit colour), cool toned bluish fawn, metallic sheen | a/a d/d Dm/- (B/- = blue-caramel, b/b = lilac-based, bl/bl = fawn-caramel) | ✅ "Caramel (Taupe)" (lilac-based), "Blue-Caramel", "Fawn-Caramel" |
| Champagne | Burmese/Tonkinese equivalent to chocolate (American term) | a/a b/b D/- with cb/cb (Burmese) or cb/cs (Tonkinese) | 🏷️ emits "Chocolate Sepia" / "Chocolate Mink" |
| Chestnut | Medium-dark brown, Oriental equivalent to chocolate | a/a b/b D/- | 🏷️ emits "Chocolate" |
| Chocolate | Medium-dark brown | a/a b/b D/- | ✅ "Chocolate" |
| Cinnamon | Milk-chocolate (reddish) colour (Light Brown) | a/a bl/bl D/- | ✅ "Cinnamon" |
| Cream | Buff colour, dilute of red | O, d/d | ✅ "Cream" (ghost tabby on red is noted by the engine) |
| Ebony | Foreign/Oriental equivalent to black (American term) | a/a B/- D/- | 🏷️ emits "Black" |
| Fawn | Hot cream colour, equivalent to Light Lilac; historically a biscuity colour. | a/a bl/bl d/d | ✅ "Fawn" |
| Frost | Alternate name for Lilac/lavender (American term) | a/a b/b d/d | 🏷️ emits "Lilac" |
| Gold | Equivalent to cinnamon in some breeds | a/a bl/bl D/- | 🏷️ emits "Cinnamon"; bare "Gold" is never produced (the engine's "Golden" means Wb without silver) |
| Honey | Equivalent to chocolate/chestnut (or to Cinnamon) in Tonkinese (American term) | Two senses: a/a b/b D/- or a/a bl/bl D/-, both on cb/cs (mink) | 🏷️ emits "Chocolate Mink" / "Cinnamon Mink" |
| Indigo | Sometimes used to describe dark blue or deep grey | descriptive — a deep shade of blue (a/a B/- d/d?) | 📖 descriptive shade; engine emits "Blue" |
| Lavender | Warm blue-brown, pinkish frosty grey (dove grey), dilute of Chocolate | a/a b/b d/d | 🏷️ emits "Lilac" |
| Lilac | Lavender | a/a b/b d/d | ✅ "Lilac" |
| Light Amber (Norwegian Forest Cat) | Pink-beige to fawn, with blue-grey nose leather, paw pads and eye rims. Kittens are born blue and brighten as they mature. | ea/ea a/a d/d | ✅ "Light Amber" |
| Light Brown | Old term for cinnamon | a/a bl/bl D/- | 🏷️ emits "Cinnamon" |
| Light chocolate | Describes Burmilla milk chocolate colour | breed term; a/a bl/bl D/-? (source also calls cinnamon "milk-chocolate"; could be a pale b/b) | 🏷️ emits "Cinnamon" (or "Chocolate") |
| Light Lilac | Old term for fawn | a/a bl/bl d/d | 🏷️ emits "Fawn" |
| Mocha | Visually similar to cinnamon, with an orangey tint, and with darker points, found only in Thai cats | cm/cm (cs/cm and cm/c also show mocha); base colour not stated (B/-?) | ✅ cm allele modelled; emitted as "<Colour> Mocha", e.g. "Seal Mocha" |
| Natural | Tonkinese equivalent to sable/seal (American term) | a/a B/- D/- with cb/cs (mink) | 🏷️ emits "Seal Mink" |
| Peach | Australian Mist pink-brown, equivalent to light lilac/fawn. Peach is also seen as a dilute of Russian Blues and may be caramel. | Australian Mist sense: a/a bl/bl d/d; Russian Blue sense: d/d Dm/-? | 🏷️ emits "Fawn" (or a "…-Caramel" name for the Russian Blue sense) |
| Platinum | Burmese/Tonkinese equivalent to lilac/lavender (American term) | a/a b/b d/d with cb/cb (Burmese) or cb/cs (Tonkinese) | 🏷️ emits "Lilac Sepia" / "Lilac Mink" |
| Red | Rich ginger red (poor reds are yellowish due to other genes). | O, D/- (shade modified by other, uncharacterised genes) | ✅ "Red" |
| Russet (Mandalay, Burmese) | Kittens are born brown, but lighten to reddish colour | er/er a/a D/- | ✅ "Russet" |
| Sable | Burmese dark brown (genetically black) (American term) | a/a B/- D/- with cb/cb | 🏷️ emits "Seal Sepia" |
| Seal | Siamese dark brown (genetically black) | a/a B/- D/- with cs/cs | ✅ "Seal Point" |
| Taupe | Caramel dilution of lilac/lavender, also known as lilac/lavender-based caramel | a/a b/b d/d Dm/- | ✅ "Caramel (Taupe)" |
| White | Non-albino white, this is the absence of visible colour. | Wd/- (dominant white; hides the colour genes) | ✅ "White (Dominant White)" |
| Yellow | An old term for a poor quality red. | O, D/- (poor-quality red; shade polygenic) | 📖 descriptive; engine emits "Red" |

> Red, Fawn and Cream are not true self colours as there will always be faint tabby markings even if the cat is genetically not tabby. Breeders work to dissipate the tabby markings and give impression of an unpatterned, self-coloured cat.

## Ticked/Agouti Colours

Genetically, ticking is a tabby pattern but it looks very different: each hair carries several bands of colour, which changes the apparent colour of the cat, and some colours are linked to the cat's sex (important to breeders and exhibitors).

| Name | Source description | Genotype | Calculator |
|---|---|---|---|
| Black | (Experimental colour) The black fur has a distinct "shimmer" due to barely visible ticking, similar effect in Chausie breed has silver-tipped fur. | uncharacterised (experimental) — a/a Ta/-? | ❌ a/a Ta/- is just "Black"; the invisible ticking has no effect in the engine |
| Blue | Blue-grey; the dilute of black | A/- Ta/- B/- d/d | ✅ "Blue Ticked Tabby" |
| Brown | Descriptive term. Equivalent to black (more commonly called Usual or Tawny) | A/- Ta/- B/- D/- | 🏷️ emits "Black Ticked Tabby" |
| Chestnut/Chocolate | Medium-dark brown. | A/- Ta/- b/b D/- | ✅ "Chocolate Ticked Tabby" ("Chestnut" not used) |
| Cream | True (sex-linked) cream, dilute of sex-linked red | O, A/- Ta/- d/d — true sex-linked (O) cream | ✅ "Cream Ticked Tabby" |
| Ebony | Foreign equivalent to black | A/- Ta/- B/- D/- | 🏷️ emits "Black Ticked Tabby" |
| Fawn (Beige) | non sex-linked cream (dilute sorrel) | A/- Ta/- bl/bl d/d — non-sex-linked (eumelanin-based, not O) | ✅ "Fawn Ticked Tabby" ("Beige" and "non sex-linked cream" wording not used) |
| Golden | Any colour ticking on a golden undercoat. This is not the same as "Gold" mentioned further up this page. | A/- Ta/- Wb/- i/i, any base colour | 🏷️ emits "<Colour> Golden Shaded"; shading replaces the pattern word, so "ticked" is lost from the name |
| Ivory (Singapura) | warm beige ticking on ivory | cb/cb A/- Ta/- B/- D/-? (Singapura sepia agouti) | 🏷️ emits "Seal Lynx Sepia" with a note "Pattern under the points: ticked." |
| Lavender (Lilac) | Warm blue-brown, pinkish frosty grey (dove grey), dilute of Chocolate | A/- Ta/- b/b d/d | ✅ "Lilac Ticked Tabby" ("Lavender" not used) |
| Manilla (Celonese/Ceylon Cat) | black/dark ticking on sandy-golden. | A/- Ta/- Wb/-? (breed-specific; ground colour uncharacterised) | 🟡 dark ticking (A/- Ta/-) is modelled; the "sandy-golden" ground is not (Wb is the nearest fit, an inference) |
| Red | Rich ginger red (sex-linked red) | O, A/- Ta/- | ✅ "Red Ticked Tabby" |
| Ruddy | Equivalent to black/brown, also called Usual, Brown, Tawny | A/- Ta/- B/- D/- | 🏷️ emits "Black Ticked Tabby" |
| Sable | Burmese dark brown (genetically black) (American term) | a/a B/- D/- with cb/cb (same as the Self table) | 🏷️ emits "Seal Sepia" |
| Seal | Siamese dark brown (genetically black) | a/a B/- D/- with cs/cs (same as the Self table) | ✅ "Seal Point" |
| Silver | Any colour ticking on a silver undercoat | A/- Ta/- I/-, any base colour | ✅ "Black Silver Ticked Tabby" (also "Blue Silver …", "Cameo Ticked Tabby" on red) |
| Sorrel (Abyssinian) | Equivalent to cinnamon, non sex-linked red. | A/- Ta/- bl/bl D/- | 🏷️ emits "Cinnamon Ticked Tabby" |
| Taupe | Caramel dilution of lilac/lavender | A/- Ta/- b/b d/d Dm/- | ✅ "Caramel (Taupe) Ticked Tabby" |
| Tawny (Abyssinian) | Abyssinian/Somali: Equivalent to black/brown, also called Usual, Brown, Ruddy; it is also the ticked sandy/golden colour found in some wild/domestic hybrid breeds | Abyssinian sense: A/- Ta/- B/- D/-; hybrid-breed sense: wild-derived (sandy/golden ticking) | 🏷️ Abyssinian sense emits "Black Ticked Tabby"; the hybrid-breed sense is not modelled |
| Usual (Abyssinian) | Equivalent to black/brown, also called Ruddy, Brown, Tawny | A/- Ta/- B/- D/- | 🏷️ emits "Black Ticked Tabby" |
| White (Suqutranese) | Suqutranese (white Somali-type): pure white, translucent silver-white bands on hair visible in good light as sparkling effect | Wd/-? (hides a ticked colour); genetics uncharacterised | 🟡 white is modelled as "White (Dominant White)"; the translucent silver-white banding is not |

## Tabby Colours

Tabby means dark markings (stripes, swirls, spots) on a paler background; the stripe colour is solid to the hair root while the background colour is agouti (each hair banded), and different breeds may use different names for the same colour.

*Calculator names below use "Mackerel" as the example pattern word; the engine substitutes Classic, Spotted, Broken Mackerel or Ticked as set by the pattern genes.*

| Name | Source description | Genotype | Calculator |
|---|---|---|---|
| Amber Tabby (Norwegian Forest Cat) | Black markings on apricot background at birth. The black markings brighten to reddish-brown or cinnamon at maturity. The nose is pink and the paw pads and eye rims are brown. | ea/ea A/- D/- | ✅ "Amber Mackerel Tabby" |
| Blue Tabby | cream/ivory-blue base, slate blue markings | A/- B/- d/d | ✅ "Blue Mackerel Tabby" |
| Brown (Black, Ebony) Tabby | coppery-brown base, black markings | A/- B/- D/- | ✅ "Black Mackerel Tabby" ("Brown" and "Ebony" not used) |
| Chocolate (Chestnut) Tabby | cream base, milk-chocolate brown markings | A/- b/b D/- | ✅ "Chocolate Mackerel Tabby" |
| Cameo Tabby | cream base, pale red markings (aka Red-Silver Tabby) | O, A/- I/- D/- | ✅ "Cameo Mackerel Tabby" |
| Caramel Tabby | cream base, biscuit-colour markings, due to presence of dilute + dilute modifier genes | A/- d/d Dm/- (B/- = blue-caramel, b/b = lilac-based, bl/bl = fawn-caramel) | ✅ "Caramel (Taupe) Mackerel Tabby" (lilac-based), "Blue-Caramel …", "Fawn-Caramel …" |
| Chestnut Tabby | ivory base, medium-dark brown markings | A/- b/b D/- | 🏷️ emits "Chocolate Mackerel Tabby" |
| Chocolate Tabby | ivory base, medium-dark brown markings (= Chestnut Tabby) | A/- b/b D/- | ✅ "Chocolate Mackerel Tabby" |
| Cinnamon Tabby | pale brown base, cinnamon markings | A/- bl/bl D/- | ✅ "Cinnamon Mackerel Tabby" |
| Cream Tabby | pale cream base, fawn/buff markings | O, d/d (tabby always shows on red) | ✅ "Cream Mackerel Tabby" (needs A/-; a/a gives plain "Cream") |
| Fawn Tabby | pale pink-beige base, lilac markings | A/- bl/bl d/d | ✅ "Fawn Mackerel Tabby" |
| Golden Tabby | tabby on golden undercoat (see chinchilla/shaded section) e.g. Chocolate Golden Tabby etc | A/- Wb/- i/i, any base colour | 🟡 golden undercoat is modelled (Wb without I) but emitted as "<Colour> Golden Shaded"; degree of tipping that separates golden tabby from golden shaded is not modelled |
| Lavender (Lilac) Tabby | milky cream base, frosty grey markings | A/- b/b d/d | ✅ "Lilac Mackerel Tabby" |
| Light Amber Tabby (Norwegian Forest Cat) | Blue markings on apricot background at birth. The blue markings brighten to pink-beige to fawn at maturity. The nose is pink and the paw pads and eye rims are blue-grey. | ea/ea A/- d/d | ✅ "Light Amber Mackerel Tabby" |
| Red Tabby | pale red base, deep red markings | O, D/- (tabby always shows on red) | ✅ "Red Mackerel Tabby" (needs A/-; a/a gives plain "Red") |
| Silver Tabby | silver base, black markings, aka Black Silver Tabby. Silver Tabbies with coloured markings on a silvery background are called Blue Silver, Red Silver (aka Cameo Tabby) etc. | A/- I/- B/- D/- (black silver); other bases give Blue Silver, Cameo… | ✅ "Black Silver Mackerel Tabby" |

## Equivalent Names Table

The source gives no intro text; the table lines up the eight basic colours against the names used by five breed groups. Genotype is that of the Full Expression row.

| Genotype | Full Expression | Sepia (Burmese) | Mink (Tonkinese) | Pointed (Siamese) | Abyssinian/Somali | Australian Mist |
|---|---|---|---|---|---|---|
| B/- D/- | Black/Brown (in tabbies)/Ebony | Brown/Sable/Seal Sepia | Sable/Natural Mink | Sable/Seal | Usual/Tawny/Ruddy/Brown | Brown |
| B/- d/d | Blue | Blue/Blue Sepia | Blue | Blue | Blue | Blue |
| b/b D/- | Chocolate/Chestnut/Brown | Chocolate/Champagne Sepia | Chocolate/Champagne Mink | Chocolate | Chocolate | Chocolate |
| b/b d/d | Lilac/Lavender/Frost | Lilac/Platinum Sepia | Lilac/Platinum Mink | Lilac/Platinum | Lavender | Lilac |
| bl/bl D/- | Cinnamon | Cinnamon/Cinnamon Sepia | Cinnamon/Honey Mink | Cinnamon | Red/Sorrel | Gold |
| bl/bl d/d | Fawn/Light Lilac | Fawn/Fawn Sepia | Fawn | Fawn | Fawn/Beige/Dilute Sorrel (non sex-linked) | Peach |
| O, D/- | Red | Red/Red Sepia | Red | Red | Sex-linked red | Red |
| O, d/d | Cream | Cream/Cream Sepia | Cream | Cream | Sex-linked cream | Cream |

**Names the calculator currently emits from this table:** Black (as "Seal" once pointed: "Seal Sepia", "Seal Mink", "Seal Point"), Blue, Chocolate, Lilac, Cinnamon, Fawn, Red and Cream, each with the Sepia/Mink/Point suffix as the C genotype dictates (e.g. "Blue Sepia", "Lilac Mink", "Cream Point") and, for the Abyssinian/Somali column, with "Ticked Tabby" (e.g. "Black Ticked Tabby"). It never emits any other name in the table: Brown, Sable, Natural, Ebony, Chestnut, Champagne, Frost, Lavender, Platinum, Honey, Light Lilac, Beige, Usual, Tawny, Ruddy, Sorrel, Dilute Sorrel, "sex-linked red/cream", Gold or Peach.

## Colour glossary

Plain-English definitions of the older terms and concepts used in the colour tables above.

| Term | Meaning | Genotype | Calculator |
|---|---|---|---|
| Solid/Self | The cat is a single colour; the individual hairs are one colour with no agouti banding on the hairs. | a/a (red excepted: O always shows faint tabby) | ✅ "solid (non-agouti)"; named by plain colour with no pattern word, e.g. "Black" |
| Agouti | Refers to the several bands of colour (ticking) on a single hair e.g. on Abyssinian cats, ticked tabbies or in the pale areas of a tabby cat. Also refers to a cat where the whole coat comprises ticked fur without a tabby pattern. | A/- (banded hairs); whole-coat ticked: A/- Ta/Ta | ✅ A/- is "agouti — tabby shows"; whole-coat ticked is named "Ticked Tabby", never "Agouti" |
| Maltesing (Dilution) | Old term for colour dilution e.g. the dilute of black is blue, of red is cream (grey). | d/d | ✅ produces Blue, Lilac, Fawn, Cream; the word "Maltesing" is not used |
| Caramelising (Dilute Modifier) | Old term for a dilute modifier that affects diluted colours e.g. caramelised blue is caramel (blue-based caramel, lilac-based caramel etc), cream + dilute modifier is apricot. | d/d Dm/- | ✅ "Blue-Caramel", "Caramel (Taupe)", "Fawn-Caramel", "Apricot" |
| Sepia (Singapura) | The 'old ivory' colour of the Singapura cat. | cb/cb A/- Ta/-? (Singapura sepia agouti; inferred) | 🟡 sepia (cb/cb) is modelled; the "old ivory" breed shade is not |
| Yellow (historical) | old term for a poor-quality red / sandy-coloured red. | O, D/- (poor-quality red; shade polygenic) | 📖 descriptive; engine emits "Red" |

## Name collisions

Names that mean different things in different breeds, registries or tables of the source. Rows marked (BS) come from the Breed-Specific Tabby/Spotted Terms table, and (FCP) from Future Colour Possibilities; neither is transcribed in this file.

| Name | Meaning A | Meaning B | Meaning C | Where |
|---|---|---|---|---|
| Brown | Old term for Chocolate; also in "Chocolate/Chestnut/Brown" | Black: Burmese "Brown" ("Sable" in America), "Brown (Black, Ebony) Tabby" (coppery-brown base, black markings), ticked "Brown" = Usual/Tawny, "Black/Brown (in tabbies)/Ebony", Australian Mist "Brown" | — | Self; Ticked; Tabby; Equivalent Names (rows 1 and 3) |
| Gold / Golden | Gold = cinnamon in some breeds (Australian Mist column also uses "Gold" for cinnamon) | Golden = ticking or tabby on a golden undercoat; the Ticked table warns it "is not the same as Gold" | "Gold" (Australian Mist, California Spangled) with no colour given (BS); Ocicat "Golden Spotted" = bright Cinnamon on Ivory (BS) | Self; Ticked; Tabby; Equivalent Names; BS |
| Mink | Tonkinese colour class: the "Mink (Tonkinese)" column (e.g. "Sable/Natural Mink") | Bengal "Mink": black spots/rosettes on mahogany (BS) | — | Equivalent Names; BS |
| Sable / Seal / Natural | Burmese dark brown, genetically black (American term); "Brown/Sable/Seal Sepia" | Siamese dark brown, genetically black; "Sable/Seal" in the Pointed column | Tonkinese "Natural" = sable/seal; "Sable/Natural Mink" | Self; Ticked; Equivalent Names |
| Peach | Australian Mist pink-brown = light lilac/fawn | Dilute of Russian Blues, "may be caramel" | Australian Mist "a misty pink base with darker markings" (BS); overlaps Apricot's "pink-brown" | Self; Equivalent Names; BS |
| Sorrel / Red (Abyssinian) | Sorrel = cinnamon, "non sex-linked red"; "Red/Sorrel" sits on the Cinnamon row | Red = sex-linked red ("Sex-linked red" row) | "Dilute sorrel" = Fawn = "non sex-linked cream" | Ticked; Equivalent Names |
| Chestnut | Oriental equivalent to chocolate, medium-dark brown | Chestnut Tabby / Chocolate Tabby: ivory base, medium-dark brown markings | "Chocolate (Chestnut) Tabby": cream base, milk-chocolate brown markings | Self; Ticked; Tabby |
| Honey / Champagne | Honey = chocolate/chestnut in Tonkinese | Honey = cinnamon ("Cinnamon/Honey Mink"; also the Self row's "(or to Cinnamon)") | Champagne = chocolate in Burmese/Tonkinese ("Chocolate/Champagne Mink") | Self; Equivalent Names |
| Fawn / Cream | Fawn = hot cream, = Light Lilac (dilute cinnamon); "historically a biscuity colour" | Ticked Fawn = "non sex-linked cream (dilute sorrel)", set against Cream = "true (sex-linked) cream" | Fawn Tabby shown with lilac markings on a pale pink-beige base | Self; Ticked; Tabby |
| Lavender / Lilac | Lilac = "Lavender"; Lavender = dilute of Chocolate | Abyssinian/Somali column says "Lavender" where the others say "Lilac"/"Platinum"; "Frost" is the American alternative | "Light Lilac" = old term for fawn | Self; Ticked; Tabby; Equivalent Names |
| Caramel / Taupe | Caramel = blue/lilac/fawn + dilute modifier, "cafe-au-lait (biscuit colour)" | Taupe = specifically the lilac/lavender-based caramel | Fawn is also "historically a biscuity colour": same descriptor, no dilute modifier | Self; Ticked; Tabby |
| Apricot | Pink-brown or hot cream: cream + dilute modifier | Amber/Light Amber Tabby kittens have an "apricot background at birth" (E series, no modifier) | Amber self = "bright apricot to cinnamon" | Self; Tabby |
| Tawny | Abyssinian/Somali: black/brown (= Usual, Ruddy, Brown) | Ticked sandy/golden colour of some wild/domestic hybrid breeds | — | Ticked |
| Yellow | Old term for a poor-quality red | "True yellow (as in palomino horse)"; historically sandy-coloured red (FCP) | — | Self; FCP |
| Bronze | Egyptian Mau "Bronze Spotted" = Chocolate Spotted Tabby (BS) | Ocicat "Cinnamon-Golden (Bronze) Spotted" = dark Cinnamon on Gold/Honey/Ivory (BS) | California Spangled "Bronze", no colour given (BS) | BS |

## Modelling notes

- Core colour set is covered: every genuine colour in the Self, Ticked and Tabby tables resolves to O × B × D (+ Dm, E-series, I, Wb), and the engine already generates the canonical names (Black, Chocolate, Cinnamon, Blue, Lilac, Fawn, Red, Cream, Caramel (Taupe), Blue-Caramel, Fawn-Caramel, Apricot, Amber, Light Amber, Russet).
- Naming-only rows (16 Self, 9 Ticked, 1 Tabby): a dialect layer keyed on (canonical colour × C-locus state × pattern) → display name would cover them. Dialect pools visible in this file (my grouping): Burmese/Tonkinese American terms (Sable, Natural, Champagne, Platinum, Honey); Oriental/Foreign (Ebony, Chestnut); Abyssinian/Somali (Usual, Ruddy, Tawny, Sorrel, Lavender, "sex-linked" red/cream); Australian Mist (Brown, Gold, Peach); historical (Beige, Light Brown, Light Lilac, Yellow); American (Frost).
- The layer must key on C as well as colour: Sable, Seal and Natural are the same pigment (B/- D/-) differing only by the C genotype (cb/cb, cs/cs, cb/cs). The Equivalent Names columns map to Sepia = cb/cb, Mink = cb/cs, Pointed = cs/cs and Abyssinian/Somali = ticked (A/- Ta/-); this is my inference, and the source does not state a genotype for the Australian Mist column.
- Sex-linked vs non-sex-linked is already kept apart: Cream is O, d/d while Fawn is bl/bl d/d. The Abyssinian dialect's "Red" (= cinnamon/sorrel) versus "sex-linked red" needs the dialect layer; the engine's "Red" always means O.
- Genuinely unmodelled: experimental shimmer Black (a/a Ta/- is invisible in the engine); hybrid-breed "tawny" (wild-derived); Singapura "ivory"/Manilla "sandy-golden" ground colours (breed-specific, uncharacterised; Wb is only a nearest guess); Suqutranese sparkle bands. Show these as a note, not a Mendelian result.
- Polygenic or descriptive: red depth ("poor reds are yellowish due to other genes") and "Yellow" are selection-quality effects, best shown as a range or note; Indigo and Light chocolate are shade descriptions (Indigo ~ a deeper blue; Light chocolate probably cinnamon or a pale chocolate).
- Golden Tabby versus Golden Shaded differ by degree of tipping, which the engine does not model (see [Silver, golden & shading](03-silver-golden-shading.md)).
- Tabby and Ticked rows are written A/- and A/- Ta/- respectively; the pattern word comes from the Mc/Sp/Ta layer. Ta/Ta gives the no-striping Abyssinian look and Ta/ta leaves residual barring (an engine note); the source's Ticked/Agouti table is presumably Ta/Ta (inference).
- Faint tabby on Red and Cream (the note under the Self table) is already implemented: pheomelanin patches always show tabby and the engine adds a ghost-markings note for a/a red.
- Mocha is emitted as "<Colour> Mocha" (e.g. "Seal Mocha") rather than as a bare colour; the source's bare "Mocha" would need a dialect alias if wanted. See [Colourpoint, mink, sepia & mocha](05-colourpoint-mink-sepia-mocha.md).

## Source quirks & open questions

- The note under the Self table says Red, Fawn and Cream always show faint tabby markings. That holds for red and cream (pheomelanin) but looks wrong for Fawn as defined in the Self table (dilute cinnamon, eumelanin-based, so a genuinely solid a/a cat). The Ticked table's "Fawn (Beige) = non sex-linked cream (dilute sorrel)" suggests the source mixes Fawn with dilute red (my inference; worth verifying).
- Chocolate/Chestnut tabby: "Chocolate (Chestnut) Tabby" says cream base with milk-chocolate brown markings, but "Chestnut Tabby" and "Chocolate Tabby" (the latter "= Chestnut Tabby") both say ivory base with medium-dark brown markings. The table is also out of alphabetical order (Cameo sits after Chocolate (Chestnut)); source order kept.
- Nose leather contradicts itself: Self says Amber has "brown nose leather" and Light Amber "blue-grey nose leather", but the Tabby rows say the nose is pink and only the paw pads and eye rims are brown / blue-grey.
- Fawn Tabby is described with "lilac markings" (expected fawn markings); possible typo, unresolved. Cream Tabby has "fawn/buff markings" on a pale cream base, which blurs Cream and Fawn.
- Honey is defined in the Self table as chocolate/chestnut (or Cinnamon), but the Equivalent Names table puts "Honey Mink" on the Cinnamon row and "Champagne Mink" on the Chocolate row.
- Equivalent Names: "Red" appears in the Abyssinian/Somali column for two different colours (Cinnamon row "Red/Sorrel" and the Red row "Sex-linked red"); "Brown" is listed in both the Black row (in tabbies) and the Chocolate row; the Mink column leaves Fawn, Red and Cream as bare names with no "Mink". The source has six columns (not seven), plus the Genotype column added here, and no yellow intro box.
- Apricot ("pink-brown or hot cream") and Peach ("Australian Mist pink-brown", possibly caramel) use near-identical descriptors for what are presented as different colours.
- Mocha is "visually similar to cinnamon, with an orangey tint, darker points, found only in Thai cats", but the calculator describes cm as a pale, even colour with soft points (Burmese "Mocha/Bangkok"); the base colour it sits on is not stated.
- Lilac is defined only as "Lavender" (circular); the substance is under Lavender. Light chocolate ("Burmilla milk chocolate") overlaps Cinnamon's own "Milk-chocolate (reddish)" description.
- Ticked table: "Black (Experimental colour)" gives no genotype and may be a/a with ticking or an A/- cat with very dark banding. "Golden" warns it differs from "Gold", yet the Self table's Gold is just a cinnamon synonym. Spellings "Celonese" (Manilla) and "Suqutranese" (White) are kept as printed and are unverified. "Pure white" is odd alongside "translucent silver-white bands".
- Singapura appears twice with different colour names: "Sepia (Singapura)" = 'old ivory' in the glossary versus "Ivory (Singapura)" = warm beige ticking on ivory in the Ticked table.
- Same-name rows repeated across tables with slightly different wording: Sable, Seal, Blue, Cream, Red, Ebony, Taupe, Lavender (Lilac) and Chestnut/Chocolate appear in both Self and Ticked tables.

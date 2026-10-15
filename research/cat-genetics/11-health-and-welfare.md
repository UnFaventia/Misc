# Health & welfare index

> **What this is:** every health-linked trait mentioned anywhere in these notes, in one place, with how the calculator handles it now. The detail lives in the linked topic files; this is the cross-cutting view, and the source list for future warnings.  
> **Calculator status:** ✅ `Wd` deafness and `Hp/Hp` ectodermal dysplasia are warnings today, in both single-cat and litter mode. Everything else below is ❌.  
> **Related:** [DBE](07-dominant-blue-eye.md) · [ears, skull & brain](09-ears-skull-and-brain.md) · [eyes](06-eye-colour-and-shape.md) · [white](04-tortie-white-van.md) · [conformation](08-conformation.md) · [coverage map](00-coverage-map.md)

## Display rule: how the calculator handles health & lethality

*Set by the calculator's owner (2026-10-15). It applies to every gene below and to any gene added later.*

1. **Input is never restricted.** Any genotype, any pairing, whatever its health consequences.
2. **Output is never filtered.** Every kitten genotype a pairing can produce appears in the litter at its true Mendelian odds. That includes lethal and severely affected combinations. Lethal kittens are **not** silently dropped or hidden.
3. **Health goes in an obvious box attached to the result it concerns:** next to the single-cat result, and on the kitten card in a litter. It isn't buried in the notes list or only visible after a click. The box says:
   - **What this combination causes:** the extra or additional health problems of this particular genotype.
   - **Whether pairings that can produce it are recommended against,** and the safer pairing that avoids it.
   - **Lethality, where it applies,** e.g. "these kittens die in utero" or "die at or soon after birth", so it's plain they'd never be born or never survive.

**The pattern to model, from the owner's bearded-dragon experience:**
- **The rule:** *leatherback* (one copy of the scale mutation) is bred only to normal/wild-scaled dragons.
- **Why:** leatherback × leatherback gives ¼ *silkbacks*, homozygotes with no scales at all, just skin.
  - Their own claws damage that skin easily, and as ectotherms they heal slowly.
  - Even the minimal UVA/UVB they need to prevent MBD gives them sunburn and skin cancer.
  - Shedding often goes wrong, with retained shed constricting digits and tails and needing human removal.
  - The result is a lower quality of life and a shorter lifespan even with experienced keepers, and few buyers can meet that husbandry.
- **The parallel in these notes:** the heterozygote is the wanted look, and the homozygote is the welfare problem. That's DBE^ALT (blue eyes / white and often deaf), Hp (Peterbald / ectodermal dysplasia) and Wd. The Altai breeders' "blue × non-blue, preferably green-eyed" rule ([07](07-dominant-blue-eye.md#altai-altay-history)) is the leatherback rule for cats.

**Where the calculator stands today:**

| Rule | Now | Gap |
|---|---|---|
| Any input | ✅ every locus accepts every genotype, **except** an XXY tom as sire: `cross()` refuses it ("XXY toms are usually sterile") | Owner's call: keep the refusal, or allow it with a box ("XXY toms are almost always sterile — this litter is hypothetical") |
| Litter unfiltered | ✅ nothing is dropped. But no lethal genotypes are modelled yet, so this hasn't been tested | Must stay true when lethal genes arrive (DBE^RE/RE, DBE^CEL/CEL, ALX1, any Manx-type gene) |
| A box next to the result | 🟡 single cat: warnings are ⚠ items in the notes list. Litter: a pairing-warning list above the kittens, a one-line ⚠ on each kitten card, and chips in the kitten detail | A distinct, styled box per result |
| Pairing advice | ❌ warnings say *what*, never "pair with X instead" | Add a "safer pairing" line from the table below |
| Lethality wording | ❌ none modelled yet | Add a lethal class: "dies in utero", "dies at birth" |

*Optional idea (mine, not part of the owner's rule):* when a litter includes lethal classes, add a second "born alive" odds column renormalised over the survivors. For example, if ¼ die in utero, the live-born ratios are ×4/3. Breeders see live-born ratios in real litters (the Manx 2:1 is the textbook case). The full Mendelian odds stay the primary display.

## Gene-linked conditions

| Trait | Gene / allele | Inheritance | Problem | Notes in | Calculator |
|---|---|---|---|---|---|
| Dominant White | KIT `Wd` (retroviral insertion) | Dominant (epistatic) | **Deafness**, one or both ears, especially on blue-eyed sides; higher risk in `Wd/Wd` | [04](04-tortie-white-van.md), [07](07-dominant-blue-eye.md#mechanism) | ✅ warning |
| White spotting | KIT `wS` (retroviral insertion) | Dominant, polygenic amount | **No deleterious phenotype described** (Abitbol 2024). But the more white around the eyes and ears in a bicolour, the more likely it's deaf. A white-from-spotting cat that had a colour smudge as a kitten should hear normally, even with blue eyes | [06](06-eye-colour-and-shape.md#modelling-notes), [04](04-tortie-white-van.md) | ❌ no hearing note for high-grade `Ws` |
| White-cat deafness, background | Pleiotropic major gene + polygenes | — | Experimental white colony: **67% deaf** (h² 0.55) and **29% partial hearing** (h² 0.75). BAER testing is used by many European breeders | [07](07-dominant-blue-eye.md#mechanism) | ❌ (info) |
| DBE^RE (Rociri Elvis) | PAX3 `c.937C>T` | Dominant | **Deafness in heterozygotes**; homozygote never seen → **presumed lethal** | [07](07-dominant-blue-eye.md) | ❌ |
| DBE^CEL (Roxi) | PAX3 FERV1 LTR insertion | Dominant | Heterozygotes BAER-normal. The only homozygote was **white, with a cleft palate, and died at birth** | [07](07-dominant-blue-eye.md) | ❌ |
| DBE^ALT (Fyodor/Seymour) | PAX3 RD-114 LTR insertion | Dominant | Homozygotes viable, white or van-like, **often deaf**. Heterozygote hearing assumed normal (no BAER) | [07](07-dominant-blue-eye.md) | ❌ |
| DBE^CEL/ALT compound | PAX3 | — | **White and deaf** (two kittens, Topaz) | [07](07-dominant-blue-eye.md) | ❌ |
| DBE, Igor line | Unknown allele | Dominant | **Deaf cats reported** (no BAER) | [07](07-dominant-blue-eye.md) | ❌ |
| Ojos Azules (extinct) | Unknown (PAX3 suspected) | Dominant | Homozygotes: **white kittens with cranial deformities** | [07](07-dominant-blue-eye.md#ojos-azules-it-isnt-dbe) | 🚫 historic |
| Toyger rounded ears | **GDF7** deletion | **Recessive** | Forebrain commissural malformation, ventriculomegaly, interhemispheric cysts, hydrocephalus; clumsy gait; **affected females infertile** | [09](09-ears-skull-and-brain.md) | ❌ |
| Burmese craniofacial malformation | **ALX1** | *Not given in notes* | Craniofacial malformation with **meningoencephalocele** | [09](09-ears-skull-and-brain.md#other-skull--brain-items-in-the-notes) | ❌ |
| Dominant hairless (Peterbald/Donskoy) | `Hp` (likely FOXI3) | Dominant | `Hp/Hp`: feline ectodermal dysplasia (poor teeth, impaired sweating and lactation) | calculator blurb | ✅ warning |
| Albinism | TYR `ca` (blue-eyed) / `c` (pink-eyed), per Schar & Hartwell 2023 | Recessive | **Photosensitivity** (Pangur). Arises in Siamese/Orientals **through inbreeding** | [06](06-eye-colour-and-shape.md#albinism) | 🟡 note says pale eyes; no photosensitivity warning; one albino allele only |
| Chediak-Higashi syndrome | *Not given in notes* | *Not given* | Pale irises, under-pigmented retinas, pale coat; seen in **Blue Smoke Persians** | [06](06-eye-colour-and-shape.md#chediak-higashi-syndrome) | ❌ |
| XXY tortie tom | Sex chromosomes | Sporadic | Usually **sterile** | [10](10-rare-and-future.md) | ✅ note; refused as a litter parent |

## Shape & selection-linked problems

| Trait | Basis | Problem | Notes in | Calculator |
|---|---|---|---|---|
| Brachycephaly (peke/ultra-type faces) | Polygenic / selection | Malformed skull-caps and facial bones, abnormal teeth, compressed or absent tear ducts, respiratory abnormalities; protruding lower jaw | [09](09-ears-skull-and-brain.md), [08](08-conformation.md#head-face--jaw) | ❌ |
| Radial hypoplasia | *Genetic; details not given* | "Twisty cat / squitten / kangaroo cat" | [08](08-conformation.md#modified-types--abnormalities-diagram) | ❌ |
| Tucked up (2), the "cabbit" | *Not given* | Loose skin missing between belly and haunch | [08](08-conformation.md) | ❌ |
| Inbreeding depression | Pedigree structure | Altai needed a European Shorthair outcross at G3. Albinism surfaced via inbreeding. Pangur's parents were half-siblings | [07](07-dominant-blue-eye.md), [06](06-eye-colour-and-shape.md) | ❌ |

## Not heritable

- **Odd eyes from injury or illness**, somatic-mutation "birthmark" odd eyes, and mosaic odd eyes in coloured cats ([06](06-eye-colour-and-shape.md#odd-eyes-heterochromia-iridium)).
- **The Danish green kitten**: copper contamination ([10](10-rare-and-future.md)).
- **Point colour shifts** from fever, environmental temperature, or bandaging an injured leg ([05](05-colourpoint-mink-sepia-mocha.md)).

## Pairing warnings litter mode could add

Litter mode already gathers kitten-level warnings and lifts them to pairing-level ones (e.g. ¼ `Wd/Wd`). Candidate additions:

Each row is box content under the [display rule](#display-rule-how-the-calculator-handles-health--lethality). The litter is still shown in full.

| Pairing | Warning | Safer pairing | Basis |
|---|---|---|---|
| DBE × DBE, any alleles | ¼ homozygous or compound: white, deafness, possible lethality | DBE × **non-DBE**, preferably green-eyed | Altai breeders' guidance (source) |
| CEL × ALT ("Roxi-origin × Seymour-origin") | ¼ compound heterozygotes: white and deaf | Never cross the lines. Each DBE allele × non-DBE | Abitbol 2024 breeder warning (source) |
| RE × RE | ¼ presumed lethal | RE × non-DBE. Heterozygotes still carry the deafness association | Inference from source |
| CEL × CEL | ¼ white; the only recorded kitten had a cleft palate and died at birth | CEL × non-DBE | Inference from source |
| `Wd` × `Wd` | ¼ `Wd/Wd`: higher deafness risk (already shown) | `Wd` × non-white; BAER-test whites | My inference; BAER from source |
| `Hp` × `Hp` | ¼ `Hp/Hp`: feline ectodermal dysplasia (already shown) | `Hp` × normal-coated | My inference |
| GDF7 carrier × carrier | ¼ affected: brain malformation, clumsy, infertile females | Carrier × DNA-tested non-carrier. No affected kittens; ½ carriers | My inference; a DNA test exists (source) |
| ALX1 carrier × carrier (if verified) | ¼ lethal craniofacial defect | Carrier × non-carrier | Lead |
| `cm/cm` × `cm/cm` (Bangkok-Mocha) | Precaution only, no known defect | `cb/cm × cs/cm` or `C/cm × cb/cm` | Doug Schar (breeder precaution) |
| `Ws/Ws` high white + blue eyes | Deafness-risk note (soft; polygenic) | BAER-test | Source (BAER), polygenic |

## Colour breeding & closed gene pools

*From Doug Schar in Schar & Hartwell 2023 (messybeast). These are a breeder's observations and opinions, labelled as such in the source. See [05](05-colourpoint-mink-sepia-mocha.md#bangkok-mocha-schar--hartwell-2023).*

- **The thesis:** inbreeding outside Thailand is bad, and so is **colour breeding**: selecting hard for one colour and culling the rest. "When people select for ONE physical attribute, they are also selecting for physical attributes that one cannot see. Like PRA [progressive retinal atrophy]."
- **The Korat example:**
  - The five founding Korats imported to the US were Thai cats carrying `cb`, `cs` and chocolate.
  - Any kitten that wasn't Korat Blue (Siamese, Burmese, chocolate or lilac) was excluded from the gene pool. One breeder's motto: "Blue and Only Blue".
  - Once they had "purified them like white flour", American Korats developed what Doug calls "**kitty ALS**".
  - *Lead to verify:* the inherited neurological diseases documented in Korats are GM1 and GM2 gangliosidosis. Whether "kitty ALS" means those is unconfirmed.
- **The registry problem:** natural Thai breeds outside Thailand aren't bred the way they breed in their native lands, which leads to closed gene pools and sick cats. CFA won't let you use an imported Thai Siamese in a breeding programme. Doug is considering a non-show **Natural Cat Breed Association** registry.
- **Bangkok-Mocha `cm/cm` caution:**
  - No abnormalities detected so far.
  - He recommends producing cm/cm from `cb/cm × cs/cm` or `C/cm × cb/cm`, rather than cm/cm × cm/cm.
  - He frames it as precaution, by analogy with parrot mutation breeding, not evidence of harm.

**For the calculator:** nothing here is a single-gene warning. Possible soft notes:
- a "colour-restricted gene pool" caution on breed presets
- a gentle note on cm/cm × cm/cm pairings, explicitly marked as breeder precaution

## Open questions

- Inheritance of **Chediak-Higashi** in cats, and its gene. *Lead: LYST in other species; verify.*
- **ALX1** inheritance and heterozygote phenotype ([09](09-ears-skull-and-brain.md)).
- Hearing data for **DBE^ALT** heterozygotes (no BAER yet).
- Whether **radial hypoplasia** is in scope at all. It's a skeletal trait, not a coat trait.

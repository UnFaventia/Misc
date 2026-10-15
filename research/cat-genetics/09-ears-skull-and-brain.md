# Ears, skull & brain: the Toyger rounded-ear mutation (GDF7) and friends

> **Sources:**
> - Sarah Hartwell, *Small Rounded Ears Mutation* (messybeast.com, 2016–2023)
> - Keating MK, Sturges BK, Siso S, Wisner ER, Creighton EK, Lyons LA. *Characterization of an Inherited Neurologic Syndrome in Toyger Cats with Forebrain Commissural Malformations, Ventriculomegaly and Interhemispheric Cysts.* J Vet Intern Med 2016;30(2):617–626
> - Yu Y, Creighton EK, Buckley RM, Lyons LA, 99 Lives Consortium. *A Deletion in GDF7 is Associated with a Heritable Forebrain Commissural Malformation Concurrent with Ventriculomegaly and Interhemispheric Cysts in Cats.* Genes 2020;11:672
> - User photos: the Italian founder male; the F2 kittens
>
> **Calculator status:** ❌ not modelled. The only ear locus is `Cu` (curl). There's no GDF7, no ALX1, and no brachycephaly.  
> **Images** (all messybeast.com; credits in [img/README](img/README.md)): [toyger-small-rounded-ears.jpg](img/toyger-small-rounded-ears.jpg)  
> **Related:** [conformation](08-conformation.md) · [health index](11-health-and-welfare.md) · [coverage map](00-coverage-map.md)

## At a glance

- **The ears were the symptom.** The small, rounded ears and domed head prized in one Toyger development line turned out to be the outward sign of a **homozygous GDF7 deletion**. That deletion causes forebrain commissural malformation, ventriculomegaly and interhemispheric cysts, usually with hydrocephalus.
- **Inheritance:** autosomal recessive, not sex-linked. Carriers look normal and are clinically healthy.
- **Affected females never got pregnant**, whether mated to affected, carrier or completely unrelated males. The founder male and the carriers were fertile.
- **Outcome:** the breeder halted the programme and neutered the cats. A DNA test now identifies carriers.
- **For the calculator:** a near-perfect example of a "health-linked shape" locus. It's recessive, testable, has a visible marker, and carries a hard warning.

## How it unfolded

| Step | What happened |
|---|---|
| Founder | A small-eared male, mixed breed with Oriental ancestry (the paper calls him an Oriental), imported **from Italy to the USA** to found a line with small, rounded ears that would make the Toyger look more like a tiger |
| Outcross | Mated to **at least four unrelated mixed-breed females** → only normal-eared kittens |
| Backcross | F1 females back to the founder → a mix of normal and short-eared kittens. Brother × sister matings gave similar results. **Pedigree analysis showed an autosomal recessive trait** |
| Fertility | Short-eared **females showed normal sexual behaviour but never became pregnant**, with affected, carrier or unrelated males. The founder, carrier males and carrier females were fertile |
| The fall | A rounded-ear kitten got a head injury from a fall. Its MRI showed **congenital hydrocephalus**. MRIs of the breeding stock then showed that round ears + domed head went with brain malformations |
| UC Davis (Keating 2016) | **20 related Oriental-derived crossbred Toyger cats** were donated: **7** clinically healthy carriers and **13** affected (neurological signs, short ears, complex brain anomalies). All were MRI-scanned, then euthanised for pathology |
| Gene (Yu 2020) | **43 cats** genotyped. Affected cats were **homozygous for a GDF7 deletion**, which was absent from **192** unaffected cats in the 99 Lives dataset |
| Photos | Short-eared male imported from Italy. F2 generation from Oriental Shorthair crosses backcrossed to the sire: **heterozygotes had a normal Oriental head; homozygotes had unusually short ears and domed heads** |

## The affected (homozygous) phenotype

| System | Findings |
|---|---|
| External | Small, rounded ears; domed head |
| Neurological | "Clumsy"; mildly uncoordinated when walking; **normal** limb reflexes and cranial nerves |
| Imaging & pathology | **Marked ventricular dilatation** (ventriculomegaly) of varying degree · **interhemispheric cysts** · multiple **midline and callosal** (corpus callosum) malformations · **thinning of the cerebral cortex** · brain-surface ridges and furrows much **shallower than normal and abnormally patterned**, with the shallowness tracking how severely the cat was affected · **hydrocephalus** in most |
| Human analogue | Resembles a mild form of **holoprosencephaly (HPE)**, where the brain doesn't properly separate into two hemispheres |
| Chromosomes | No abnormalities |
| Reproduction | Affected females infertile |
| Gene | **GDF7** (Growth Differentiation Factor 7), important in the development of neurons in the mammalian brain |

**Glossary from the source:**
- **Commissural fibres** connect the two brain hemispheres.
- **Ventriculomegaly** means the brain's fluid-filled cavities are enlarged.
- **Interhemispheric cysts** are fluid-filled bodies between the two hemispheres. They're associated with defective development of the **corpus callosum**, the bundle of nerve fibres that lets the left and right sides of the brain communicate.

## Other skull & brain items in the notes

- **Most cat skull and brain malformations occur "out of the blue"**, i.e. sporadically (Keating 2016).
- **Brachycephaly:** a high degree of brachycephaly (short muzzle, flat face) goes with malformed skull-caps, malformed facial bones, abnormal teeth, compressed or absent tear ducts, and/or respiratory abnormalities.
  - See also *peke-faced* in [08](08-conformation.md#head-face--jaw).
  - The tear-shaped eye of ultra-short muzzles is in [06](06-eye-colour-and-shape.md#eye-shapes).
- **Burmese craniofacial malformation with meningoencephalocele**, caused by a mutation in **ALX1** (ALX Homeobox 1). A meningoencephalocele is a sac of fluid, brain tissue and brain membranes pushing through a defect in the skull. *The notes give no inheritance details.*
  - *Lead to verify:* this is usually called the **Burmese head defect**. It's commonly described as lethal in homozygotes, with heterozygotes showing the shortened "contemporary" Burmese face. Likely citation: Lyons et al. 2016, *Dev Biol*, on an ALX1 variant and frontonasal dysplasia in Burmese.

## Modelling notes

*Design suggestions, not source content.*

- **New locus `GDF7`**, alleles `+` / `del`, recessive:
  - **Phenotype for `del/del`:** coat line gets "small rounded ears", and the portrait gets a smaller rounded ear plus a domed skull. The portrait already varies ear geometry for `Cu`.
  - **Warning for `del/del`:** "GDF7 del/del — forebrain commissural malformation, ventriculomegaly, interhemispheric cysts (usually with hydrocephalus); clumsy gait; affected females infertile."
  - **`+/del`:** add to *carried* as "rounded-ear brain defect (GDF7)".
  - **Litter mode:** carrier × carrier → ¼ affected, as a pairing-level warning like Wd/Wd.
- **ALX1 (if verified):** a two-tier warning. Heterozygotes get a shortened face (portrait); homozygotes get a lethal craniofacial defect. In a litter: "¼ not viable".
- **"Trait with a price" flag:** a general UI idea. Mark every selected trait that carries welfare cost (Hp/Hp, Wd/Wd, DBE homozygotes, GDF7, and Fold/Manx if those are ever added) in one consistent style.

## Source quirks & open questions

- **Founder description:** "small-eared male **Oriental** cat" (paper summary) vs "a **mixed breed** cat from Italy, with Oriental ancestry" (later paragraph). Probably both true.
- **Heterozygote look:** the photo caption says heterozygotes had a normal Oriental head. Is there *any* heterozygote phenotype? The notes say carriers had no clinical signs.
- **ALX1:** inheritance and heterozygote phenotype need a source before modelling.

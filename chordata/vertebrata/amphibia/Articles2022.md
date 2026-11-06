# Salamander Regeneration Literature, 2022
 
An annotated, deduplicated bibliography of salamander regeneration publications from 2022, with a reproducible search strategy.
 
> **Scope note:** This is a curated core set of 45 publications plus 7 notable preprints. It is **not** an exhaustive census. Running the database queries below will return more records, mostly lower-profile papers in *Dev Dyn*, *Biomedicines*, *Front Cell Dev Biol*, and Russian/Japanese journals. Use this list as an annotated backbone and the queries to fill the long tail.
 
## Contents
 
- [Summary](#summary)
- [Search strategy](#search-strategy)
- [Key findings](#key-findings)
- [Annotated list by tissue](#annotated-list-by-tissue)
  - [Limb](#limb)
  - [Tail](#tail)
  - [Spinal cord](#spinal-cord)
  - [Brain / CNS](#brain--cns)
  - [Heart](#heart)
  - [Eye / lens / retina](#eye--lens--retina)
  - [Skin / wound healing](#skin--wound-healing)
  - [Methods, resources, reviews, history](#methods-resources-reviews-history)
- [Species cross-index](#species-cross-index)
- [Notable 2022 preprints](#notable-2022-preprints)
- [Caveats](#caveats)
- [Recommendations](#recommendations)
## Summary
 
- The highest-profile 2022 papers were in **brain/CNS**: two back-to-back *Science* papers on axolotl telencephalon regeneration (Wei et al., Stereo-seq; Lust et al., scRNA-seq).
- **Limb** papers were the most numerous, covering positional identity (Tig1), skeletal integration (osteoclasts, "bulky bones"), and blastema signaling (Wnt, Lmx1b, Pde4b/B2FF).
- **Newt** work centered on *Pleurodeles waltl*: heart (epicardium-to-cardiomyocyte conversion, cryo-injury), neurospheres, gene nomenclature, and the October 2022 chromosome-scale genome preprint. *Cynops* work came from the Chiba lab. No 2022 journal paper centered on *Notophthalmus* was found.
## Search strategy
 
### PubMed (title/abstract)
 
```text
(salamander*[tiab] OR axolotl*[tiab] OR Ambystoma[tiab] OR newt*[tiab] OR Pleurodeles[tiab] OR Notophthalmus[tiab] OR Cynops[tiab] OR Urodela[tiab] OR Urodela[mh] OR Ambystoma mexicanum[mh] OR Salamandridae[mh])
AND regenerat*[tiab]
AND ("2022/01/01"[dp] : "2022/12/31"[dp])
```
 
### Web of Science (Core Collection)
 
```text
TS=(salamander* OR axolotl* OR Ambystoma OR newt* OR Pleurodeles OR Notophthalmus OR Cynops OR Urodela) AND TS=(regenerat*)
```
 
Filter: `PY=2022`.
 
### Scopus
 
```text
TITLE-ABS-KEY((salamander* OR axolotl* OR ambystoma OR newt* OR pleurodeles OR notophthalmus OR cynops OR urodela) AND regenerat*) AND PUBYEAR = 2022
```
 
### bioRxiv
 
Full-text search for `axolotl OR newt OR Pleurodeles OR salamander` plus `regeneration`, posted 2022-01-01 to 2022-12-31.
 
### Rules used
 
- **Deduplication:** a paper counts as 2022 if its journal issue/volume year is 2022, or if its version of record appeared online in 2022 with a later issue date. Preprints are counted only in the preprint section unless the version of record also appeared in 2022.
- **"newt\*" caveat:** this term also matches non-amphibian hits (e.g., "Newton"). Screen these manually.
## Key findings
 
1. **Spatial and single-cell atlases reached the CNS.** Before 2022, the main axolotl single-cell work was on the limb (Gerber 2018; Leigh 2018). In 2022 the field gained telencephalon atlases with injury-induced ependymoglia states (Wei; Lust), making brain regeneration a newly tractable, comparative system.
2. **Limb skeletal regeneration is imperfect.** Three independent papers (Riquelme-Guzmán, *eLife*; Kaucka, *Nat Commun*; Polikarpova, *npj Regen Med*) converge: osteoclast resorption is needed for integration, regenerated bones are bulkier, and a stabilized osteotomy does not heal within 9 months.
3. ***Pleurodeles* is becoming the genetically tractable newt.** 2022 brought a standardized gene nomenclature, neurosphere culture, cryo-injury and lineage-tracing heart models, and a chromosome-scale genome preprint.
## Annotated list by tissue
 
Species are given in brackets where not obvious from the title.
 
### Limb
 
#### Axolotl
 
1. **Riquelme-Guzmán C et al.** Osteoclast-mediated resorption primes the skeleton for successful integration during axolotl limb regeneration. *eLife* 11:e79966 (2022). [doi:10.7554/eLife.79966](https://doi.org/10.7554/eLife.79966)
   Amputation triggers osteoclast-driven resorption of calcified skeleton, which is required for integration of the regenerate with the stump. Skeletal abnormalities after regeneration are frequent.
2. **Duerr TJ et al.** A constitutively expressed fluorescent ubiquitination-based cell-cycle indicator (FUCCI) in axolotls for studying tissue regeneration. *Development* 149(6):dev199637 (2022). [doi:10.1242/dev.199637](https://doi.org/10.1242/dev.199637) · [PMID 35266986](https://pubmed.ncbi.nlm.nih.gov/35266986/)
   Transgenic FUCCI axolotl line for live, cell-cycle-resolved imaging of the blastema and other regenerating tissues.
3. **Lovely AM et al.** Wnt signaling coordinates the expression of limb patterning genes during axolotl forelimb development and regeneration. *Front Cell Dev Biol* 10:814250 (2022). [doi:10.3389/fcell.2022.814250](https://doi.org/10.3389/fcell.2022.814250) · [PMID 35531102](https://pubmed.ncbi.nlm.nih.gov/35531102/)
   Wnt modulation alters patterning-gene expression in both limb buds and blastemas.
4. **Oliveira CR et al.** Tig1 regulates proximo-distal identity during salamander limb regeneration. *Nat Commun* 13:1141 (2022). [doi:10.1038/s41467-022-28755-1](https://doi.org/10.1038/s41467-022-28755-1) · Publisher Correction: *Nat Commun* 13:4507, [doi:10.1038/s41467-022-32302-3](https://doi.org/10.1038/s41467-022-32302-3) [axolotl; *Pleurodeles*]
   Tig1 is an RA-responsive cell-surface protein graded along the PD axis; overexpression reprograms distal cells toward proximal identity.
5. **Yamamoto S et al.** *Lmx1b* activation in axolotl limb regeneration. *Dev Dyn* 251(9):1509–1523 (2022). [doi:10.1002/dvdy.476](https://doi.org/10.1002/dvdy.476)
   Dorsal *Lmx1b* in dermal fibroblasts is reactivated in regeneration and accessory limb model (ALM) blastemas independently of epidermal signals, implicating nerves in activating dorsoventral positional memory.
6. **Kaucka M et al.** Altered developmental programs and oriented cell divisions lead to bulky bones during salamander limb regeneration. *Nat Commun* 13:6949 (2022). [doi:10.1038/s41467-022-34266-w](https://doi.org/10.1038/s41467-022-34266-w) · [PMID 36376278](https://pubmed.ncbi.nlm.nih.gov/36376278/) [axolotl; *Pleurodeles*]
   Chondrogenesis and ossification are decoupled in regeneration; together with altered clonal orientation this produces thicker regenerated bones.
7. **Polikarpova A et al.** The specialist in regeneration—the Axolotl—a suitable model to study bone healing? *npj Regen Med* 7:35 (2022). [doi:10.1038/s41536-022-00229-4](https://doi.org/10.1038/s41536-022-00229-4)
   Plate-fixated femur osteotomy in axolotl shows incomplete healing at 9 months, compared with limb amputation and mouse fracture healing.
8. **Riquelme-Guzmán C, Beck T, Edwards-Jorquera S, Schlüßler R, Müller P, Guck J, Möllmert S, Sandoval-Guzmán T.** In vivo assessment of mechanical properties during axolotl development and regeneration using confocal Brillouin microscopy. *Open Biol* 12(6):220078 (2022). [doi:10.1098/rsob.220078](https://doi.org/10.1098/rsob.220078) · [PMID 35728623](https://pubmed.ncbi.nlm.nih.gov/35728623/)
   Cartilage viscoelasticity recovers progressively and is not back to baseline at 30 dpa despite normal morphology.
9. **Glotzer GL, Tardivo P, Tanaka EM.** Canonical Wnt signaling and the regulation of divergent mesenchymal Fgf8 expression in axolotl limb development and regeneration. *eLife* 11:e79762 (2022). [doi:10.7554/eLife.79762](https://doi.org/10.7554/eLife.79762) · PMID 35587651 *(unverified)*
   Canonical Wnt regulates the unusual mesenchymal (rather than AER) *Fgf8* expression in axolotl limbs.
10. **Carbonell-M B, Zapata Cardona J, Delgado JP.** Post-amputation reactive oxygen species production is necessary for axolotl limb regeneration. *Front Cell Dev Biol* 10:921520 (2022). [doi:10.3389/fcell.2022.921520](https://doi.org/10.3389/fcell.2022.921520)
    NOX-dependent ROS after amputation is required for blastema formation; blocking ROS produces a miniature limb.
11. **Hu Y, Pan X, Shi Y, Qiu Y, Wang L, Murawala P, Liu Y, Xing W, Tanaka EM, Fei J-F.** Muscles are barely required for the patterning and cell dynamics in axolotl limb regeneration. *Front Genet* 13:1036641 (2022). [doi:10.3389/fgene.2022.1036641](https://doi.org/10.3389/fgene.2022.1036641) · [PMID 36299593](https://pubmed.ncbi.nlm.nih.gov/36299593/)
    Pax7-CRISPR mutant axolotls lacking limb muscle still pattern and regenerate limbs normally.
#### *Pleurodeles waltl* (with axolotl comparison)
 
12. **Satoh A et al.** An approach for elucidating dermal fibroblast dedifferentiation in amphibian limb regeneration. *Zool Lett* 8:6 (2022). [doi:10.1186/s40851-022-00190-6](https://doi.org/10.1186/s40851-022-00190-6)
    BMP2+FGF2+FGF8 (B2FF) makes a newt dermal fibroblast line multipotent. *Pde4b* is upregulated only in newt (not mouse) cells; rolipram or mosaic *Pde4b* crispants suppress the dermis-to-cartilage transition.
#### *Cynops pyrrhogaster*
 
13. **Yu ZY et al.** The latent dedifferentiation capacity of newt limb muscles is unleashed by a combination of metamorphosis and body growth. *Sci Rep* 12:11653 (2022). [doi:10.1038/s41598-022-15879-z](https://doi.org/10.1038/s41598-022-15879-z)
    Myofiber dedifferentiation in the stump requires both metamorphosis and body growth, explaining the life-cycle switch from stem-cell-based to dedifferentiation-based muscle regeneration.
14. **Chen X et al.** Newtic1 is a component of globular structures that accumulate along the marginal band of erythrocytes in the limb blastema of adult newt, *Cynops pyrrhogaster*. *Biomedicines* 10(11):2772 (2022). [doi:10.3390/biomedicines10112772](https://doi.org/10.3390/biomedicines10112772) · [PMID 36359293](https://pubmed.ncbi.nlm.nih.gov/36359293/)
    Newtic1 localizes to erythrocyte globular structures in the blastema, revising its proposed role.
### Tail
 
15. **Carbonell MB, Zapata Cardona J, Delgado JP.** Hydrogen peroxide is necessary during tail regeneration in juvenile axolotl. *Dev Dyn* 251(6):1054–1076 (2022). [doi:10.1002/dvdy.386](https://doi.org/10.1002/dvdy.386) · [PMID 34129260](https://pubmed.ncbi.nlm.nih.gov/34129260/) [axolotl]
    NOX-derived H₂O₂ is necessary and sufficient for tail regeneration, acting through Akt, Agr2 and Yap1.
    > ⚠️ Online June 2021; 2022 issue.
### Spinal cord
 
16. **Walker SE et al.** Regulation of stem cell identity by miR-200a during spinal cord regeneration. *Development* 149(3):dev200033 (2022). [doi:10.1242/dev.200033](https://doi.org/10.1242/dev.200033) [axolotl]
    miR-200a maintains neural stem cell identity in the regenerating spinal cord; inhibition shifts progenitor fate.
17. **Seki-Omura R et al.** Establishment of neural stem cell culture from the central nervous system of the Iberian ribbed newt *Pleurodeles waltl*. *Dev Growth Differ* 64(9):494–500 (2022). [doi:10.1111/dgd.12820](https://doi.org/10.1111/dgd.12820) · [PMID 36308507](https://pubmed.ncbi.nlm.nih.gov/36308507/) [*Pleurodeles*]
    First neurospheres from post-metamorphic *P. waltl* brain and spinal cord; unlike axolotl neurospheres under standard conditions, these produce oligodendrocytes.
18. **Walker SE, Echeverri K.** Spinal cord regeneration — the origins of progenitor cells for functional rebuilding. *Curr Opin Genet Dev* 75:101917 (2022). [doi:10.1016/j.gde.2022.101917](https://doi.org/10.1016/j.gde.2022.101917) · [PMID 35623298](https://pubmed.ncbi.nlm.nih.gov/35623298/)
    Review of progenitor origins in salamander and fish spinal cord regeneration.
### Brain / CNS
 
19. **Wei X et al.** Single-cell Stereo-seq reveals induced progenitor cells involved in axolotl brain regeneration. *Science* 377(6610):eabp9444 (2022). [doi:10.1126/science.abp9444](https://doi.org/10.1126/science.abp9444) · [PMID 36048929](https://pubmed.ncbi.nlm.nih.gov/36048929/) [axolotl]
    Spatial single-cell atlas of telencephalon development and regeneration; identifies injury-induced reactive ependymoglia that regenerate neurons through a development-like state transition.
20. **Lust K et al.** Single-cell analyses of axolotl telencephalon organization, neurogenesis, and regeneration. *Science* 377(6610):eabp9262 (2022). [doi:10.1126/science.abp9262](https://doi.org/10.1126/science.abp9262) [axolotl]
    Telencephalon atlas with neuron types homologous to mammalian hippocampus and lateral cortex. Regenerative neurogenesis reuses homeostatic neuroblast programs after an injury-specific ependymoglia state.
    > ⚠️ The glutamatergic/GABAergic cluster counts sometimes quoted for this paper come from a commentary, not the paper itself; check before citing.
### Heart
 
21. **Eroglu E et al.** Epicardium-derived cells organize through tight junctions to replenish cardiac muscle in salamanders. *Nat Cell Biol* 24(5):645–658 (2022). [doi:10.1038/s41556-022-00902-2](https://doi.org/10.1038/s41556-022-00902-2) · [PMID 35550612](https://pubmed.ncbi.nlm.nih.gov/35550612/) [*Pleurodeles*]
    Lineage tracing shows epicardial cells convert into cardiomyocytes, at low levels in homeostasis and expanded after cryoinjury, via CLDN6⁺ intermediates whose tight junctions are needed for regeneration.
22. **Uemasu H et al.** Cryo-injury procedure-induced cardiac regeneration shows unique gene expression profiles in the newt *Pleurodeles waltl*. *Dev Dyn* 251(5):864–876 (2022). [doi:10.1002/dvdy.450](https://doi.org/10.1002/dvdy.450) [*Pleurodeles*]
    Establishes a cryoinjury model; regeneration after cryoinjury involves fewer fluctuating genes than after amputation.
23. **Dittrich A et al.** Does metabolism regulate cardiac repair in the regeneration competent axolotl salamander? *FASEB J* 36(S1), abstract R1919 (2022). [axolotl]
    Whole-animal and cardiac respirometry after cryoinjury.
    > ⚠️ Conference abstract only, not a peer-reviewed article. Author list unconfirmed.
### Eye / lens / retina
 
24. **Tsissios G, Sallese A, Chen W, Miller A, Wang H, Del Rio-Tsonis K.** In vivo and ex vivo view of newt lens regeneration. In: *Salamanders: Methods and Protocols*. *Methods Mol Biol* 2562:197–208. [doi:10.1007/978-1-0716-2659-7_13](https://doi.org/10.1007/978-1-0716-2659-7_13) [newt]
    SD-OCT protocol for longitudinal in vivo imaging of lens regeneration from the dorsal iris, with histological correlation.
    > ⚠️ Online October 2022; volume labeled "1st ed. 2023". Tsissios et al., *Differentiation* 132:15–23 (*Pleurodeles* lens) is a 2023 paper and is excluded.
25. **Grigoryan EN.** Self-organization of the retina during eye development, retinal regeneration in vivo, and in retinal 3D organoids in vitro. *Biomedicines* 10:1458 (2022).
    Review covering newt retinal regeneration from RPE.
### Skin / wound healing
 
26. **Kashimoto R et al.** Lattice-patterned collagen fibers and their dynamics in axolotl skin regeneration. *iScience* 25(7):104524 (2022). [doi:10.1016/j.isci.2022.104524](https://doi.org/10.1016/j.isci.2022.104524) · [PMID 35754731](https://pubmed.ncbi.nlm.nih.gov/35754731/) [axolotl]
    The dermal collagen lattice is not reorganized after simple wounding but is reorganized when nerves are present.
### Methods, resources, reviews, history
 
27. **Bölük A, Yavuz M, Demircan T.** Axolotl: A resourceful vertebrate model for regeneration and beyond. *Dev Dyn* 251(12):1914–1933 (2022). [doi:10.1002/dvdy.520](https://doi.org/10.1002/dvdy.520) · [PMID 35906989](https://pubmed.ncbi.nlm.nih.gov/35906989/)
    Broad review: limb staging, signaling, miRNAs, immunity, cancer resistance.
28. **Reiß C.** Cut and Paste: The Mexican Axolotl, Experimental Practices and the Long History of Regeneration Research in Amphibians, 1864–Present. *Front Cell Dev Biol* 10:786533 (2022). [doi:10.3389/fcell.2022.786533](https://doi.org/10.3389/fcell.2022.786533)
    History-of-science review.
29. **Yun MH, Hayashi T, Simon A.** Standardized gene and genetic nomenclature for the newt *Pleurodeles waltl*. *Dev Dyn* 251:911–912 (2022). [doi:10.1002/dvdy.355](https://doi.org/10.1002/dvdy.355) [*Pleurodeles*]
    Community nomenclature standard.
30. **Masselink W et al.** Meeting report: Salamander models in cross-disciplinary biological research meeting. *Dev Dyn* 251(6):906–910 (2022). [doi:10.1002/dvdy.481](https://doi.org/10.1002/dvdy.481)
31. **Tilley L, Papadopoulos SC, Pende M, Fei JF, Murawala P.** The use of transgenics in the laboratory axolotl. *Dev Dyn* 251:942–956 (2022).
    Review of transgenic and CRISPR tools.
32. **Bonett RM et al.** Repeated ecological and life cycle transitions make salamanders an ideal model for evolution and development. *Dev Dyn* 251(6):957–972 (2022). [doi:10.1002/dvdy.373](https://doi.org/10.1002/dvdy.373)
    Evo-devo review, including genome size versus regeneration rate. *(Borderline inclusion.)*
33. **Adamson CJ, Morrison-Welch N, Rogers CD.** The amazing and anomalous axolotls as scientific models. *Dev Dyn* 251(6):922–933 (2022). [doi:10.1002/dvdy.470](https://doi.org/10.1002/dvdy.470) · [PMID 35322911](https://pubmed.ncbi.nlm.nih.gov/35322911/)
    Review including a regeneration-capacity table by tissue.
34. **(Echeverri lab; authors to verify).** The Axolotl's journey to the modern molecular era. *Curr Top Dev Biol* 147:631–658 (2022).
    Review.
    > ⚠️ Authors unconfirmed.
35. **Maden M.** Salamanders as key models for development and regeneration research. *Methods Mol Biol* 2562:1–23 (online October 2022).
    Introductory chapter.
36–45. **Other regeneration-relevant chapters in *Methods Mol Biol* 2562** (*Salamanders: Methods and Protocols*, eds. Seifert AW & Currie JD; Humana; online October 2022; 31 protocols). Cite each individually by its `10.1007/978-1-0716-2659-7_N` DOI. Topics include:
   - COMET assay for DNA damage during axolotl tail regeneration
   - Induction and characterization of cellular senescence in salamanders
   - Methods for appendicular skeletal biology in axolotls (Riquelme-Guzmán & Sandoval-Guzmán)
   - Small molecules to dissect regeneration
   - Bead implantation and growth factor delivery
   - The Accessory Limb Model and its derivatives
   - HCR-FISH in *A. mexicanum*
   - Ethyl cinnamate tissue clearing
   - Colony establishment (Yandulskaya & Monaghan)
   - Health monitoring
   > ⚠️ Entries 35–45: online 2022, labeled 2023 edition.
 
## Species cross-index
 
Numbers refer to entries above.
 
| Species | Entries |
|---|---|
| Axolotl (*Ambystoma mexicanum*) | 1–11, 15, 16, 18–20, 23, 26–28, 31, 33–35, most of 36–45 |
| *Pleurodeles waltl* | 4 (partly), 6 (partly), 12, 17, 21, 22, 29 |
| *Cynops pyrrhogaster* | 13, 14 |
| *Notophthalmus viridescens* | None as primary system in 2022; appears in reviews (25) |
| Newt, species-general or mixed | 24, 25 |
| Pan-salamander / multi-species | 32 |
 
## Notable 2022 preprints
 
> These were not peer-reviewed at posting. Several were later published.
 
| Preprint | Posted | Status |
|---|---|---|
| **Brown T et al.** Sequencing and chromosome-scale assembly of the giant *Pleurodeles waltl* genome. [doi:10.1101/2022.10.19.512763](https://doi.org/10.1101/2022.10.19.512763) | Oct 2022 | TE (especially hAT) expansion; hAT and domesticated hAT/ZBED genes regulated during adult limb regeneration |
| **Yu Q et al.** Cellular senescence modulates progenitor cell expansion during axolotl limb regeneration. [doi:10.1101/2022.09.01.506196](https://doi.org/10.1101/2022.09.01.506196) | Sep 2022 | Later published in *Dev Cell* (2023) |
| **Walters HE et al.** Senescent cells enhance newt limb regeneration by promoting muscle dedifferentiation. [doi:10.1101/2022.09.01.506186](https://doi.org/10.1101/2022.09.01.506186) | Sep 2022 | Later published (2023) |
| **Furukawa S, Yamamoto S, Kashimoto R, Morishita Y, Satoh A.** Variable Shh and Fgf8 positioning in regenerating axolotl limb guarantees consistent limb morphogenesis in different limb sizes. [doi:10.1101/2022.01.04.475010](https://doi.org/10.1101/2022.01.04.475010) | Jan 2022 | — |
| **Riquelme-Guzmán C et al.** Osteoclast preprint, [doi:10.1101/2022.04.27.489662](https://doi.org/10.1101/2022.04.27.489662); Brillouin preprint, [doi:10.1101/2022.03.01.482501](https://doi.org/10.1101/2022.03.01.482501) | Apr / Mar 2022 | Published as entries 1 and 8 |
| **Lust K et al.** Single-cell analyses of axolotl forebrain organization, neurogenesis, and regeneration | Mar 2022 | Published as entry 20 |
| Axolotl retinal regeneration and Notch signaling. [doi:10.1101/2022.04.28.489898](https://doi.org/10.1101/2022.04.28.489898) | Apr 2022 | Authors to verify |

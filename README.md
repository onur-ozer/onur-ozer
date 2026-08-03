## Hi, I'm Onur Özer!

I'm a geneticist with a PhD in computational immunology. My research is centered around a straightforward question: Why do we get sick? More specifically, why are some people more prone to certain diseases, whether it is an infectious disease, an autoimmnue condition or even cancer, while others stay unaffected, and what is the genetic basis of that difference?

I approach this from two angles. One is evolutionary: how and why did these differences arise over time. The other is clinical: how can this information translate into better medical strategies. To answer these questions I've worked with data from both modern humans and ancient humans who died thousands of years ago.

Recently I added machine learning to that foundation through an intensive bootcamp, and I'm now looking to bring that combination into more translational, clinically-oriented work.

**Currently working on:** expanding my machine learning skills (scikit-learn, TensorFlow, Keras) and applying it to immunogenomics and clinical prediction problems.


### Project highlights

- [HLA-scRNA](https://github.com/onur-ozer/HLA-scRNA)

scRNA-seq analysis tutorial in R/Seurat: QC, normalization, PCA/UMAP/t-SNE, Harmony batch correction, label transfer, and MAST differential expression, applied to HLA class I/II expression under interferon stimulation.

- [HLA-PCA](https://github.com/onur-ozer/HLA-PCA)

Interactive R Shiny application for exploring HLA allele and haplotype diversity across populations.

- [HLA Defense](https://onur-ozer.github.io/immune-defence-game/)

Browser-based game simulating the immune system. Aims to make immunology concepts approachable to non-specialist audiences.

- [BRAINNet](https://github.com/simonwilliams32/MRI_project)

Deep learning pipeline classifying MRI brain scans as normal or abnormal, and identifying tumor subtype (meningioma, pituitary adenoma, glioma) when present.



### Tech stack

**Languages & libraries**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-003B57?style=flat&logo=postgresql&logoColor=white)

![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white)
![tidyverse](https://img.shields.io/badge/-tidyverse-1A162D?style=flat&logo=tidyverse&logoColor=white)
![ggplot2](https://img.shields.io/badge/-ggplot2-276DC3?style=flat)

**Pipelines & infrastructure**

![Snakemake](https://img.shields.io/badge/-Snakemake-039475?style=flat)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**Tools**

![RStudio](https://img.shields.io/badge/-RStudio-75AADB?style=flat&logo=rstudio&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Bioconductor](https://img.shields.io/badge/-Bioconductor-172554?style=flat)



### Publication highlights


**[Unique Pathogen Peptidomes Facilitate Pathogen-Specific Selection and Specialization of MHC Alleles](https://doi.org/10.1093/molbev/msab176)**

*Özer O, Lenz TL. Molecular Biology and Evolution, 2021*

![Figure 1](figures/msab176f1.jpeg)

Built a reference peptidome of 51.9 million unique 9-mer peptides from the proteomes of 36 representative human pathogens (viruses, bacteria, eukaryotic parasites) and found that 98.8% of peptides were unique to a single pathogen species.

Used NetMHCpan to characterize the peptide-binding repertoires of 321 common HLA class-I variants, and showed that variants with narrower repertoires ("fastidious" variants) show significantly higher pathogen-specific specialization scores than promiscuous variants. This pattern is confirmed using experimental IEDB binding data. 

Identified locus-level differences in binding promiscuity (HLA-A > HLA-B/C) and a positive correlation between promiscuity and self-peptide binding for HLA-A and HLA-C.

These results provide empirical evidence that antigenic diversity of pathogens shapes the evolution of HLA allelic diversity, and that narrow-repertoire HLA variants persist in populations through specialization against particular pathogens.

---

**[Ancient genomics study reveals low HLA diversity in eastern hunter-gatherers](https://doi.org/10.1186/s13059-026-04214-8)**

*Özer O, da Silva NA, Haller-Caskie M, Myburgh DA, Piezonka H, et al. Genome Biology, 2026*

![Figure 3](figures/fig3_aDNA.webp)

Analyzed genome-wide and HLA data from individuals buried at Sakhtysh. Genome-wide analysis places all Sakhtysh individuals within the Eastern Hunter-Gatherer (EHG) cluster, showing genetic continuity across the Lyalovo and Volosovo cultural traditions, alongside a sizable WHG-related component likely reflecting shared Paleolithic ancestry rather than later gene flow. 

Developed a pipeline for HLA genotyping, combining multiple tools and automating the error-prone manual process. Using this pipeline together with targeted enrichment, genotyped 27 individuals at classical HLA loci, providing the first look at HLA diversity in ancient hunter-gatherers. The populations showed strikingly low diversity. B\*27:05 reached close to 50% frequency, with a trend in the Ewens-Watterson test hinting at selection. The DRB1\*08:01~DQB1\*04:02 haplotype, which in European farmers only appears after admixture with WHG, was also common in Sakhtysh, pointing to the deep shared ancestry between WHG and EHG.

These results provide the first direct evidence that ancient hunter-gatherer populations carried unexpectedly low HLA diversity alongside high-frequency alleles that may reflect specific selective pressures rather than population history alone.

---

**[Ancient DNA study provides clues to leprosy susceptibility in medieval Europe](https://doi.org/10.1186/s13059-025-03925-8)**

*Romeyer-Dherbey JH, Caliebe A, Özer O, da Silva NA, Mendoza Mejía N, et al. Genome Biology, 2026*

![Figure 4](figures/fig4_leprosy.webp)

A case-control HLA association study on 302 medieval individuals (93 leprosy cases, 209 controls) from 18 archaeological sites in Denmark and Germany. HLA-B\*38 was confirmed as a leprosy risk allele, with three additional variants, HLA-A\*23, DRB1\*04, and DRB1\*13, identified as novel candidates for risk or protection.

Contributed the population genetic and statistical framework of the study: calculated pairwise F<sub>ST</sub> between medieval cases, controls, and modern European populations to rule out stratification as a confounder, compared heterozygosity and allelic richness between groups, and ran computational binding prediction of *M. leprae* peptides across the associated HLA alleles to test whether risk alleles differed in their peptide-binding repertoires. Also built a multivariate logistic regression model incorporating ancient DNA damage metrics (λ parameter, terminal deamination rate, endogenous DNA content) to confirm that the observed HLA associations were not artifacts of DNA preservation differences between cases and controls.

These analyses show that the HLA associations detected in this medieval cohort reflect genuine disease susceptibility signals rather than population structure or DNA damage artifacts, extending leprosy genetic association studies to a European population for the first time.

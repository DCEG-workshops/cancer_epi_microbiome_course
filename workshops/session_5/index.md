---
layout: page
permalink: workshops/session_5
---

### Topics Covered
- Statistical methods for microbiome data
- Compositional data analysis
- Differential abundance testing
- Alpha Diversity
- Beta Diversity
- Measurement error & reproducibility
- Network Analysis
- Data Integration – Multi-omics


### Session Overview

This session covers statistical analysis methods specifically designed for microbiome data, addressing the unique challenges of compositional, high-dimensional, and sparse data.

# Recommended Readings

---

## 0. General Data Exploration & Pre-processing

- Zuur, A. F., Ieno, E. N., and Elphick, C. S. (2010). A protocol for data exploration to avoid common statistical problems. *Methods in Ecology and Evolution*, 1(1), 3–14.

- Zhou, R., Ng, S. K., Sung, J. J. Y., Goh, W. W. B., and Wong, S. H. (2023). Data pre-processing for analyzing microbiome data – a mini review. *Computational and Structural Biotechnology Journal*, 21, 4804–4815.

- Davis, N. M., Proctor, D. M., Holmes, S. P., Relman, D. A., and Callahan, B. J. (2018). Simple statistical identification and removal of contaminant sequences in marker-gene and metagenomics data. *Microbiome*, 6(1), 226. *(introduces `decontam`)*

---

## 1. Compositional Data & Transformations

### Foundational Theory

- Aitchison, J. (1986). *The Statistical Analysis of Compositional Data*. Chapman & Hall, London.

- Gloor, G. B., Macklaim, J. M., Pawlowsky-Glahn, V., and Egozcue, J. J. (2017). Microbiome datasets are compositional: and this is not optional. *Frontiers in Microbiology*, 8, 2224.

### Transformations for Ecological / Microbiome Data

- Legendre, P., and Gallagher, E. D. (2001). Ecologically meaningful transformations for ordination of species data. *Oecologia*, 129(2), 271–280. *(covers Hellinger and related transformations)*

- Greenacre, M., Martínez-Álvaro, M., and Blasco, A. (2021). Compositional data analysis of microbiome and any-omics datasets: a validation of the additive logratio transformation. *Frontiers in Microbiology*, 12, 727398.

---

## 2. Diversity Analysis

### Alpha Diversity

- Chao, A. (1984). Nonparametric estimation of the number of classes in a population. *Scandinavian Journal of Statistics*, 11(4), 265–270. *(Chao1 estimator)*

- Faith, D. P. (1992). Conservation evaluation and phylogenetic diversity. *Biological Conservation*, 61(1), 1–10. *(Faith's phylogenetic diversity)*

- Willis, A. D. (2019). Rarefaction, alpha diversity, and statistics. *Frontiers in Microbiology*, 10, 2407. *(critical discussion of rarefaction for diversity estimation)*

### Beta Diversity & Ordination

- Lozupone, C., and Knight, R. (2005). UniFrac: a new phylogenetic method for comparing microbial communities. *Applied and Environmental Microbiology*, 71(12), 8228–8235.

- Anderson, M. J., Ellingsen, K. E., and McArdle, B. H. (2006). Multivariate dispersion as a measure of beta diversity. *Ecology Letters*, 9(6), 683–693. *(PERMDISP)*

- McArdle, B. H., and Anderson, M. J. (2001). Fitting multivariate models to community data: a comment on distance-based redundancy analysis. *Ecology*, 82(1), 290–297. *(PERMANOVA)*

---

## 3. Differential Abundance Analysis

### Methods

- Weiss, S., Xu, Z. Z., Peddada, S., Amir, A., Bittinger, K., Gonzalez, A., … Knight, R. (2017). Normalization and microbial differential abundance strategies depend upon data characteristics. *Microbiome*, 5(1), 27.

- Lin, H., and Peddada, S. D. (2020). Analysis of compositions of microbiomes with bias correction. *Nature Communications*, 11(1), 3514. *(ANCOM-BC)*

- Mandal, S., Van Treuren, W., White, R. A., Eggesbø, M., Knight, R., and Peddada, S. D. (2015). Analysis of composition of microbiomes: a novel method for studying microbial composition. *Microbial Ecology in Health and Disease*, 26(1), 27663. *(original ANCOM)*

- Zhou, H., He, K., Chen, J., and Zhang, X. (2022). LinDA: linear models for differential abundance analysis of microbiome compositional data. *Genome Biology*, 23(1), 95.

- Love, M. I., Huber, W., and Anders, S. (2014). Moderated estimation of fold change and dispersion for RNA-seq data with DESeq2. *Genome Biology*, 15(12), 550.

### Benchmarking

- Nearing, J. T., Douglas, G. M., Hayes, M. G., MacDonald, J., Desai, D. T., Allward, N., … Langille, M. G. I. (2022). Microbiome differential abundance methods produce different results across 38 datasets. *Nature Communications*, 13(1), 342.

- Calgaro, M., Romualdi, C., Waldron, L., Risso, D., and Vitulo, N. (2022). Assessment of statistical methods from single cell, bulk RNA-seq, and metagenomics applied to microbiome data. *Genome Biology*, 21(1), 191. *(introduces `benchdamic`)*

---

## 4. Correlation & Network Analysis

- Friedman, J., and Alm, E. J. (2012). Inferring correlation networks from genomic survey data. *PLOS Computational Biology*, 8(9), e1002687. *(SparCC)*

- Kurtz, Z. D., Müller, C. L., Miraldi, E. R., Littman, D. R., Blaser, M. J., and Bonneau, R. A. (2015). Sparse and compositionally robust inference of microbial ecological networks. *PLOS Computational Biology*, 11(5), e1004226. *(SPIEC-EASI)*

---

## 5. Measurement Error & Technical Variability

- Kaul, A., Mandal, S., Davidov, O., and Peddada, S. D. (2017). Analysis of microbiome data in the presence of excess zeros. *Frontiers in Microbiology*, 8, 2114. *(zero-inflation and its consequences for inference)*

- Reproducibility and sources of technical variation:
  - Sinha, R., Abu-Ali, G., Vogtmann, E., Fodor, A. A., Ahn, J., Amir, A., … Human Microbiome Project Consortium. (2017). Assessment of variation in microbial community amplicon sequencing by the Microbiome Quality Control (MBQC) project consortium. *Nature Biotechnology*, 35(11), 1077–1086.

- Carroll, R. J., Ruppert, D., Stefanski, L. A., and Crainiceanu, C. M. (2006). *Measurement Error in Nonlinear Models: A Modern Perspective* (2nd ed.). Chapman & Hall/CRC. *(general reference on measurement error in statistical models)*

---

## 6. General Microbiome Statistics — Reviews & Textbooks

- Gloor, G. B., Wu, J. R., Pawlowsky-Glahn, V., and Egozcue, J. J. (2016). It's all relative: analyzing microbiome data as compositions. *Annals of Epidemiology*, 26(5), 322–329.

- Mallick, H., Rahnavard, A., McIver, L. J., Ma, S., Zhang, Y., Nguyen, L. H., … Huttenhower, C. (2021). Multivariable association discovery in population-scale meta-omics studies. *PLOS Computational Biology*, 17(11), e1009442. *(MaAsLin2)*

- Holmes, S., and Huber, W. (2019). *Modern Statistics for Modern Biology*. Cambridge University Press.


<br><br>
*Instructors: Shi & Anyaso Samuel (BB)*

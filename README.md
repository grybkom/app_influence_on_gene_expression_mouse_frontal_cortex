# APPs Influence on Gene Expression in the Mouse Frontal Cortex
Analysis of DNA microarray gene expression data from mouse frontal cortex to examine transcriptional changes associated with genetic manipulation of APP and related family members.

## Background

Amyloid precursor protein (APP) and its proteolytic processing products, particularly amyloid-β (Aβ), have long been implicated in the pathogenesis of Alzheimer’s disease (AD) (Aydin et al., 2011 and Cha et al., 2022). While APP accumulation and altered processing are central to AD pathology, the broader transcriptional consequences of APP loss or modification in the adult brain remain incompletely understood.

In this study, DNA microarray transcriptomic profiling of mouse frontal cortical tissue is used to examine how genetic manipulation of APP and related family members influences gene expression (Aydin et al., 2011). Five experimental conditions are analyzed: control wildtype mice (WT_R6), APP homozygous knockout mice (APP_R6), APPsa knock-in mice (APPsa_R6) that expresses only a soluble fragment released from the amyloid precursor protein and is considered neuroprotective (Tackenberg & Nitsch, 2019), and two homozygous APLP2 knockout mouse lines, APLP2_R6 (backcrossed six generations to C57BL/6) and APLP2_R1(backcrossed for one generation). APLP2 is a homolog of APP (Cha et al., 2022). 

DNA microarray technology is a hybridization-based approach used to measure expression levels of predefined genes. Gene-specific probe sequences are immobilized on a chip and hybridized with labeled complementary DNA (cDNA) derived from tissue RNA. Gene expression levels are inferred from fluorescence intensity, enabling genome-wide comparison of transcriptional changes across experimental conditions.

**References:**

Aydin, D., Filippov, M. A., Tschäpe, J., Gretz, N., Prinz, M., Eils, R., Brors, B., & Müller, U. C. (2011). Comparative transcriptome profiling of amyloid precursor protein family members in the adult cortex. BMC Genomics, 12(1), 160. https://doi.org/10.1186/1471-2164-12-160

Cha, H. J., Shen, J., & Kang, J. (2022). Regulation of gene expression by the APP family in the adult cerebral cortex. Scientific Reports, 12(1), 66. https://doi.org/10.1038/s41598-021-04027-8

Tackenberg, C., & Nitsch, R. M. (2019). The secreted APP ectodomain sAPPα, but not sAPPβ, protects neurons against Aβ oligomer-induced dendritic spine loss and increased tau phosphorylation. Molecular Brain, 12(1), 27. https://doi.org/10.1186/s13041-019-0447-2

## Data Cleaning and Processing

The data used in this study can be accesses through the Gene Expression Omnibus (GEO) hosted by the National Center for Biotechnology Information (NCBI). The data accession viewer for this project: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE25926

The microarray expression values are fluorescence intensities they have already been log-transformed. 

Genotype information was not included in the full dataset, therefore a genotype table was manually created and merged with the expression data. 

The data consists of 15 samples and 

**Mouse IDs and Their Associated Genotypes:**

- GSM636860:    WT_R6_rep1
- GSM636861:	WT_R6_rep2
- GSM636862:	WT_R6_rep3
- GSM636863:	APP_R6_rep1
- GSM636864:    APP_R6_rep2
- GSM636865:	APP_R6_rep3
- GSM636866:	APPsa_R6_rep1
- GSM636867:	APPsa_R6_rep2
- GSM636868:	APPsa_R6_rep3
- GSM636869:	APLP2_R6_rep1
- GSM636870:	APLP2_R6_rep2
- GSM636871:	APLP2_R6_rep3
- GSM636872:	APLP2_R1_rep1
- GSM636873:	APLP2_R1_rep2
- GSM636874:	APLP2_R1_rep3

# EDA

![app_sample_expression_distributions](https://github.com/user-attachments/assets/2a54dfc6-5289-4839-8e0a-a320e478da51)

![app_cluster_map](https://github.com/user-attachments/assets/c16927c0-a497-4315-9672-57788f5eefe7)

![app_cluster_map_by_genotype](https://github.com/user-attachments/assets/26e422f3-341e-4570-99fc-0db6aba0c3ea)

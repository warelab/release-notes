# Technical Reference Manual: Interpreting Genome-by-Environment Associations in the 19K Rice Genome Project

## 1. Overview
This manual provides a comprehensive framework for utilizing genome-by-environment association (GEA) data from the 19K Rice Genome Project (19K-RGP). By integrating genome-wide variation with environmental variables, this resource identifies genetic loci underlying local adaptation and climate-driven selection in rice, facilitating the development of climate-smart, resilient crop varieties.

## 2. Landrace Dataset and Climate Variables
The 19K-RGP dataset includes over 4,500 geo-referenced rice landraces, providing an unprecedented opportunity to dissect genotype-by-environment (G × E) interactions. These landraces are categorized into four major varietal groups:
*   **Xian-Indica (XI):** 2,379 accessions.
*   **Geng-Japonica (GJ):** 1,349 accessions.
*   **circum-Aus (cA):** 525 accessions.
*   **circum-Basmati (cB):** 300 accessions.

For each landrace, a robust set of 431 geo-environmental variables was curated to describe local environmental conditions, revealing strong blocks of correlated climate parameters specific to each varietal group.

## 3. Genome-Wide Environmental Associations (G × E)
Genome-wide association studies (GWAS) were conducted utilizing standalone genetic variation (minor allele frequency ≥ 0.05) within each group to identify climate-associated variants (Bonferroni < 0.01). The number of significant variants discovered are:
*   **GJ:** 206,072 variants.
*   **XI:** 633,438 variants.
*   **cA:** 117,748 variants.
*   **cB:** 111,316 variants.

Analyses show that single-nucleotide polymorphisms (SNPs) are more frequently associated with climate variables than InDels. Additionally, approximately 28% of these climate-associated SNPs are classified as riboSNitches, meaning they are predicted to alter mRNA structures. While most climate-associated variants are specific to their respective varietal groups, suggesting distinct evolutionary adaptations, convergence was observed at the gene loci level, where multiple groups shared common genes facilitating climate adaptation. 

## 4. Oryza CLIMtools 19K-RGP Platform
To streamline phenotype-by-genotype-by-environment (P × G × E) analyses, researchers are encouraged to utilize the open-source **Oryza CLIMtools 19K-RGP** platform. This platform expands upon earlier resources to include the newly sequenced cA and cB groups, along with thousands of new climates and genotypes. It features three core interactive modules:
*   **OryzaCLIM 19K-RGP:** Enables the exploration of local climate variation among landraces across different varietal groups and subpopulations.
*   **Oryza GenoCLIM 19K-RGP:** Allows users to interrogate specific genes of interest to identify associated climate variants.
*   **Oryza CLIMGeno 19K-RGP:** Provides a genome-wide examination of variants correlated with user-specified climate variables.

## 5. Phenotype-by-Environment (P × E) Interactions: Heading Date
Environmental variables significantly shape phenotypic traits such as grain weight, shape, length, width, and heading date. Heading date exhibits the strongest associations with the local environment, particularly with temperature-related climate variables, with over 50% of these associations overlapping between the GJ and XI groups. 

### Case Study: *MADS14* in Xian-Indica (XI)
The flowering time transcription factor *MADS14*/*APETALA1* (Os03g0752800) in XI landraces serves as an exemplar for interpreting these associations:
*   **Climate Association:** The *MADS14* locus features a significant GWAS peak for the minimum temperature of the coldest month (BIO6), which is the climate factor most strongly correlated with heading date in XI rice.
*   **Haplotype Structure:** Based on 33 variants, the gene is composed of four main haplotypes (H1 to H4).
*   **Haplotype H1:** Primarily distributed in warm, low-latitude environments across Southeast Asia and correlates with a later heading date.
*   **Haplotype H2:** Distributed across cooler East Asian regions and correlates with an earlier heading date, reflecting an adaptation to a shorter growing season.
*   **Haplotypes H3 and H4:** Exhibit patchier distributions and associations that may be interpreted as maladaptive (e.g., early-heading varieties growing in high temperatures), which may point to specific multi-cropping agricultural practices.

This analytical framework demonstrates how coupling population-scale genetic diversity with environmental data can uncover the mechanistic basis of local adaptation, ultimately informing modern, climate-resilient breeding strategies.

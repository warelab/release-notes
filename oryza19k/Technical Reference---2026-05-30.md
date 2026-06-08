Technical Reference Manual: Interpreting Genome-by-Environment Associations in the 19K Rice Genome Project

1. Foundations of the 19K Rice Genome Framework

The 19K Rice Genome Project (19K-RGP) marks a strategic evolution from the static cataloging of genetic diversity to the operationalization of a "Digital Genebank." While the preceding 3K-RGP established an essential genomic baseline, we have expanded this framework to include 19,035 accessions, moving the field into a transdisciplinary era where functional genomics and environmental integration are paramount. This project identifies approximately 57 million natural variants, providing a high-resolution map of the Oryza sativa pangenome. Critically, ~28% of these variants are novel relative to the European Variation Archive (EVA), representing a vast, previously uncharacterized reservoir of alleles that are essential for discovering the genetic basis of local adaptation.

Core Dataset Composition

The 19K-RGP architecture provides the most comprehensive genomic resolution for any crop species to date:

Feature	Specification
Total Accessions	19,035
Geo-referenced Landrace Subset	4,500+
Total Natural Variants	~57 million
Novel Variants vs. EVA	~28%
Platinum Reference Genomes	Os-Nipponbare (GJ), IR64RS2 (XI), MH63RS3 (XI), ARC 104978 (cB), N22 (cA)

The Strategic Value of Geo-referenced Landraces

Our inclusion of over 4,500 geo-referenced landrace accessions transforms genomic data into a precision tool for studying evolutionary trajectories. Unlike modern cultivars, landraces carry the signatures of centuries of selection across diverse ecological gradients. By coupling these genotypes with local climate data, we can identify the specific loci underlying local adaptation—moving beyond theoretical diversity to practical breeding targets. This scale allows us to organize global diversity through a rigorous understanding of population architecture.


--------------------------------------------------------------------------------


2. Population Architecture and Ancestral Recombination Graphs (ARGs)

Accurate Genome-by-Environment (GxE) association mapping requires a precise baseline of population structure to distinguish adaptive signals from demographic noise. We utilized a hierarchy of analysis from K=4 to K=15 subpopulations, ensuring that association signals are corrected for historical relatedness.

Evolutionary Histories via ARGs and TMRCA

Through Ancestral Recombination Graphs (ARGs) and Time to Most Recent Common Ancestor (TMRCA) analysis, we have reconstructed the dispersal patterns and ancestral origins of the four major variety groups:

* Geng-Japonica (GJ): ARGs reveal distinct regional dispersal signatures. Landraces from Island Southeast Asia and Mainland Southeast Asia form separate clusters with recent internal TMRCAs, confirming structured, regional expansion.
* Xian-Indica (XI): This group exhibits the youngest and most uniform TMRCAs. This suggests a recent and rapid dispersal across geography, leading to a more homogenous population structure compared to other groups.
* circum-Aus (cA) and circum-Basmati (cB): Our analysis identifies Bangladesh as the critical reservoir of diversity for these groups, harboring the deepest divergence and the oldest surviving lineages.

Genetic Diversity and Fine-Mapping Resolution

Our evaluation of genetic diversity (\pi) and Linkage Disequilibrium (LD) decay provides critical insights for association mapping. GJ-temperate populations exhibit low diversity and slow LD decay, which inherently limits mapping resolution. In contrast, the XI and cA groups possess high diversity and rapid LD decay. Synthesis: This rapid decay makes XI and cA the superior populations for fine-mapping; trait-associated variants in these groups can be pinpointed with far greater genomic precision than in GJ-temperate lineages.


--------------------------------------------------------------------------------


3. High-Resolution Functional Variant Mapping: Rare and Regulatory Variants

The "missing" components of climate adaptation frequently reside in the under-sampled genomic landscape of rare and regulatory variants. In the 19K-RGP, 81.3% of identified SNPs are categorized as rare or ultra-rare, providing a high-impact resource for crop improvement.

Categories of Standing Variation

* Common: Minor Allele Frequency (MAF) > 0.05
* Low-frequency: 0.01 < MAF ≤ 0.05
* Rare: Allele Count (AC) > 10, MAF ≤ 0.01
* Ultra-rare: AC ≤ 10

Deep Learning for Regulatory Mapping (Basenji)

To bridge the gap between non-coding sequence and function, we employed the Basenji deep-learning framework across Open Chromatin Regions (OCRs). This identified 2.44 million high-effect regulatory variants (HEVs).

* The "So What?" Layer: Traditional GWAS often ignores the non-coding landscape due to a lack of functional context. The Basenji framework provides this context, identifying variants that govern gene expression dynamics rather than protein sequence. Furthermore, Derived Allele Frequency (DAF) analysis shows HEVs are enriched at intermediate-to-high frequencies, suggesting these regulatory elements are targets of positive selection for adaptive traits.

Case Study: The TB1/FC1 Promoter Variant

A primary example of this regulatory control is the promoter variant vg0328428354 in the TB1/FC1 gene. Our model identifies an A-to-G substitution at this locus. The 'G' allele creates a significantly stronger binding site for the transcription factor OsBZR1. This increased binding suppresses TB1 expression, leading to higher tiller numbers—a rare but potent allele for optimizing plant architecture.


--------------------------------------------------------------------------------


4. The Genome-by-Environment (GxE) Association Framework

We established a methodology for coupling genomic variation with 431 geo-environmental variables to pinpoint loci under local selection. For high-confidence associations, we utilized a stringent Bonferroni P < 0.01 threshold.

Core Environment-Genotype Modules

* G x E Identification: We identified 206,072 climate-associated variants in GJ and 633,438 in XI.
* Convergence vs. Specificity: While most variants are specific to a single group, the gene loci often overlap. This demonstrates convergent functional adaptation: different mutations in the same genes are independently selected across different groups to achieve similar environmental fitness.
* RiboSNitches: Approximately 28% of climate-associated SNPs are riboSNitches—variants that alter mRNA secondary structure, adding a post-transcriptional layer to environmental adaptation.

Trait Correlation and Reliability

Climate variables correlate most significantly with phenological traits, particularly Heading Date. This remains the most reliable trait for GxE studies as it represents the plant’s primary mechanism for aligning its reproductive cycle with local growing seasons.


--------------------------------------------------------------------------------


5. Technical Guide to Oryza CLIMtools 19K-RGP

Oryza CLIMtools is our open-access, interactive platform designed to democratize GxE analysis. It allows researchers to visualize environmental selection pressures without intensive bioinformatic overhead.

Core Modules

1. OryzaCLIM: Explores local climate variation across the 4,500 landraces.
2. Oryza GenoCLIM: Interrogates climate-associated variants within specific candidate genes.
3. Oryza CLIMGeno: Examines genome-wide variants associated with specific environmental variables.

Conceptual Workflow: Validating MADS14/MADS50

A researcher can validate a candidate gene using this three-step protocol:

1. Select a target climate variable (e.g., minimum temperature).
2. Use Oryza GenoCLIM to identify significant climate-associated variants within genes like MADS14.
3. Map the geographic distribution of these variants to correlate allele frequency with regional environmental gradients.


--------------------------------------------------------------------------------


6. Case Study: Climate Adaptation in the MADS14 Locus

The MADS14 transcription factor serves as a model for Phenotype-by-Genotype-by-Environment (P x G x E) interactions, particularly regarding its response to the BIO6 climate variable (Minimum Temperature of the Coldest Month).

Haplotype Analysis in XI Rice

* H1 Haplotype: Associated with low-latitude, warm environments and late heading dates, maximizing vegetative growth in long growing seasons.
* H2 Haplotype: Found in cooler East Asian regions, favoring early heading dates as an adaptation to shorter seasonal windows.
* H3 & H4 Haplotypes: These illustrate specific adaptive mismatches or niche specializations. H3 is found in high-temperature regions but exhibits early heading, likely an adaptation for specialized multi-cropping. H4 is found in cold temperatures but exhibits late heading, potentially representing a maladaptive or highly niche-specific phenotype.

Synthesis: This mapping allows breeders to match specific MADS14 haplotypes to precise geographic regions, ensuring optimal flowering time and yield.


--------------------------------------------------------------------------------


7. Advanced Adaptive Mechanisms: Small RNAs and Protein Stability

Adaptation is multi-dimensional, extending from sequence variation to small RNA pathways and protein stability.

Small RNA Pathways

We investigated the miR2118-triggered 21-nt phasiRNA pathway, which regulates male fertility. Variants in miR2118l and miR2118o are strongly associated with evapotranspiration and temperature in XI rice. These represent standing variations present in wild ancestors, selected to fine-tune reproductive success under specific environmental stresses.

Protein Structural Modeling

Using AlphaFold3 and the Evo2 foundational model for sequence-level scoring, we modeled the OsCBL8-OsCIPK17 module.

* Methodology: Before structural modeling, we used Evo2 to score the functional impact of haplotypes independent of SNP count.
* Simulation Findings: The combination of CIPK17 HAP54 and CBL8 HAP6/7 was identified as the most energetically favorable (stable) under thermal stress. This provides a blueprint for selecting "climate-resilient" protein interactions that maintain signaling integrity in harsh environments.


--------------------------------------------------------------------------------


8. AI-Driven Phenotypic Prediction and the "Digital Twin" Concept

The 19K-RGP facilitates a transition from reactive breeding to proactive design through AI-driven models.

AI Prediction Benchmarks

We utilized XGBoost and LightGBM models to achieve high-accuracy phenotypic predictions:

Trait	Accuracy (Spearman r)
Heading Date	> 0.80
Grain Width	> 0.80
Grain Length	0.77 – 0.85
Grain Weight	0.77 – 0.85
Grain Shape	> 0.80

The Rice Digital Twin

Our framework introduces the Rice Digital Twin, a virtual simulation environment. This concept applies Fisher’s theorem of a multidimensional fitness space, allowing us to forecast allele frequency trajectories across dynamic landscapes. By simulating how populations will respond to future climate scenarios, we move from observing past adaptation to actively designing the future of global food security. The 19K-RGP thus provides the essential roadmap for integrative genomics and precision agriculture.

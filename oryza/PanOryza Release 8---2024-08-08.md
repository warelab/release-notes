### Oryza PanGenome Release 8.0
### Released: August 2024

GrameneOryza (https://oryza.gramene.org), funded by the USDA-ARS, is an open resource released to the public in 2015. The GrameneOryza team works closely with the community to support stewardship of rice genomics data, establish best-practices on managing the data, and provide opportunities for networking and capacity building within the community. We maintain a database of genome sequences, gene structure annotations, and comparative genomic analyses integrated with curated data from [EBI's Gene Expression Atlas](https://www.ebi.ac.uk/gxa/plant/experiments), [Gramene's Plant Reactome](https://plantreactome.gramene.org), and [Oryza CLIMtools](https://www.gramene.org/CLIMtools/oryza_v1.0/).


## What's New in release 8?

### New & Updated Data
  
***Genes***

- New pan-gene set identifiers provided as gene synonyms for _O. sativa_ Japonica Nipponbare. Example: [Os4530.POR.1.pan0017141 for Os07g0129700](/?fq_field=PanOryza__xrefs&fq_value=Os4530.POR.1.pan0017141&category=PanOryza%20pan%20gene&name=Os4530.POR.1.pan0017141).

***Genetic Variation***

- _O. sativa_ Japonica Nipponbare (IRGSP1): 27 million SNPs were assigned standard rsIDs provided by the [European Variation Archive](https://www.ebi.ac.uk/eva/).

- New variation data sets mapped to _O. sativa_ Japonica Nipponbare (IRGSP1):

  1) **Rice Mini-Core Collection (USDA URMC)**: 6.5 million SNPs determined in the URMC diversity panel (190 rice accessions) of the United States Department of Agriculture (USDA) by Kumar et al (2021) and kindly provided by Julie Thomas and Andy Pereira from the University of Arkansas.
     
  2) **World Rice Core Collection (NARO WRC)** & **Rice Core Collection of Japanese Landraces (NARO JRC)**: 12 million SNPs determined in 68 accessions of the WRC (Tanaka et al, 2020a) and 50 accessions of the JRC (Tanaka et al, 2020b) collections of the National Agriculture and Food Research Organization (NARO) Genebank. This data was kindly provided by the team led by Dr. Takeshi Itoh of the RAP-DB resource.

***Regulation***

_O. sativa_ Japonica Nipponbare (IRGSP1): ATAC-seq and Chip-seq data for rice from Lou _et al_ (2019). 


### New Functionality & Features

- Gramene Oryza's Search Results enhancements:

  1) The Papers tab listing publications describing a gene's function has now a user entry form (for example, this is a direct link to the [_Add Papers_ or "Submit a gene function" form](https://docs.google.com/forms/d/e/1FAIpQLSey-xPyTysdd9c2phXT6kcbjEDeCppG4dLG7LjZCeLpx_KGog/viewform) to suggest a gene's function given experimental evidence. Currently, there are 5707 functionally curated Nipponbare genes. We invite you to check out your favorite gene and contribute your expertise!

  2) The new Sequences tab provides quick access to gene, transcript and protein sequences for gene models.
     
  3) The new Germplasm tab lists germplasm bearing a protein-truncating variant (PTVs are putative loss-of-function SNPs) within the canonical transcript of a gene model. The table includes links to IRRI and/or GRIN, as well as a way to search for other genes with a PTV in a given germplasm accession. The indexed PTVs include the following predicted functional effects: start lost, stop gained, stop lost, splice site acceptor, and splice site donor.
  

## Summary

Gramene's Oryza Pan-Genome (https://oryza.gramene.org) is a web portal for comparative plant genomics focused on rice varieties. 

In its eighth release, we have assigned standard rsIDs provided by the [European Variation Archive](https://www.ebi.ac.uk/eva/) to a total of 27 million SNPs. In addition, we are featuring SNP data for three new data sets: 

  1) **Rice Mini-Core Collection (USDA URMC)**: 6.5 million SNPs determined in the URMC diversity panel (190 rice accessions) of the USDA by Kumar et al (2021).
     
  2) **World Rice Core Collection (NARO WRC)** and **Rice Core Collection of Japanese Landraces (NARO JRC)**: 12 million SNPs determined in 68 accessions of the WRC (Tanaka et al, 2020a) and 50 accessions of the JRC (Tanaka et al, 2020b) collections of the Japanese NARO Genebank kindly provided by the RAP-DB resource.

We are also providing updated functional gene associations from RAP-DB and GeneRIF from curated scientific literature.  New features within the results of a database query include: 1) a new Sequences tab providing quick access to gene, transcript and protein sequences for gene models, 2) a new Germplasm tab listing accessions bearing protein-truncating variants or PTVs (putative loss-of-function SNPs such as start lost, stop gained, stop lost, splice site acceptor, and splice site donor) and which includes links to IRRI and/or GRIN, and 3) a user entry form to suggest gene function given experimental evidence in the Papers tab.

Since the last release, members of the Gramene Oryza Team contributed to two publications (Harrison et al, 2024; Zhou et al, 2024). In addition to genomic resources, GrameneOryza provides updates of news items, conferences, and community events. Feedback may be provided via a [contact form](https://oryza.gramene.org/feedback). 


## Release Contents -- Databases

### Genomes & Gene Annotations

There are a total of **35 genomes** in GrameneOryza: 28 rice genomes and 7 plant outgroups (_Leersia perrieri_ - the nearest outgroup of the genus Oryza in the Oryzeae tribe, B73 maize V4 and V5, _Sorghum bicolor_, _Arabidopsis thaliana_, grapevine, Selaginella, and Chlamydomonas - a single-celled green algae) and fruit fly Drosophila, in order to allow comparisons between higher eukaryotes, lower plants, and the model Arabidopsis.

The site now includes 13574 [functionally curated gene annotations from GeneRIF and RAP-DB](https://oryza.gramene.org/?filters={%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:3,%22children%22:[{%22fq_field%22:%22capabilities%22,%22fq_value%22:%22pubs%22,%22name%22:%22publication%22,%22category%22:%22Curated%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:true}],%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20}&genomes=) in 6 species (7258 Arabidopsis, 5707 rice, 357 maize, 135 Chlamydomonas, 114 sorghum, 3 Selaginella). For each of the genes, GrameneOryza's search results include a Papers tab listing directly relevant PubMed articles. Moreover, the associated Plant Ontology (PO) and Trait Ontology (TO) terms are searchable, for example: [PO: Anatomy: root](https://oryza.gramene.org/?filters={%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:3,%22children%22:[{%22fq_field%22:%22PO__ancestors%22,%22fq_value%22:%229005%22,%22name%22:%22root%22,%22category%22:%22Plant%20Ontology:%20anatomy%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:true}],%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20}&genomes=) or [TO: drought tolerance](https://oryza.gramene.org/?filters={%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:3,%22children%22:[{%22fq_field%22:%22TO__ancestors%22,%22fq_value%22:%22276%22,%22name%22:%22drought%20tolerance%22,%22category%22:%22Trait%20ontology%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:true}],%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20}&genomes=). 


### Variation

#### Genetic variation: SNPs, InDels, RFLPs and SSRs

Gramene Oryza release 8 features genetic variation data mapped to the following reference assemblies:

===> **_O. sativa_ Japonica Nipponbare (IRGSP1)**:

  - 27 million SNPs determined in _O. sativa_ Japonica Nipponbare IRGSP1 with corresponding standard identifiers or rsIDs imported from the European Variation Archive (EVA). A complete list of the data sets that were assigned rsIDs is provided below and also in [GrameneOryza release notes for version 7.0](https://oryza.gramene.org/News?section=PanOryza%20Release%207). Corresponding genotypes and allele/genotype frequencies by study population are also available in the [Gramene database](https://ensembl.gramene.org/Oryza_sativa/).

  - 6.5 million SNPs determined in the USDA Rice Mini-Core Collection (URMC) of 190 rice accessions in Kumar et al (2021).
     
  - 12 million SNPs determined in two collections at the Japanese NARO Genebank: 68 accessions of the World Rice Core Collection (NARO WRC) (Tanaka et al, 2020a) and 50 accessions of the Rice Core Collection of Japanese Landraces (JRC) (Tanaka et al, 2020b), data kindly provided by the RAP-DB resource.
 
  - 990 RFLPs and 288 SSRs from [Gramene’s legacy markers database](http://archive.gramene.org/markers) associated with traits/phenotypes. Example: [R2382](https://oryza-ensembl.gramene.org/Oryza_sativa/StructuralVariation/Explore?db=core;r=8:23502736-23503637;sv=R2382;svf=1;vdb=variation).

Large-scale rice studies with rsIDs assigned by the EVA:

   1) [Duitama _et al_ (2015)](https://doi.org/10.1371/journal.pone.0124617): 25.8 million SNPs in 104 elite rice cultivars by whole-genome sequencing for marker-assisted selection.
   2) [BGI (2004)](https://doi.org/10.1371/journal.pbio.0030038 ): 3 million SNPs to compare the Indica (93-11) and Japonica (Nipponbare) genomes for adaptive loss-of-function in domesticated rice.
   3) [OMAP (2007)](https://doi.org/10.1093/jxb/erac490): 1.6 million SNPs in 4 rice varieties determined by comparing BAC End Sequences.
   4) [McNally _et al_ (2009](https://doi.org/10.1073/pnas.0900992106): 157K SNPs across 20 diversity rice accessions (OryzaSNP) determined by chip-based analysis to  reveal relationships among landraces and modern varieties.
   5) [Zhao _et al_ (2010)](https://doi.org/10.1371/journal.pone.0010780 ): 1.3K SNPs in 395 samples determined by chip-based analysis for domestication and breeding.

_Note_: The [3000 Rice Genome Project (2014)](https://doi.org/10.1186/2047-217x-3-7), an international effort to sequence the genomes of 3,024 rice varieties from 89 countries, originally identified 365,710 variant loci including SNPs and InDels. This set was also submitted to the EVA and assigned rsIDs. However, more recently, [Zhou _et al_ (2024)](https://doi.org/10.1186/s12915-024-01820-5) used GATK4 software to call about 19 million SNPs using the 3K resequenced accessions on eight of the [MAGIC16 genomes](https://doi.org/10.1038/s41597-020-0438-2) genomes, including Nipponbare. Therefore, we are providing the 19 million SNPs from the 3K rice project as part of the MAGIC16 data set (see below), which supercedes the original 366K SNP set from the 2014 publication.


===> **[MAGIC16](https://doi.org/10.1038/s41597-020-0438-2) genomes**:

  - Approximately 19 million SNPs called on 8 of the [MAGIC16](https://doi.org/10.1038/s41597-020-0438-2) genomes from the [3K rice genome project](https://doi.org/10.1186/2047-217x-3-7): Nipponbare, MH63, IR64, Azucena, ARC 10497, Zhenshan 97, Liu Xu, and N22.


#### Oryza CLIMtools 

The [Oryza CLIMtools portal](https://www.gramene.org/CLIMtools/oryza_v1.0/) continues to provide interactive web-based views of environment x genome (ExG) associations, RiboSNitch prediction, and correlations between the local environment and a pool of curated phenotypes (Ferrero-Serrano _et al_, 2024). Curated data corresponds to 413 geo-environmental variables describing the local environments of 658 Indica and 283 Japonica landrace varieties sequenced as part of the 3K Rice Genome Project. 


#### Phenotypic variation: QTLs and Structural Variants
 
- 20,483 Quantitative Trait Locus (QTL) remapped to the IRGSP-1.0 assembly by [KeyGene](http://www.keygene.com), and imported from [Gramene's legacy QTLs database](http://archive.gramene.org/qtl) and the [Q-Taro database](http://qtaro.abr.affrc.go.jp). Click [here](https://oryza-ensembl.gramene.org/Oryza_sativa/Gene/Summary?g=Os08g0531600;r=8:26501167-26506198;t=Os08t0531600-01) for a region rich in QTLs.

- 990 RFLPs and 288 SSRs from [Gramene’s legacy markers database](http://archive.gramene.org/markers) associated with traits/phenotypes. Example: [RZ413 is associated with 7 traits](https://oryza-ensembl.gramene.org/Oryza_sativa/StructuralVariation/Explore?db=core;r=1:17853225-17953226;sv=RZ413;svf=511;vdb=variation) for yield (spikelet number and panicle weight), abiotic stress (dry mass, sodium concentration, potassium uptake), biochemical (soluble protein content), and development (leaf senescence).
  

### Expression

Gene expression data for _O. sativa_ was curated and processed through the [EMBL-EBI Expression Atlas](https://www.ebi.ac.uk/gxa/plant/experiments). The set consists of 15 studies with baseline expression and 95 with differential expression. Baseline experiments, as well as expression of paralogs for the reference study, are available through our Gene Search (Expression panel). [Differential experiments](https://www.ebi.ac.uk/gxa/experiments?kingdom=Plants&species=Oryza+sativa&experimentType=Differential) are available at the Expression Atlas. Baseline gene expression is also available from the gene pages of the Genome Browser, see for example [Expression for Os05g0113900](https://oryza-ensembl.gramene.org/Oryza_sativa/Gene/ExpressionAtlas?g=Os05g0113900;r=5:738208-739079;t=Os05t0113900-01).


### Pathways

There are 339 pathways for _O. sativa_ Japonica Nipponbare (IRGSP1) curated by [Gramene’s Plant Reactome](https://plantreactome.gramene.org/) Team as of August 2023. In addition, these pathways were projected by orthology to the following 15 rice varieties: _O. australiensis_*, _O. barthii_, _O. brachyantha_, _O. glaberrima_, _O. glumaepatula_, _O. longistaminata_*, _O. meridionalis_, _O. meyeriana_ var. granulata, _O. minuta_*, _O. nivara_, _O. officinalis_*, _O. punctata_, _O. rufipogon_, _O. sativa_ aus subgroup, and _O. sativa_ Indica. 


### Comparative Genomics

No updates in the current release, please see [release notes for version 5.0](https://oryza.gramene.org/News?section=PanOryza%20Release%205).


## References

- Ferrero-Serrano A, Chakravorty D, Kirven KJ, Assmann SM. 2024. "Oryza CLIMtools: An Online Portal for Investigating Genome-Environment Associations in Rice." Plant Comm. 5(4):100813. doi: [10.1016/j.xplc.2024.100813](https://doi.org/10.1016/j.xplc.2024.100813).
  
- Harrison P, Ridwan Amode M, Austine-Orimoloye O et al. 2024. "Ensembl 2024." Nucleic Acids Research 52:D1(D891–D899). doi: [10.1093/nar/gkad1049](https://doi.org/10.1093/nar/gkad1049).

- Kumar A, Gupta C, Thomas J, Pereira A. 2021. "Genetic Dissection of Grain Yield Component Traits Under High Nighttime Temperature Stress in a Rice Diversity Panel." Front Plant Sci. 12:712167. doi: [10.3389/fpls.2021.712167](https://doi.org/10.3389/fpls.2021.712167).

- Lu Z, Marand AP, Ricci WA, Ethridge CL, Zhang X, Schmitz RJ. 2019. "The prevalence, evolution and chromatin signatures of plant regulatory elements." Nature Plants. doi: [10.1038/s41477-019-0548-z](https://doi.org/10.1038/s41477-019-0548-z).

- Tanaka N, Shenton M, Kawahara Y, et al. 2020. "Whole-genome sequencing of the NARO World Rice Core Collection (WRC) as the basis for diversity and association studies." Plant and Cell Physiology 61(5):922-932. doi: [10.1093/pcp/pcaa019](https://doi.org/10.1093/pcp/pcaa019).

- Tanaka N. Shenton M, Kawahara Y, et al. 2020. "Investigation of the Genetic Diversity of a Rice Core Collection of Japanese Landraces using Whole-Genome Sequencing." Plant and Cell Physiology 61(12):2087-2096. doi: [10.1093/pcp/pcaa125](https://doi.org/10.1093/pcp/pcaa125).
  
- Zhou Y, Kathiresan N, Yu Z, et al. 2024. "A high-performance computational workflow to accelerate GATK SNP detection across a 25-genome dataset." BMC biology. doi: [10.1186/s12915-024-01820-5](https://doi.org/10.1186/s12915-024-01820-5).


## Funding

Core funding for the project was provided by the National Science Foundation (NSF IOS-1127112) and ongoing support comes from the Agricultural Research Service of the U.S. Department of Agriculture (USDA ARS 8062-21000-051-00D).



### Oryza PanGenome Release 8.0
### Released: August 2024

GrameneOryza (https://oryza.gramene.org), funded by the USDA-ARS, is an open resource released to the public in 2015. The GrameneOryza team works closely with the community to support stewardship of rice genomics data, establish best-practices on managing the data, and provide opportunities for networking and capacity building within the community. We maintain a database of genome sequences, gene structure annotations, and comparative genomic analyses integrated with curated data from [EBI's Gene Expression Atlas](https://www.ebi.ac.uk/gxa/plant/experiments), [Gramene's Plant Reactome](https://plantreactome.gramene.org), and [Oryza CLIMtools](https://www.gramene.org/CLIMtools/oryza_v1.0/).

## What's New in release 8?

### New Functionality & Features

- Gramene Oryza's Search Results enhancements:

  1) The Papers tab listing publications describing a gene's function has now a user entry form (_Add Papers_) to suggest gene function given experimental evidence. Currently, there are 5,743 functionally curated Nipponbare genes. We invite you to check out your favorite gene and contribute your expertise! [This number is only from RAP-DB, ANDREW, are there aditional ones from Gene-RIF?]

  2) New Sequences tab provides quick access to gene, transcript and protein sequences for gene models.
     
  3) New Germplasm tab lists germplasm bearing a protein-truncating variant (PTVs are putative loss-of-function SNPs) within the canonical transcript of a gene model. The table includes links to IRRI and/or GRIN, as well as a way to search for other genes with a PTV in a given germplasm accession. The indexed PTVs include the following predicted functional effects: start lost, stop gained, stop lost, splice site acceptor, and splice site donor. _ANDREW please check this is correct_
  

### New & Updated Data

- No new genomes
  
***Genes***

- New pan-gene set identifiers provided as gene synonyms for . Example: [Os4530.POR.1.pan0017141 for Os07g0129700](https://oryza.gramene.org/Oryza_sativa/Gene/Summary?db=core;g=Os07g0129700;r=7:1565529-1572681;t=Os07t0129700-01). _Also as a new browser track? If so, for which genomes?_

***Genetic & Phenotypic Variation***

- _Oryza sativa_ Japonica Nipponbare (IRGSP1): XX million SNPs were assigned standard rsIDs provided by the [European Variation Archive](https://www.ebi.ac.uk/eva/).

- New variation data from kindly provided by Julie T and Andy Pereira from the University of Arkansas:

  1) Mini-core: 6.5M SNPs in 200 rice accessions [REF]
  2) RDP1: X SNPs in Y rice accessions [REF]
 
- New variation data from RAP-DB for the following populations: _KAPPEL - Are these going to be included in R8?_

  1) WRC: https://academic.oup.com/pcp/article/61/5/922/5758272
  2) JRC: https://academic.oup.com/pcp/article/61/12/2087/5921186
     
- No Kitakee mutations (VIVEK -- no genotypes provided in VCF, formatted incorrectly)

- Visualization of GWAS hits from XX phenotypic trait datasets on XX accessions of the XX population panel [REF]. Density plot for the GWAS hits for the traits is available on a karyotype view. Traits will be made searchable by trait ontology (TO) term.

- Table with overlapping germplasm? _Marcela working on it_

[Magic16](https://www.nature.com/articles/s41597-020-0438-2) genomes from the [3000 rice genome project](https://doi.org/10.1186/2047-217x-3-7).




## Summary

Gramene's Oryza Pan-Genome (https://oryza.gramene.org) is a web portal for comparative plant genomics focused on rice varieties. 

In its eigth release, we feature new SNP data for ... We provide updated functional gene associations from RAP-DB (June 2024) and GeneRIF from curated scientific literature.

In addition to genomic resources, GrameneOryza provides updates of news items, conferences, and community events; and feedback may be provided via a [contact form](https://oryza.gramene.org/feedback). 


## Release Contents -- Databases

### Genomes & Gene Annotations

There are a total of **35 genomes** in GrameneOryza: 28 rice genomes and 6 plant outgroups (B73 maize V4 and V5, _Sorghum bicolor_, _Arabidopsis thaliana_, grapevine, Selaginella, and Chlamydomonas - a single-celled green algae) and fruit fly Drosophila, in order to allow comparisons between higher eukaryotes, lower plants, and the model Arabidopsis in the Oryza pan-genome.

The site now includes NN [functionally curated gene annotations from GeneRIF and RAP-DB (June 2024)](https://oryza.gramene.org/?filters={%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:3,%22children%22:[{%22fq_field%22:%22capabilities%22,%22fq_value%22:%22pubs%22,%22name%22:%22publication%22,%22category%22:%22Curated%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:true}],%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20}&genomes=) in N species (XX Arabidopsis, XX rice, XX maize, XX chlamy, XX sorghum, XX Selaginella). For each of the genes, GrameneOryza's search results include a Papers tab listing directly relevant PubMed articles. Moreover, the associated Plant Ontology (PO) and Trait Ontology (TO) terms are searchable, for example: [PO: Anatomy: root](https://oryza.gramene.org/?filters={%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:3,%22children%22:[{%22fq_field%22:%22PO__ancestors%22,%22fq_value%22:%229005%22,%22name%22:%22root%22,%22category%22:%22Plant%20Ontology:%20anatomy%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:true}],%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20}&genomes=) or [TO: drought tolerance](https://oryza.gramene.org/?filters={%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:3,%22children%22:[{%22fq_field%22:%22TO__ancestors%22,%22fq_value%22:%22276%22,%22name%22:%22drought%20tolerance%22,%22category%22:%22Trait%20ontology%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:true}],%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20}&genomes=)


### Variation

- Approximately 19 million SNPs called per each of 8 [Magic16](https://doi.org/10.1038/s41597-020-0438-2) genomes from the [3K rice genome project](https://doi.org/10.1186/2047-217x-3-7): Nipponbare, MH63, IR64, Azucena, ARC 10497, Zhenshan 97, Liu Xu, and N22.

- 31 million SNPs determined in _O. sativa_ Japonica Nipponbare IRGSP1 imported from the Euorpean Variation Archive (EVA) encompass the following data sets:


### Expression

No updates in the current release, please see [release notes for version 3.0](https://oryza.gramene.org/News?section=PanOryza%20Release%203).


### Pathways

No updates in the current release, please see [release notes for version 3.0](https://oryza.gramene.org/News?section=PanOryza%20Release%203).


### Comparative Genomics

No updates in the current release, please see [release notes for version 5.0](https://oryza.gramene.org/News?section=PanOryza%20Release%205).


## References

- 3,000 rice genomes project. The 3,000 rice genomes project. Gigascience. 2014;3: 7. doi:10.1186/2047-217X-3-7



## Funding

Core funding for the project was provided by the National Science Foundation (NSF IOS-1127112) and ongoing support comes from the Agricultural Research Service of the U.S. Department of Agriculture (USDA ARS 8062-21000-051-00D).



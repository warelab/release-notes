### Oryza PanGenome Release 7.0
### Released: July 2023

GrameneOryza (https://oryza.gramene.org) is an open source resource released to the public in XXX [ask Sharon: OGE] currently funded by the USDA-ARS. The GrameneOryza team works closely with the community to support stewardship of rice genomics data, establish best-practices on managing the data, and provide opportunities for networking and capacity building within the community. We maintain a database of genome sequences, gene structure annotations, and comparative genomic analyses integrated with curated data from [EBI's Gene Expression Atlas](https://www.ebi.ac.uk/gxa/plant/experiments) and [Gramene's Plant Reactome](https://plantreactome.gramene.org).

## What's New in release 7?

### New Functionality

- Oryza CLIMtools portal with interactive web-based views of environment x genome associations, RiboSNitch prediction, and correlations between the local environment and a pool of curated phenotypes. 

- Updated RAP-DB gene models and nomenclature, see for example
  
- 11,793 [functionally curated genes from GeneRIF and RAP-DB](https://oryza.gramene.org/?filters={%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:3,%22children%22:[{%22fq_field%22:%22capabilities%22,%22fq_value%22:%22pubs%22,%22name%22:%22publication%22,%22category%22:%22Curated%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:true}],%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20}&genomes=) (6 species: 7184	Arabidopsis, 4102	rice, 354	maize, 135 chlamy, 15	sorghum, 3 Selaginella). For each of these genes, GrameneOryza's search results include a Papers tab listing directly relevant PubMed articles. Moreover, the associated Plant Ontology (PO) and Trait Ontology (TO) terms are searchable, for example: [PO: Anatomy: root](https://oryza.gramene.org/?filters={%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:3,%22children%22:[{%22fq_field%22:%22PO__ancestors%22,%22fq_value%22:%229005%22,%22name%22:%22root%22,%22category%22:%22Plant%20Ontology:%20anatomy%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:true}],%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20}&genomes=) or [TO: drought tolerance](https://oryza.gramene.org/?filters={%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:3,%22children%22:[{%22fq_field%22:%22TO__ancestors%22,%22fq_value%22:%22276%22,%22name%22:%22drought%20tolerance%22,%22category%22:%22Trait%20ontology%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:true}],%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20}&genomes=)
 - _Not new, but link, stats, and examples weren't provided before_

- Links to the Gene Tree Curation Tool in the Homology tab of Nipponbare genes. Example: [Os05g0569300](http://curate.gramene.org/admin/curationUI/oryza_v5/?since=4479&gene=Os05g0569300) - _Not new, but wasn't reported before_

- Updated nomenclature for reference sequence assemblies based on standard recommendations from the NSF-DBI (#2029854): CIBR-BBSRC: PanOryza: Globally coordinated genomes, proteomes and pathways for rice, see [species list]([https://ensembl.sorghumbase.org/species.html](https://oryza-ensembl.gramene.org/species.html)). [remove?  ask Sharon: is this different from the update in R5?]


### New Data

***Genetic Variation***

Approximately 19 million SNPs called per each of four [Magic16](www.nature.com/articles/s41597-020-0438-2) genomes from the [3000 rice genome project](https://doi.org/10.1186/2047-217x-3-7) were called by Dr. Robert Wing's group from resequencing reads using [GATK4](https://gatk.broadinstitute.org/hc/en-us) software:

- _Oryza sativa_ circum-Basmati var. ARC 10497
- _Oryza sativa_ Xian/Indica-1A var. Zhenshan 97
- _Oryza sativa_ Xian/Indica-3B2 var. Liu Xu
- _Oryza sativa_ circum-Aus1 var. N22

Genetic variation for _O. sativa_ Japonica Nipponbare IRGSP1 was imported from the Euorpean Variation Archive (EVA). It consists of the following data sets:

- 25.8 million SNPs from Duitama _et al_ (2015)
- 3 million SNPs from BGI (2004)
- 1.6 million SNPs from OMAP (2007)
- 366K SNPs from the [3K rice genome project](https://doi.org/10.1186/2047-217x-3-7)
- 157K SNPs from McNally _et al_ (2009)
- 1.3K SNPs from Zhao et al (2010)


## Summary

Gramene's Oryza Pan-Genome (https://oryza.gramene.org) is a web portal for comparative plant genomics focused on rice varieties. 

In its seventh release, we feature new 3K SNP data for four Magic16 genomes: ARC 10497, Zhenshan 97, Liu Xu, and N22. We are also introducing the Oryza CLIMtools portal to study Environment x Genome x Phenotype Associations in rice.

In addition to genomic resources, GrameneOryza provides updates of news items, conferences, and community events; and feedback may be provided via a [contact form](https://oryza.gramene.org/feedback). 


## Release Contents -- Databases

### Genomes & Gene Annotations

There are a total of **36 genomes** in GrameneOryza: 28 rice genomes and 8 non-rice genomes.
_Should we mention # of genes or any other stats? _

### Variation

- Approximately 19 million SNPs called per each of 8 [Magic16](https://doi.org/10.1038/s41597-020-0438-2) genomes from the [3K rice genome project](https://doi.org/10.1186/2047-217x-3-7): Nipponbare, MH63, IR64, Azucena, ARC 10497, Zhenshan 97, Liu Xu, and N22.

- 31 million SNPs determined in _O. sativa_ Japonica Nipponbare IRGSP1 from the following data sets:

* 25.8 million SNPs from Duitama _et al_ (2015)
* 3 million SNPs from BGI (2004)
* 1.6 million SNPs from OMAP (2007)
* 366K SNPs from the [3K rice genome project](https://doi.org/10.1186/2047-217x-3-7)
* 157K SNPs from McNally _et al_ (2009)
* 1.3K SNPs from Zhao et al (2010)

- 20,483 Quantitative Trait Locus (QTL) remapped to the IRGSP-1.0 assembly by industry collaborator [KeyGene](http://www.keygene.com). Of those, 19,435 were taken from [Gramene's legacy QTLs database](http://archive.gramene.org/qtl), and 1,048 from the [Q-Taro database](http://qtaro.abr.affrc.go.jp).


### Expression

No updates in the current release, please see [release notes for version 3.0](https://oryza.gramene.org/News?section=PanOryza%20Release%203).

### Pathways

No updates in the current release, please see [release notes for version 3.0](https://oryza.gramene.org/News?section=PanOryza%20Release%203).

### Comparative Genomics

No updates in the current release, please see [release notes for version 5.0](https://oryza.gramene.org/News?section=PanOryza%20Release%205).


## References

Zhou Y, Chebotarov D, Kudrna D, Llaca V, Lee S, Rajasekar S, et al. "A platinum standard pan-genome resource that represents the population structure of Asian rice." Sci Data. 2020;7: 113. doi: [10.1038/s41597-020-0438-2](https://doi.org/10.1038/s41597-020-0438-2).

The 3,000 rice genomes project. GigaScience, Volume 3, Issue 1, December 2014, 2047-217X-3-7, https://doi.org/10.1186/2047-217X-3-7

Duitama et al. 2015
BGI 2004
OMAP 2007
McNally et al. 2009
Zhao et al. 2010


## Funding

Core funding for the project was provided by the National Science Foundation (NSF IOS-1127112) and ongoing support comes from the Agricultural Research Service of the U.S. Department of Agriculture (USDA ARS 8062-21000-041-00D).


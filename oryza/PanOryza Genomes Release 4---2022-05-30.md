## Oryza PanGenome Release 4
### Released: May 2022
## Summary

Gramene's Oryza Pan-Genome (https://oryza.gramene.org) is a web portal for comparative plant genomics focused on rice varieties. In its fourth release, three new rice genomes were added to the portal: 

* _Oryza sativa indica_ XI-adm var. MH63 [(Zhou _et al_, 2020)](https://doi.org/10.1038/s41597-020-0438-2)

* _Oryza sativa indica_ XI-1A var. ZS97 [(Zhou _et al_, 2020)](https://doi.org/10.1038/s41597-020-0438-2)

* _Oryza sativa japonica_ var. KitaakeX [(Jain _et al_, 2019)](https://doi.org/10.1186/s12864-019-6262-4)

In this fourth release, we completed the 16 accessions of the Platinum Standard RefSeqs (also known as the 16 MAGIC rice cultivars) or PSRefSeq collection with Oryza sativa indica cv. Minghui 63 or MH63, a representative of the XI-adm subpopulation, and O. sativa indica cv. Zhengshan 97, Zhenshan 97 or ZS97, representing the XI-1A subpopulation. The 16 MAGIC cultivars were selected to represent the 15 rice subpopulations and the largest admixed rice population, i.e. XI-adm described by [Zhou et al (2020)](https://doi.org/10.1038/s41597-020-0438-2). Notably, the assembly for MH63 and ZS97 are considered to be T2T (or Telomere-to-Telemere), which means that thy are complete and gapless: MH63 has 10 T2T chromosomes, and ZS97 has 7 of them [(Song et al, 2021)](https://doi.org/10.1016/j.molp.2021.06.018).

The Kitaake accession is a fast cycling rice variety (seed to seed in nine weeks), making it an excellent model for functional genomics in rice. The accession carries the rice XA21 immune receptor and its genome was sequenced and assembled, annotated and analyzed for variation by Pamela Ronalds and collaborators [(Jain et al, 2019)](https://doi.org/10.1186/s12864-019-6262-4) and it was used to generate mutagenized lines, of which 1,504 have been sequenced and indexed [(Li et al, 2017)](https://doi.org/10.1105/tpc.17.00154). 

The rice pangenomes collection now amounts to a total of 28 Oryza genomes. Together with the genomes of _Leersia perrieri_ (the most closely related species to the Oryza in the Oryzeae tribe), 6 plant outgroups (B73 maize, sorghum, Arabidopsis thaliana, grapevine, a vascular plant, and a single-celled green algae) and Drosophila, a total of 38,308 GeneTree families were constructed comprising 1,239,682 individual genes (1,294,888 input proteins) in order to allow comparisons between higher eukaryotes, lower plants, and the model Arabidopsis. See updated stats [here](https://oryza-ensembl.gramene.org/prot_tree_stats.html). Our complete genome collection is being made readily available for BLAST alignments.  

Core funding for the project was provided by the National Science Foundation (NSF IOS-1127112) and the Agricultural Research Service of the U.S. Department of Agriculture (USDA ARS 8062-21000-041-00D).  


## Release Information
- [Overall Highlights](#overall-highlights)
- [Databases](#databases)
- [Statistics](#statistics)
- [References](#references)

## Overall Highlights 

Our comparative genomics collection was updated to include a total of 38,308 protein-coding gene family trees using Ensembl Compara software (Herrero _et al_, 2016). The new trees were constructed with 1,294,888 input proteins from 1,239,682 individual genes from the 28 Oryza genomes, _L. perrieri_, and 7 outgroup species (Arabidopsis thaliana, sorghum, grapevine, Chlamydomonas, Selaginella, B73 maize in assembly versions 4 and 5, and Drosophila).


## Databases 
### Comparative Genomics

[**Gene Trees.**](https://oryza-ensembl.gramene.org/prot_tree_stats.html) A total of 38,308 protein-coding gene family trees were constructed using the peptide encoded by the canonical transcript (i.e., a representative transcript for a given gene) for each of 1,239,682 individual genes (1,294,888 input proteins) from 36 genomes.

[**Whole-Genome Alignments**](https://oryza-ensembl.gramene.org/compara_analyses.html). No updates in the current release, please see [release notes for version 3.0](https://oryza.gramene.org/news).

[**Synteny**](https://oryza-ensembl.gramene.org/compara_analyses.html). No updates in the current release, please see [release notes for version 3.0](https://oryza.gramene.org/news).

### Variation

No updates in the current release, please see [release notes for version 3.0](https://oryza.gramene.org/news).

### Expression

No updates in the current release, please see [release notes for version 3.0](https://oryza.gramene.org/news).

### Pathways

No updates in the current release, please see [release notes for version 3.0](https://oryza.gramene.org/news).

## References

- Herrero J, Muffato M, Beal K, Fitzgerald S, Gordon L, Pignatelli M, et al. "Ensembl comparative genomics resources." Database. 2016;2016. doi: [10.1093/database/bav096](http://doi.org/10.1093/database/bav096).
- Jain R, Jenkins J, Shu S, Chern M, Martin JA, Copetti D, et al. "Genome sequence of the model rice variety KitaakeX." BMC Genomics. 2019;20: 905. doi: [10.1186/s12864-019-6262-4](http://doi.org/10.1186/s12864-019-6262-4).
- Zhou Y, Chebotarov D, Kudrna D, Llaca V, Lee S, Rajasekar S, et al. "A platinum standard pan-genome resource that represents the population structure of Asian rice." Sci Data. 2020;7: 113. doi: [10.1038/s41597-020-0438-2](http://doi.org/10.1038/s41597-020-0438-2).
- Song, J.-M. et al. Two gap-free reference genomes and a global view of the centromere architecture in rice. Mol. Plant 14.2021; 1757–1767: 12.	doi: [10.1016/j.molp.2021.06.018](https://doi.org/10.1016/j.molp.2021.06.018).
- Li, G. et al. The Sequences of 1504 Mutants in the Model Rice Variety Kitaake Facilitate Rapid Functional Genomic Studies. Plant Cell. 2017; 29: 1218–1231. doi: [10.1105/tpc.17.00154)](https://doi.org/10.1105/tpc.17.00154).


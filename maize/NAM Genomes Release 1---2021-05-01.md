## Maize PanGenome Release 1.0
### Released: July, 2021
## Summary
[maize-pangenome.gramene.org](http://maize-pangenome.gramene.org), a web portal for comparative plant genomics focused on Maize crop varieties,
has now released its first version. It provides access to 35 assembled genomes, including the 25 maize NAM founders and the B73 reference
([Hufford et al, 2021; Science in press](https://doi.org/10.1101/2021.01.14.426684)). The team contributed maize gene annotations constructed
with a genome annotation workflow that uses an ensemble approach and canonical transcripts selected for downstream analysis with a
new tool that integrates gene expression data with length criteria
([Olson, Ware, 2021; Bioinformatics in press](https://doi.org/10.1101/2020.12.15.422742)).
For more information see [NAM genomes](https://nam-genomes.org) and MaizeGDB's [NAM project page](https://maizegdb.org/NAM_project).

The maize gene models, together with seven outgroups (*Arabidopsis thaliana, Oryza sativa Japonica, Sorghum bicolor, Vitis vinifera ssp. vinifera PN40024 v3, Selaginella moellendorffii, Chlamydomonas reinhardtii, and Drosophila melanogaster*)
were used to build 31,412 protein-coding gene family trees. Data from 25 baseline gene expression studies from the Expression Atlas,
and 269 orthology-based pathway projections from the Plant Reactome are provided for B73 (APGv4).

The genome databases were built in direct collaboration with the [Gramene](http://gramene.org) and
[Ensembl Plants](http://plants.ensembl.org) projects. Other data sets were facilitated via
collaborations with the [Expression Atlas](https://www.ebi.ac.uk/gxa/plant/experiments),
and the [Plant Reactome](https://plantreactome.gramene.org/) databases.

## Release Information
- [Overall Highlights](#overall-highlights)
- [Comparative Genomics](#compara)
- [Gene Expression](#expression)
- [Pathways](#pathways)
- [Funding](#funding)

## Overall Highlights {#overall-highlights}
- Maize reference genomes: B73 and the 25 NAM founder accessions were assembled and annotated (Hufford et. al. 2021).
- Six plant outgroup species (Japonica rice, B73 maize, *Arabidopsis thaliana*, grapevine,
  a vascular plant, and a single-celled green algae) and *Drosophila melanogaster* were
  used to build 31,412 protein-coding gene family trees from 1,276,195 protein sequences.
- We also have gene expression and orthology-based pathway projections for the reference 
  genome *Zea mays* B73.

## Comparative Genomics {#compara}

[**Gene Trees.**](http://maize-pangenome-ensembl.gramene.org/prot_tree_stats.html) A total of
31,412 protein-coding gene family trees were constructed using the peptide encoded by
the canonical transcript (i.e., a representative transcript for a given gene) for each
of 1,276,195 individual genes (1,315,155 input proteins) from 34 plant genomes.

## Expression {#expression}

Gene expression data for the Zea mays B73 genome reference was curated and
processed through the [EMBL-EBI Expression Atlas](https://www.ebi.ac.uk/gxa/plant/experiments).
The set consists of 25 studies with baseline expression and 55 with differential expression. Baseline experiments
are available through our Gene Search (Expression panel) and Genome Browser; [differential experiments](https://www.ebi.ac.uk/gxa/experiments?kingdom=Plants&species=Zea+mays&experimentType=Differential) are available
at the Expression Atlas.

## Pathways {#pathways}

In this first release, we also feature 269 orthology-based maize pathways associated with 1,540 genes in the [Plant Reactome](http://gramene.org),
the pathway knowledgebase. We utilize the Reactome pathway data model to represent plant metabolic, transport and
signaling pathways, developmental processes, organ differentiation, and transcriptional regulatory networks. Manual
biocuration is conducted in the reference species rice (Oryza sativa Japonica) and pathways are then projected via gene
orthology to the B73 Zea mays (pior reference), and other crops and model plants, lower plants and single-cell photoautotrophs.

## Funding {#funding}

Core funding for the project is provided by the Agricultural Research Service of the U.S. Department of Agriculture (USDA ARS 8062-21000-041-00D).
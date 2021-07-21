## Maize PanGenome Release 1.0
### Released: July, 2021
## Summary
[maize-pangenome.gramene.org](http://maize-pangenome.gramene.org), a web portal for comparative plant genomics focused on Maize crop varieties,
has now released its first version. It provides access to 28 Maize reference genomes, including
the three most recent versions of B73 and 25 NAM founder lines, together with seven other species selected for comparative analysis.
Genome assemblies and annotations of the NAM founders are described in Hufford et al, 2021.
The genome databases were built in direct collaboration with the [Gramene](http://gramene.org) and
[Ensembl Plants](http://plants.ensembl.org) projects. Other data sets were facilitated via
collaborations with the [Expression Atlas](https://www.ebi.ac.uk/gxa/plant/experiments),
and the [Plant Reactome](https://plantreactome.gramene.org/) databases.

## Release Information
- [Overall Highlights](#overall-highlights)
- [Comparative Genomics](#compara)
- [Gene Expression](#expression)
- [Pathways](#pathways)

## Overall Highlights {#overall-highlights}
- Maize reference genomes: B73 and the 25 NAM founder accessions were assembled and annotated (Hufford et. al. 2021).
- Six plant outgroup species (Japonica rice, B73 maize, Arabidopsis thaliana, grapevine,
  a vascular plant, and a single-celled green algae) and Drosophila melanogaster were
  used to build 31,412 protein-coding gene family trees from 1,276,195 protein sequences.
- We also have gene expression and orthology-based pathway projections for the reference 
  genome Zea mays B73.

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


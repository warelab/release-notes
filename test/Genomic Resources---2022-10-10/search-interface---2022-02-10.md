## Using the genes search interface {#search-interface}

Watch the [demo video on YouTube](https://www.youtube.com/watch?v=nnAEnA9qTMY&t=2s).

Searching for a gene given a standard gene identifier can be done in a couple of ways:
- Click the spyglass icon and type/paste `SORBI_3006G095600` it into the search box, for example
- Link directly to [http://sorghumbase.org/genes?idList=SORBI_3006G095600](https://www.sorghumbase.org/genes?idList=SORBI_3006G095600)

NOTE: See the "Gene Search" section below for tips to search by gene name.

If you don't know the gene id you can search by pathway and taxonomy, [see example](https://www.sorghumbase.org/genes?filters={%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:5,%22children%22:[{%22fq_field%22:%22pathways__ancestors%22,%22fq_value%22:%221119332%22,%22name%22:%22Jasmonic%20acid%20biosynthesis%22,%22category%22:%22Plant%20Reactome%20Pathway%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:false},{%22fq_field%22:%22taxonomy__ancestors%22,%22fq_value%22:%224558%22,%22name%22:%22Sorghum%20BTx623%22,%22category%22:%22Taxonomy%22,%22leftIdx%22:3,%22rightIdx%22:4,%22negate%22:false,%22showMenu%22:false,%22marked%22:true}],%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20}&genomes=):

1. In the search box, start typing `jasmonic acid biosynthesis` and choose the matching Plant Reactome Pathway term
2. To limit the search to genes in *Sorghum bicolor* BTx623, type `sorghum` in the search box and select the matching Taxonomy term

The search results page is organized into three areas:

1. A panel on the left side shows the status of the search
2. At the top is a visualization of the genomic locations of genes matching the search
3. Below this is a paginated list of genes

Each gene has a set of tabs that can be expanded to explore more details:

- **Germplasm** - Germplasm bearing a protein-truncating variant (PTV), specifically a PTV's putative loss-of-function allele
- **Sequences** - Genomic, transcript and peptide sequences
- **Location** - Lightweight genome browser showing gene structure
- **Expression** - Baseline gene expression viewer from [EBI-Expression Atlas](https://www.ebi.ac.uk/gxa)
- **Homology** - Gene family tree viewer (opens by default if only one gene is found)
- **Pathways** - Associated pathways in [Gramene’s Plant Reactome](https://plantreactome.gramene.org)
- **Xrefs** - Cross-references to other databases


### Germplasm Tab

The Germplasm tab lists accessions which bear a protein-truncating variant  or PTV, its predicted consequence, whether it is in homozygous or heterozygous form, and the genotyping study from which it was identified. The table includes links to GRIN or SorbMutDB (USDA-Lubbock-EMS lines), as well as a way to search for other genes with a PTV in a given germplasm accession. The indexed PTVs include the following predicted functional effects: start lost, stop gained, stop lost, splice site acceptor, and splice site donor.

![Germplasm View](images/germplasm_search.png)

See also the Genetic Variation section below.


### Sequences Tab

This tab provides quick access to three kind of sequences: Genomic, Transcript and Peptide, where CDS and UTRs are color-coded.

![Sequences View](images/sequences_search.png)


### Location Tab

![Location View](images/location_search.png)

- The "Ensembl Browser" option takes you to the corresponding Gene page in the Ensembl Genome Browser platform.
- The "Phytozome" option takes you to the corresponding Gene report in the Phytozome (Sbicolor_v5_1) site. 

### Expression Tab

Gene expression data for sorghum BTx623 v3 is available in this tab for baseline experiments and expression of paralogs for the reference study from the EMBL-EBI Expression Atlas, and Electronic Fluorescent Pictograph (eFP) expression visualizations from the .
Gene expression data for sorghum BTx623 v3 was curated and processed through the EMBL-EBI Expression Atlas. As of release 7, the curated set consists of eigth studies with baseline expression and three with differential expression. Differential experiments are available at the Expression Atlas. Baseline gene expression is also available from the gene pages of the Genome Browser, see for example Expression for SORBI_3006G095600. Data for the eFP browser on the Expression tab of the SorghumBase search results projects gene expression from a Developmental and a Stress Atlas by McCormick et al (2018).

#### eFP Browser

eFP browsers are available for sorghum, maize and Arabidopsis. Sorghum gene expression herein corresponds to the Developmental and Stress Atlases by McCormick et al (2018).

![eFP Expression View](images/efp_search.png)


#### Expression Atlas (All Studies)


![Expression Atlas View](images/expression_search.png)


#### Expression Atlas Paralogs (Reference Study - All paralogs)

![Paralogs Expression View](images/paralogs_search.png)


See also the Expression section below.


### Homology Tab

#### Gene Family Tree (Protein Alignment Overview)

- This view opens by default if only one gene is found in the query. Trees are built with canonical transcripts and their protein domains are color coded. 

- You may configure to show the species, gene name, gene and/or protein identifier by clicking in the spider gear icon to th eleft of the Display Mode panel. 

- Click on a triangle to expand or collapse a tree branch. Click on a gene name to get more information such as the gene's description, genomic location, and number of transcripts. 

- For the target gene (the one at the top of the tree), you may get a list of paralogs by clicking on "Show paralogs", or you may bring any other gene to the top of the tree by clicking on "Focus on this gene" instruction. 

![Gene Tree - Search Results Default View](images/default_search_tree.png)

- A list of orthologs or paralogs may also be obtained by clicking on the corresponding "Search Filters" at the bottom of the Homology panel. 

- The "Ensembl Gene Tree view" instruction takes you to the same gene family tree in the Ensembl Genome Browser platform. 

- The "Curate" option takes you to the Gramene Gene Tree Tool, which allows you to evaluate the structure of the gene model and flag it for potential annotation errors.


#### Multiple Sequence Alignment

Zoom into the amino acid-level of the family tree.

![Multiple Sequence Alignment View](images/aa_alignment_search.png)

 
#### Neighborhood Conservation

Zoom out +/- 10 flanking genes.

![Gene Neighborhood View](images/gene_neighborhood_search.png)


### Pathways Tab


![Pathways View](images/pathways_search.png)

See also the Pathways section below.


### Papers Tab (_Add Papers_)

Genes that have undergone functional curation (e.g., [SORBI_3001G488700](http://sorghumbase.org/genes?idList=SORBI_3001G488700)) will have scientific literature associated with them in this tab. 

![Papers](images/papers_search.png)

The Papers tab is complemented with an [easy-to-fill form](https://docs.google.com/forms/d/e/1FAIpQLSey-xPyTysdd9c2phXT6kcbjEDeCppG4dLG7LjZCeLpx_KGog/viewform) to _Submit a gene function_. 


### XRefs Tab

![Cross-References](images/xrefs_search.png)

Cross-links for additional resources (e.g., QuickGO, UniGene, UniProt, UniParc, ENA, ENA proteins) might be available in the Gramene database for the query gene.

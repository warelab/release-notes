**_Vitis vinifera_ PanGenome**

This user guide refers to the contents of the fourth public release (February 2024) of the Grape PanGenome. Currently, the PanGenome hosts 29 genomes including 16 _Vitis vinifera_ genomes, and 8 outgroups (_Arabidopsis thaliana_, _Oryza sativa Japonica_, _Solanum lycopersicum_, _Sorghum bicolor_, _Zea mays B73_, _Selaginella moellendorffii_, _Chlamydomonas reinhardtii_, and _Drosophila melanogaster_).

At present, most data types are only available for the Vitis vinifera L. ssp. vinifera Pinot noir PN40024 reference version 4, so this guide will focus on the phytochrome B gene model (PHYB), using its v4 gene identifier: Vitvi05g00130 (VIT_05s0077g00940 in v3).

---

Let’s begin!

Go to [http://vitis.gramene.org/](http://vitis.gramene.org/)

Locate the search box at the top left corner of the page. Type a search term (gene, species, pathway, ontology term, protein domain, etc.). For the exercises below, we will focus on searching for the grape PHYB gene or Vitvi05g00130.

**PanGenome Search Interface**

**Querying a Gene**

Let’s start by typing "PHYB" in the search box and observe the auto-completion suggestions that pop-up as you type, as well as the various data categories in which the potential results are organized.


![auto-complete](images/PHY_search_vitis1.png "PanGrape auto-complete")


The image below shows the default view of the [results from searching for PHYB](http://vitis.gramene.org/?filters={%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:3,%22children%22:[{%22fq_field%22:%22_terms%22,%22fq_value%22:%22PHYB%22,%22name%22:%22PHYB%22,%22category%22:%22Gene%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:true}],%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20}&genomes=) (phytochrome B). Depending on how the gene name, locus name, gene synonyms and gene description were assigned to a gene model, you may get one or multiple hits for a query. You may narrow down your search by selecting the species you are interested in.

![PHYB](images/PHYB_results_vitis2.png "Search PHYB")

Type "PHYB" in the search box. You will see five closely related gene names associated with this term. Select “PHYB” from the Gene category under results. Notice that it has a number next to it; this indicates that there are 72 hits associated with it (clicking on it will display the 49 genes from 35 genomes these hits refer to). To limit the results to grape genomes, you may click on the spider gear icon and deselect the non-grape outgroups (e.g., _Arabidopsis_, _Oryza_, _Solanum_, _Sorghum_, _Vitis_, _Selaginella_, _Chlamydomonas_, and _Drosophila_). Or deselect all genomes using the "None" option and select only PN40024 v4, then click on “Submit”. The later filtering step should render the v4 model as a single result with the Homology tab open; however, when you do this, you will be also pruning the tree to only display the species you selected so this is not ideal for most cases and you might be better off searching a gene by its unique identifer (Vitvi05g00130 in this case), so we will delete the query for PHYB by clicking on the trash icon at the top left of the results bar and type Vitvi05g00130 in the sarch box anew.

![search genomes](images/select_genomes_vitis3.png "Select species")

For single gene results, the Homology tab will be in full display, else click on the Homology tab for your gene of interest.  For this exercise, you will notice that the v3 (VIT_05s0077g00940) and v4 (Vitvi05g00130) models appear identical. As mentioned above, we will focus on v4 models, for which gene expression and pathways data is available from the EBI Expression Atlas and Plant Reactome, respectively.

![search results](images/Vitvi05g00130_overview_vitis4.png "Search results")

Before we go on, here is a summary of the seven data categories in which the results of a gene search are organized. These also correspond to the tabs at the top of the results panel for each gene in the image above.

* **Sequences** - Genomic, transcript and peptide sequences
* **Location** - Genomic context
    * Ensembl Browser (Gramene Maize PanGenome)
    * Phytomine
* **Expression** - Baseline gene expression from [EBI-Expression Atlas](https://www.ebi.ac.uk/gxa)
* **Homology** - Customizable Ensembl Compara gene family trees with displays:
    * Alignment Overview (full-length gene)
    * Multiple-Sequence Alignment (zoom into the amino acid level)
    * Neighborhood Conservation View (zoom out +/- 10 flanking genes)
* **Pathways** - Association to pathways in [Gramene’s Plant Reactome](https://plantreactome.gramene.org)
* **Papers** - Curated publications supporting function for the gene. Includes link to a form to submit a gene's function
* **Xrefs** - Cross-references to other databases


Note: More complex queries can be constructed using junctions such as AND/OR (click on your search term in the query box to see your options) to combine genes identified by gene name or gene ID, or genes that share, for example, an InterPro domain or a Gene Ontology function, or simply to retrieve a list of genes associated with a pathway. The query box below can be obtained by typing “inflorescence development” (trait) in the search box, and changing the default “AND” to “OR”). Query terms may be deleted, copied, moved or negated (see options in the Filters inset on the left).


![complex queries](images/pangrape5.png "Complex queries")


Note that the number of hits for your search is reflected in the karyotype view on top, where every chromosome of a genome is represented as a colorful box and every hit of a query is represented as a tick mark overlaid on its corresponding karyotype. Therefore, you will see six tick marks along the karyotype corresponding to the six genes in the “inflorescence development” pathway.

To follow this exercise, you could click on “delete” for the inflorescence pathway and select “All” the available species in the gene tree, then select the Homology view for the Vitvi05g00130 gene. However, to simplify the images, we will simply redo a new search using “Vitvi05g00130”.


![PHYB tree view](images/pangrape6.png "Homology default view")


Clicking on the spider gear that precedes the “Display Mode” drop-down menu, allows you to configure the labels for members of the family tree, the choices are: Species, Gene name, Gene ID, and Protein ID (see image below).


![configure labels](images/pangrape7.png "Configure species labels")


**Homology Views**

Click on the “Display Mode” drop-down menu to select one of three displays for the Homology view: Alignment overview, Multiple Sequence Alignment, and Neighborhood conservation.


![display modes](images/pangrape8.png "Homology Display Modes")


1. The **Alignment Overview** allows you to view the entire length of the protein. Proteins are color-coded by InterPro domain. Click anywhere in one of the colored protein domains to reveal its name and some statistics. 

    

![interpro domains](images/pangrape9.png "Protein domains")



You may expand collapsed taxonomic clades, which are symbolized by triangles along the branches of the tree, by clicking on the black (speciation) or red (duplication) nodes and selecting the option “Expand”. Already expanded clades can be contracted by selecting the option “Collapse” that appears upon clicking a node.



![expand or collapse](images/pangrape10.png "Expand or collapse tree clades")



For the following exercises, let’s expand all the rosid clades so that we can see every grape gene in the tree as a single row. You will notice that most of the Chardonnay gene models appear split in two. 


![expanded tree](images/pangrape11.png "Split Chardonnay genes")


Putative split genes are marked with a blinking yellow node (it will only blink for a few seconds after the clade is open), and when you click on it, you will read “gene_split” following the species name (see inset below for the first split gene pair: VvChar04.ver1.0.g339770 and VvChar04.ver1.0.g339780). 


![gene split](images/pangrape12.png "gene_split")


Notice that these gene pairs map to contiguous regions in the chromosome and hence have consecutive gene ids, for example, the second putative split gene pair in the tree consists of VvChar04.ver1.0.g009660 at position GCs104:9825009-9826201:- (N-terminal) and VvChar04.ver1.0.g009650 at position GCs104:9816229-9824982:- (C-terminal). 

You may also prune the tree to only display a subset of the 37 species, by clicking on the spider gear of the Search Filters panel. Hover your mouse over to see a message like: “Genomes Filter” and Searching 37 genomes. Click on it and select the species you want to limit your search to, and also those that you wish to be included in the Homology tree view.


![prune tree](images/pangrape13.png "Select Genomes")


Please note that resizing the gray slider that surrounds the entire protein allows you to navigate along it. Also, at the bottom of the panel notice the number of Homologs, Orthologs, and Paralogs. By clicking on any of them, the corresponding gene list will be displayed. See for example, the list of 4 paralogs of Vitvi05g00130 in the figure below.



![paralogs](images/pangrape14.png "Paralogs")


Let’s go back to the Homology view of the Vitvi05g00130 gene search results, and select the Multiple-Sequence Alignment from the Display Mode menu.



2. The **Multiple-Sequence Alignment** allows you to zoom into the amino acid level. Drag the slider along the length of the protein to change the area of detail. This view allows you to observe the degree of amino acid sequence conservation and identify areas where lack of conservation could indicate biologically significant differences such as alternatively spliced forms or mere annotation artifacts. See for example clade-specific amino acid conservation or how amino acid conservation drops and picks back up for the split gene model pairs, and where a missing stretch of amino acids in the GAF domain of the VvChar04.ver1.0.g315290 model might indicate an annotation artifact (or an alternatively spliced transcript, if there is experimental evidence for it).



![multi-sequence](images/pangrape15.png "Multiple Sequence Alignment")



    Luckily, we have a tool to capture your observations for dubious annotations. Click on the “Curate” button at the bottom of the inset, and you will be taken to Gramene’s Gene Tree tool. In it, you will see the same tree from the Homology view and on the right, you will be able to qualify gene models as OK or “poor” quality, and submit your annotations via e-mail (see below). The same display options described here are available to zoom in and out the tree view in the tool.


![gene tree tool](images/pangrape16.png "Gramene Gene Tree Tool")



3. **Neighborhood Conservation View**

    This view presents the target gene in the middle with a red line across the best ortholog in each species in the tree plus 10 flanking genes upstream and downstream color-coded by gene family. This allows you to identify structural variants and Presence/Absence variants in the region in question.


    
![neighborhood](images/pangrape17.png "Neighborhood Connservation")


**Sequences**



**Location**


    Switch to the “Location” tab to observe the gene structure and alternative transcripts for your target gene. Exons are shown as red boxes, introns as lines, and UTRs as orange boxes. Use the sizing tool to modify the region under observation. The search filters allow users to list all genes in the chromosome or all the genes in the region specified in the field. Links to the [Vitis PanGenome Browser](http://vitis-ensembl.gramene.org/Vitis_vinifera/Gene/Summary?g=Vitvi05g00130;r=5:710743-718860;t=Vitvi05g00130.t01) is provided at the bottom of the tab.



![location](images/pangrape18.png "Location")



**Expression**

***All studies***

    This view depicts baseline gene expression data for defined organism parts (as shown in the image below: fruit, pericarp, and seed), cultivars or developmental stages (the latter only available in the [Expression Atlas website](https://www.ebi.ac.uk/gxa/genes/vit_05s0077g00940). Experiments are organized by study on the left side, and by tissue or developmental stage on the top of the graph. 


    Unique data points are colored in blue, with intensity increasing in proportion to the level of expression. What this means is that higher expression data points are shown in darker blue. 


    When you hover the cursor over a data point, the data point is highlighted in yellow, and a more detailed data summary will pop up to reveal study (Da Silva _et al_, 2013 in this case), part of the plant, and a quantitative measure of gene expression (in TPM units).



![expression search results](images/pangrape19.png "Expression")



    You may find additional expression data views in our collaborators’ sites, the [Plant Reactome (Pathways tab)](https://plantreactome.gramene.org/content/detail/R-VVN-8933856), and the [Expression Atlas](https://www.ebi.ac.uk/gxa/genes/VIT_05s0077g00940).


    

![atlas widget PR](images/pangrape20.png "Expression in Plant Reactome")


    
![expression atlas](images/pangrape21.png "Expression Atlas")


***Reference study (all paralogs)***

This view shows gene expression for all paralogs of the gene in the reference study.

add image



**Pathways**

From the literature, we know that PHYB is part of the circadian rhythm and inflorescence development pathways. Accordingly, the Pathways panel shows that this gene product catalyzes a reaction in both pathways: conversion of inactive PHYB into active PHYB (circadian rhythm) and expression of PhyB under long day photoperiod (inflorescence development), see the image below.

When you hover the cursor over the reaction in the hierarchy on the left side, the diagram on the right will show the reaction in the context of the corresponding pathway. 

Under “Search Filters”, you have the option of getting a list of all genes in a reaction or an entire pathway. You may also navigate to the Gene and corresponding Reaction pages in the Plant Reactome site, where you will be able to perform more complex analyses of omics data, including pathway-based comparisons across species.

An example of such analysis is illustrated in a short video in the [Gramene series](https://www.youtube.com/channel/UCMtmq20XMccsNUaACuqQJ-w) where transcriptomics data is overlaid onto orthology-based projected pathways to compare expression between mutant and wild-type tissues at distinct developmental stages.

![pathways](images/pangrape22.png "Pathways")


**Papers**

For genes with curated gene function, this tab displays a list of papers with PubMed identifiers. For all genes, a link to a form to provide gene function (supported with ontology terms and experimental validation described in publications).

IMAGE


**Cross-References**

In the Xref tab, you will find references to your gene of interest in other databases, including ENA, UniProt, UniParc, and UniGene. Please note that the image below shows cross-references for the v3 model, GRMZM2G017616. As described above, additional databases such as Phytomine are cross-referenced in the Location tab.


    

![x-refs](images/pangrape23.png "Cross-References")


**Gene & Transcript pages**

From the Location tab, click on the Ensembl Browser link and you will be taken to the gene summary page (or Gene tab, shown below). Click on a transcript from the Transcripts Table and you will reach the selected transcript page. Here are the links for the corresponding [PHYB gene page](http://test.gramene.org/Vitis_viniferapn40024/Gene/Summary?g=Vitvi05g00130;r=5:1193907-1202258;t=Vitvi05g00130_t001) and [transcript page](http://test.gramene.org/Vitis_viniferapn40024/Transcript/Summary?db=core;g=Vitvi05g00130;r=5:1193907-1202258;t=Vitvi05g00130_t001) in the Grapevine Pan-Genome browser. Click on the options on the left menu to visualize a gene tree, obtain a list of orthologues or paralogues, gene ontology associations, gene expression anatograms, sequence (cDNA, exons, protein), protein domains, etc. 



![gene page](images/pangrape24.png "Ensembl gene page")


The image below corresponds to the [Protein summary view of the Vitvi05g00130_t001.1](http://test.gramene.org/Vitis_viniferapn40024/Transcript/ProteinSummary?db=core;g=Vitvi05g00130;r=5:1193907-1202258;t=Vitvi05g00130_t001) (grape PHYB) transcript.


![protein summary](images/pangrape25.png "Protein domains summary (transcript)")


**Comparative Genomics**


####
**Gene trees**

Ensembl Compara pipeline - [Example](http://test.gramene.org/Vitis_viniferapn40024/Gene/Compara_Tree?db=core;g=Vitvi05g00130;r=5:1193907-1202258;t=Vitvi05g00130_t001)


![gene trees](images/pangrape26.png "PHYB gene family tree")



**Expression**


####
**mRNA and protein alignments**

For the PN40024 v4 genome there are seven tracks with ESTs and EST clusters data available. You can get a complete list by clicking on the spider gear symbol for “Configure this page” (left side menu) or “Configure this image” (Location panel), see the inset in the image below. In addition to grape ESTs, there are EST clusters for the following species or clades: Dicots, Monocots, Arabidopsis, maize, rice, and grape. Click on the square that precedes the name of the track to turn it on or off and configure it with the available options (normal, with labels, stacked, etc.).


![mRNA and protein](images/pangrape27.png "mRNA & protein alignments")



### 
**Genetic, Structural & Phenotypic Variation**

## Variation {#variation}

Variation in SorghumBase is available for short variants (genetic variation, which in turn may be naturally occurring or chemically induced) and QTL variants associated with physical traits.


### Genetic & Phenotypic Variation

Genetic variation data sets are available as over 59 million sorghum variants including more than 46 million naturally ocurring Single Nucleotide Polymorphisms (SNPs), and almost 13 million chemically-induced variants (i.e., ethyl methanesulfonate (EMS)-induced mutations). In addition, we host nearly 6,000 QTLs for 148 sorghum traits from the Sorghum QTL Atlas.

### Naturally occurring genetic variation - SNPs

Currently in SorghumBase, there are three SNPs data sets, two on sorghum BTx623 and one on Tx2783.

#### BTx623

- The Lozano SNP dataset (Lozano et al, 2021) consists of nearly 13 million SNPs in 499 sorghum accessions, including lines from the TERRA-MEPP and TERRA-REF population panels, and the samples previously reported by Emma Mace and collaborators (Mace et al, 2013).

- The Boatwright SNP dataset (Boatwright et al, 2022) consists of almost 44 million genetic variants including nearly 38 millon SNPs and 5 million indels genotyped in 400 Sorghum Association Panel (SAP) accessions via whole-genome sequencing (WGS).

#### Tx2783

- About 32.5 million SNPs were called in 400 SAP lines by Rod Wing's group at King Abdullah University of Science and Technology with the GATK4 pipeline [Yong Zhou, Nagarajan Kathiresan and Rod A. Wing (2023), manuscript in preparation], and are now available from the Tx2783 genome browser. See for example [4_6047465_C_T](https://ensembl.sorghumbase.org/Sorghum_tx2783pac/Variation/Sample?db=core;r=4:6046965-6047965;v=4_6047465_C_T;vdb=variation;vf=11387812), a SNP predicted to introduce a STOP codon and result in a truncated [SbiRTX2783.04G076100](https://ensembl.sorghumbase.org/Sorghum_tx2783pac/Gene/Summary?db=core;g=SbiRTX2783.04G076100;r=4:6046424-6048133;t=SbiRTX2783.04G076100.1;v=4_6047465_C_T;vdb=variation;vf=11387812) protein product.


**Literature References**

[Diploid genome assembly of the Malbec grapevine cultivar enables haplotype-aware analysis of transcriptomic differences underlying clonal phenotypic variation](https://doi.org/10.1101/2023.11.30.569420). Calderón L, Carbonell-Bejerano P, Muñoz P, Bree L, Sola C et al. 2023. biorxiv.

[A super-pangenome of the North American wild grape species](https://doi.org/10.1186/s13059-023-03133-2). Cochetel N, Minio A, Guarracino A, Garcia JF, Figueroa-Balderas R et al. 2023. Genome Biology 24:290.

[The grapevine genome sequence suggests ancestral hexaploidization in major angiosperm phyla](https://www.nature.com/articles/nature06148).
Jaillon O, Aury JM, Noel B, Policriti A, Clepet C, Casagrande A, Choisne N, Aubourg S, Vitulo N, Jubin C et al. 2007. Nature. 449:463-467.

[Diploid Genome Assembly of the Wine Grape Carménère](https://www.g3journal.org/content/9/5/1331.full). Minio, A., Massonnet, M., Figueroa-Balderas, R., Castro, A., and Cantu, D. 2019. G3: Genes, Genomes, Genetics. 9: 1331-1337.

[The genetic basis of sex determination in grapes](https://doi.org/10.1038/s41467-020-16700-z). Massonnet M, Cochetel N, Minio A, Vondras AM, Lin J et al. 2020.  Nat Commun. 11: 2902.

[The wild grape genome sequence provides insights into the transition from dioecy to hermaphroditism during grape domestication](https://doi.org/10.1186/s13059-020-02131-y). Badouin H, Velt A, Gindraud F, Flutre T, Dumas V et al. 2020. Genome Biol. 21:223.

[Haplotyping the Vitis collinear core genome with rhAmpSeq improves marker transferability in a diverse genus](https://doi.org/10.1038/s41467-019-14280-1). Zou C, Karn A, Reisch B, Nguyen A, Sun Y et al. 2019. Nat Commun. 11: 413.

[An improved reference of the grapevine genome reasserts the origin of the PN40024 highly homozygous genotype](https://doi.org/10.1093/g3journal/jkad067). Velt A, Frommer B, Blanc S, Holtgräwe D, Duchêne E et al. 2023. G3. 13(5):jkad067.

[The genomic diversification of clonally propagated grapevines](https://doi.org/10.1186/s12864-019-6211-2). Vondras AM, Minio A, Blanco-Ulate B, Figueroa-Balderas R, Penn MA et al. 2019. BMC Genomics.

[The population genetics of structural variants in grapevine domestication](https://www.nature.com/articles/s41477-019-0507-8). Zhou Y, Minio A, Massonnet M, Solares E, Lv Y et al. 2019. Nature Plants. 5: 965–979.


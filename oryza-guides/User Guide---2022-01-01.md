**_Oryza_ PanGenome User Guide**

This user guide refers to the contents of the Third Public Release (November 2021) of the Rice PanGenome. Currently, the PanGenome hosts 25 rice genomes and Leersia perrieri, an ancestor of rice, 11 of those Oryzae genomes were recently described (Zhou et al, 2021), and 7 outgroups (Arabidopsis thaliana, Sorghum bicolor, Vitis vinifera ssp. vinifera PN40024, Selaginella moellendorffii, Chlamydomonas reinhardtii, Drosophila melanogaster, and 2 versions of Zea mays B73  (Hufford et al, 2021; Jiao et al, 2017)).

At present, most data types are only available for Japonica rice, so this guide will focus on the Grain Width on chromosome 8 gene model, also known as GW8.

- [PanGenome Search interface](#search-interface)
- [Searching for a gene](#gene-search)
- [Ensembl Gene page](#gene-pages)
- [Add/remove data tracks](#configure-image)
- [Ensembl Comparative Genomics](#comparative-genomics)
- [Gene expression](#gene-expression)
- [Variation](#variation)
- [Literature references](#references)

---

Let’s begin!

Go to https://oryza.gramene.org/

Locate the search box at the top left corner of the page. Type a search term (gene, species, pathway, ontology term, protein domain, etc.). For the exercises below, we will focus on searching for the rice GW8 gene (Grain Width on chromosome 8, OsSPL16 or Os08g0531600), a transcription factor containing an SBP-domain transcription factor that promotes cell division and grain filling by regulating grain width, size, shape and quality (Wang et al, 2012). It was identified in a domestication gene among 55 known selective domestication sweeps or signatures (Chen et al, 2019).


## PanGenome Search Interface {#search-interface}

**Querying a Gene**

To get an exact match, it is preferable to use the gene identifier (Os08g0531600 in this case). However, if this is not available from the literature, you could try searching for the gene’s common name (OsSPL16) or a synonym (SPL16), its symbol (GW8) or the gene’s description (grain width on chromosome 8). Please keep in mind that there are genes with similar names or symbols in different species that may not necessarily be orthologous, so it is advisable to narrow your search to your species of interest (see below). 

If there are multiple results for your query, it is important to browse through the categories on display (the number in the small gray box next to a hit, indicates the number of genes associated with the suggested result), and select the best hit for your query from the suggested results. See for example, the suggested results categories (hits) when I search for “jasmonic” in the image below.



After selecting a results category (for example, by clicking on the JAR1 InterPro Family from the above example), you may limit your results to only rice genomes or select a specific rice variety. Do this by clicking on the “Genomes Filter” spider gear icon on the top right of the results box and select/deselect the target (or unwanted) species like the non-rice outgroups (Arabidopsis, Zea mays, Sorghum bicolor, Vitis vinifera, Selaginella, Chlamydomonas, and Drosophila), as shown in the image below. Click the Submit button or simply close the Genomes of Interest window to save your selection.




For the remainder of the exercises, we will use Os08g0531600 to find the GW8 gene in the Oryza PanGenome. Type  “Os08g0531600” in the search box and select the gene from the displayed results by clicking on it.

The image below shows the default Homology (gene family tree) view of the results from searching for Os08g0531600. Depending on how a gene’s name, symbol, locus name, synonyms, and description were assigned to a gene model, you may get one or multiple hits for your query. Check them all until you are certain to have identified your target gene. If you had to limit the species to find your gene of interest, remember to select again the species that you want included in the phylogeny tree.






Here is a summary of the five data categories in which the results of a gene search are organized. These also correspond to the tabs at the top of the results panel in the image below.

**Location** - Genomic context

  *Ensembl Browser* (Gramene Rice PanGenome)
  
  *Phytomine*
  
**Expression** - Baseline gene expression from EBI-Expression Atlas

**Homology** - Customizable Ensembl Compara gene family trees with displays:

  *Alignment Overview* (full-length gene)
  
  *Multiple-Sequence Alignment* (zoom into the amino acid level)
  
  *Neighborhood Conservation View* (zoom out +/- 10 flanking genes)
  
**Pathways** - Association to pathways in Gramene’s Plant Reactome

**Xrefs** - Cross-references to other databases



Note: More complex queries can be constructed using junctions such as AND/OR (click on your search term in the query box to see this option) to combine genes identified by gene name or gene ID, or genes that share, for example, an InterPro domain or a Gene Ontology function, or simply to retrieve a list of genes associated with a pathway. The query box below can be obtained by typing the term “jasmonic acid biosynthesis” in the search box, and changing the default “AND” to “OR”). Query terms may be deleted, copied, moved or negated; see the options in the inset below. 



To follow this exercise, click on “delete” for the JA pathway so there is only one result left, the Os08g0531600 gene.

Clicking on the spider gear that precedes the “Display Mode” drop-down menu, allows you to configure the labels for members of the family tree, the choices are: Species, Gene name, Gene ID, and Protein ID (see image below).



**Homology Views**

Click on the “Display Mode” drop-down menu to select one of three displays for the Homology view: Alignment overview, Multiple Sequence Alignment, and Neighborhood conservation.




*Alignment Overview*. This view allows you to view the entire length of the protein. Proteins are color-coded by InterPro domain. Click anywhere in the colored protein domain to reveal its name and some statistics. 



You may expand collapsed taxonomic clades, which are symbolized by triangles along the branches of the tree, by clicking on the black (speciation) or red (duplication) nodes and selecting the option “Expand”. Already expanded clades can be contracted by selecting the option “Collapse” that appears upon clicking a node.


You may also prune the tree to only display a subset of the 34 species, by clicking on the spider gear of the Search Filters panel. Hover your mouse over to see the message: “Genomes Filter. Searching 34 genomes” (see image above when narrowing your search to oryza species). Click on it and select the species you want to limit your search to, and also those that you wish to be included in the Homology tree view.

Please note that resizing the gray slider that surrounds the entire protein in the top ideogram of the Homology allows you to navigate along it. Also, at the bottom of the panel, notice the number of Homologs, Orthologs, and Paralogs. By clicking on any of them, the corresponding gene list will be displayed. See for example, the list of 26 paralogs in the figure below.



Let’s go back to the Os08g0531600 gene search results (Homology default view). 

*Multiple-Sequence Alignment*. This view allows you to zoom into the amino acid level. Drag the slider along the length of the protein to change the area of detail. This view allows you to observe the degree of amino acid sequence conservation and identify areas where lack of conservation could indicate biologically significant differences such as alternatively spliced forms or mere annotation artifacts. See for example how the O. sativa indica IR8 ortholog of Os08g0531600 differs in a well-conserved region of the SBP domain (blue box) indicating an internal deletion or a potential annotation error. The O. rufipogon ortholog of Os08g0531600 also varies slightly from consensus towards the 3’-end of the region shown in the image, which invites further exploration to identify whether the difference is biologically significant or an annotation artifact.



*Neighborhood Conservation View*. This view presents the target gene in the middle with a red line across the best ortholog in each species in the tree plus 10 flanking genes upstream and downstream color-coded by gene family. The target gene and its orthologs, for example, are shown in green and shaded based on similarity with the gene of interest. Genes from unrelated families are shown in gray. Non-coding genes are depicted as smaller gray boxes (with shading intensity proportional to number of genes in the corresponding group). The colorful scheme allows researchers to identify structural variants and Presence/Absence variants in the region in question. 


At the bottom of the Homology view, you will find a link to the corresponding Ensembl Gene Tree view. The trees displayed in the Oryza PanGenome Search interface are the same as those in Ensembl Plants, which were built using the EnsemblCompara pipeline (Vilella et al, 2019). 


**Location**

Switch to the “Location” tab to observe the gene structure and alternative transcripts for your target gene. Exons are shown as red boxes, introns as lines, and UTRs as orange boxes. Use the sizing tool to modify the region under observation. The search filters allow users to list all genes in the chromosome or all the genes in the region specified in the field. Links to the Oryza PanGenome Browser and PhytoMine are provided at the bottom of the tab.



**Expression**

This view depicts baseline gene expression data for a whole plant (top anatogram on the left of the results box) and for the plant’s reproductive organs (bottom anatogram). Experiments are organized by study on the left side, and by tissue or developmental stage on the top of the graph. 
Unique data points are colored in blue, with intensity increasing in proportion to the level of expression. What this means is that higher expression data points are shown in darker blue. 
When you hover the cursor over a data point, the data point is highlighted in yellow, and a more detailed data summary pops up. The corresponding tissue is also colored in pink in the anatograms.







If instead, you hover over a tissue on the anatogram on the left, the name of the tissue will pop up, and the points corresponding to expression data from that tissue will light up. 




**Pathways**

Examples of manually curated biological pathways for rice (Os Japonica) in the Plant Reactome include classical intermediary metabolism, signaling, transcriptional regulation and developmental pathways. In the future, curatorial work will be extended to cell cycle, apoptosis and resistance to pathogen infection.

From the literature, we know that GW8 is part of the “Regulation of seed size” pathway. Accordingly, the Pathways panel shows that this gene product catalyzes two black box reactions in this pathway.
When you hover the cursor over the reaction in the hierarchy on the left side, the diagram on the right will show the reaction in the context of the corresponding pathway. 
Under “Search Filters”, you have the option of getting a list of all genes in a reaction or an entire pathway. You may also navigate to the Gene and corresponding Reaction pages in the Plant Reactome site, where you will be able to perform more complex analyses of omics data, including pathway-based comparisons across species.
An example of such an analysis is illustrated in a short video in the Gramene series where transcriptomics data is overlaid onto orthology-based projected pathways to compare expression between mutant and wild-type tissues at distinct developmental stages (see Gramene's YouTube channel).


**Cross-References**

In the Xref tab, you will find references to your gene of interest in other databases, such as UniProt, UniParc, and UniGene. Currently, this view is dissabled in the Oryza PanGenome. However, as described above, additional databases such as Phytomine are cross-referenced in the Location tab.


---

## Ensembl Gene & Transcript pages {#gene-pages}

From the Location tab, click on the Ensembl Browser link and you will be taken to the gene summary page (shown below). Click on any of the transcripts from the Transcripts Table and you will reach the selected transcript page. Here are the links for the corresponding Os08g0531600 gene page and transcript page (tabs) in the Oryza PanGenome browser. Click on the options on the left menu to visualize a gene tree, obtain a list of orthologs or paralogs, gene ontology associations, gene expression anatograms, sequence (cDNA, exons, protein), protein domains, etc. 



The image below corresponds to the Exons sequence view of the  Os08t0531600-01 transcript.




## Comparative Genomics {#comparative-genomics}

*Gene trees* (Ensembl Compara pipeline) - GRAIN-WIDTH 8 Gene Tree Example


In addition to phylogenetic trees, available from both, the Oryza PanGenome Search Interface and Genome Browser, whole-genome pairwise alignments (81 for the Japonica reference), as well as synteny maps (19 for the Japonica reference) for 10 of the Oryza genomes are available in the Gramene website. Click here for a GW8 region comparison or a synteny map for the GW8 region between Os japonica and O. rufipogon in the Gramene Genome Browser.
New alignments and synteny maps with the new Oryza genomes will be made available here in future releases.

## Baseline Gene Expression (EBI-Atlas) {#gene-expression}

Baseline gene expression data from 10 datasets for O. sativa japonica curated and processed by the EMBL-EBI Expression Atlas are also available from the Oryza PanGenome Search, the Ensembl PanGenome gene pages, and the corresponding Plant Reactome panels. The Expression panel of the Search results was described above in detail. The same Expression Atlas view for the GW8 gene is available from the Gramene browser gene page and the Plant Reactome Expression panel (find a link to the Plant Reactome at the bottom of the Pathways panel of the Search results).



GW8 gene expression in the Gramene browser gene page



GW8 gene expression in the Plant Reactome Expression panel



GW8 gene expression in the Expression Atlas


## Genetic, Structural & Phenotypic Variation {#variation}

Coming soon… 

Genetic variation and QTL phenotypic variation is available for the *O. sativa Japonica* and *Indica* references, *O. glaberrima* and *O. glumaepatula* in the main Gramene website. Genetic variation data sets will be made available here in future releases. Click here for an image or a table of genetic variation for the GW8 gene in the Gramene Ensembl browser. There are no structural / copy number variants associated with the WG8 gene. Phenotypic (QTL) associations are available under the Variation (Phenotype annotations) track of the Gene page “Configure this image” option.



## Literature References {#references}


Chen Erwang, Xuehui Huang, Zhixi Tian, Rod A.Wing, and Bin Han. 2019. The Genomics of Oryza Species Provides Insights into Rice Domestication and Heterosis. Annu. Rev. Plant Biol. 70:639–65
doi: 10.1146/annurev-arplant-050718-100320.

Hufford, Matthew B., Arun S. Seetharam, Margaret R. Woodhouse, Kapeel M. Chougule, Shujun Ou, Jianing Liu, William A. Ricci, et al. 2021. “De Novo Assembly, Annotation, and Comparative Analysis of 26 Diverse Maize Genomes.” bioRxiv. doi: 10.1101/2021.01.14.426684.

Jiao, Yinping, Paul Peluso, Jinghua Shi, Tiffany Liang, Michelle C. Stitzer, Bo Wang, Michael S. Campbell, et al. 2017. “Improved Maize Reference Genome with Single-Molecule Technologies.” Nature 546 (7659): 524–27.

Vilella AJ, Severin J, Ureta-Vidal A, Heng L, Durbin R, Birney E. EnsemblCompara GeneTrees: Complete, duplication-aware phylogenetic trees in vertebrates. 2009. Genome Res. 19(2):327-35. doi: 10.1101/gr.073585.107.

Wang S,Wu K, Yuan Q, Liu X, Liu Z, et al. 2012. Control of grain size, shape and quality by OsSPL16
in rice. Nat. Genet. 44:950–54.

Zhou, Yong, Dmytro Chebotarov, Dave Kudrna, Victor Llaca, Seunghee Lee, Shanmugam Rajasekar, Nahed Mohammed, et al. 2020. “A Platinum Standard Pan-Genome Resource That Represents the Population Structure of Asian Rice.” Scientific Data 7 (1): 113.


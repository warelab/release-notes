_Last updated: Aug 15, 2024_

**_Oryza_ PanGenome User Guide**

This user guide refers to the contents of the Eighth Public Release (August 2024) of the Rice PanGenome. Currently, the PanGenome hosts 28 rice genomes including _Leersia perrieri_, an ancestor of rice, 16 Oryzeae Platinum Standard RefSeqs (the MAGIC16 or PSRefSeq collection; Zhou et al, 2020), domesticated African rice, short life cycle KitaakeX, and heirloom US Carolina Gold Rice. In addition, release 8 included the genomes of six plant outgroups (_Arabidopsis thaliana_, _Sorghum bicolor_, _Vitis vinifera_ ssp. _vinifera_ PN40024, _Selaginella moellendorffii_, _Chlamydomonas reinhardtii_, and 2 assembly versions of _Zea may_s B73 (Hufford et al, 2021; Jiao et al, 2017), and _Drosophila melanogaster_.

At present, most data types are only available for Japonica rice, therefore this guide will focus on data and views for the Grain Width on chromosome 8 (GW8) gene model.

- [PanGenome Search interface](#search-interface)
- [Searching for a gene](#gene-search)
- [Ensembl Gene page](#gene-pages)
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

![jasmonic_search](images/Picture1.png)


After selecting a results category (for example, by clicking on the JAR1 InterPro Family from the above example), you may limit your results to only rice genomes or select a specific rice variety. Do this by clicking on the “Genomes Filter” spider gear icon on the top right of the results box and select/deselect the target (or unwanted) species like the non-rice outgroups (Arabidopsis, Zea mays, Sorghum bicolor, Vitis vinifera, Selaginella, Chlamydomonas, and Drosophila), as shown in the image below. Click the Submit button or simply close the Genomes of Interest window to save your selection.

![genomes_of_interest](images/Picture2.png)


For the remainder of the exercises, we will use Os08g0531600 to find the GW8 gene in the Oryza PanGenome. Type  “Os08g0531600” in the search box and select the gene from the displayed results by clicking on it.

The image below shows the default Homology (gene family tree) view of the results from searching for Os08g0531600. Depending on how a gene’s name, symbol, locus name, synonyms, and description were assigned to a gene model, you may get one or multiple hits for your query. Check them all until you are certain to have identified your target gene. If you had to limit the species to find your gene of interest, remember to select again the species that you want included in the phylogeny tree.

![default_search_results](images/Picture3.png)




Here is a summary of the seven data categories in which the results of a gene search are organized. These also correspond to the tabs at the top of the results panel in the image below.

- **Germplasm** - Germplasm bearing a protein-truncating variant (PTV), specifically a PTV's putative loss-of-function allele

- **Sequences** - Genomic, transcript and peptide sequences
 
- **Location** - Genomic context

   - *Ensembl Browser* (Gramene rice pan-genome)
  
- **Expression** - Baseline gene expression from EBI-Expression Atlas

- **Homology** - Customizable Ensembl Compara gene family trees with displays:

   - *Alignment Overview* (full-length gene)
  
   - *Multiple-Sequence Alignment* (zoom into the amino acid level)
  
   - *Neighborhood Conservation View* (zoom out +/- 10 flanking genes)
  
- **Pathways** - Association to pathways in Gramene’s Plant Reactome

- **Papers** - Scientific literature associated with genes that have undergone functional curation from RAP-DB and GeneRIF

- **Xrefs** - Cross-references to other databases



### Location Tab

![homology](images/Picture4.png)


Note: More complex queries can be constructed using junctions such as AND/OR (click on your search term in the query box to see this option) to combine genes identified by gene name or gene ID, or genes that share, for example, an InterPro domain or a Gene Ontology function, or simply to retrieve a list of genes associated with a pathway. The query box below can be obtained by typing the term “jasmonic acid biosynthesis” in the search box, and changing the default “AND” to “OR”). Query terms may be deleted, copied, moved or negated; see the options in the inset below. 

![genomes_filter](images/Picture5.png)


To follow this exercise, click on “delete” for the JA pathway so there is only one result left, the Os08g0531600 gene.

Clicking on the spider gear that precedes the “Display Mode” drop-down menu, allows you to configure the labels for members of the family tree, the choices are: Species, Gene name, Gene ID, and Protein ID (see image below).

![configure_labels](images/Picture6.png)


### Homology Tab

Click on the “Display Mode” drop-down menu to select one of three displays for the Homology view: Alignment overview, Multiple Sequence Alignment, and Neighborhood conservation.


![alignment_overview](images/Picture7.png)


**Alignment Overview**. This view allows you to view the entire length of the protein. Proteins are color-coded by InterPro domain. Click anywhere in the colored protein domain to reveal its name and some statistics. 

![interpro_inset](images/Picture8.png)



You may expand collapsed taxonomic clades, which are symbolized by triangles along the branches of the tree, by clicking on the black (speciation) or red (duplication) nodes and selecting the option “Expand”. Already expanded clades can be contracted by selecting the option “Collapse” that appears upon clicking a node.

![expand_collapse_node](images/Picture9.png)


You may also prune the tree to only display a subset of the 34 species, by clicking on the spider gear of the Search Filters panel. Hover your mouse over to see the message: “Genomes Filter. Searching 34 genomes” (see image above when narrowing your search to oryza species). Click on it and select the species you want to limit your search to, and also those that you wish to be included in the Homology tree view.

Please note that resizing the gray slider that surrounds the entire protein in the top ideogram of the Homology allows you to navigate along it. Also, at the bottom of the panel, notice the number of Homologs, Orthologs, and Paralogs. By clicking on any of them, the corresponding gene list will be displayed. See for example, the list of 26 paralogs in the figure below.


![paralogs](images/Picture10.png)


Let’s go back to the Os08g0531600 gene search results (Homology default view). 

**Multiple-Sequence Alignment**. This view allows you to zoom into the amino acid level. Drag the slider along the length of the protein to change the area of detail. This view allows you to observe the degree of amino acid sequence conservation and identify areas where lack of conservation could indicate biologically significant differences such as alternatively spliced forms or mere annotation artifacts. See for example how the O. sativa indica IR8 ortholog of Os08g0531600 differs in a well-conserved region of the SBP domain (blue box) indicating an internal deletion or a potential annotation error. The O. rufipogon ortholog of Os08g0531600 also varies slightly from consensus towards the 3’-end of the region shown in the image, which invites further exploration to identify whether the difference is biologically significant or an annotation artifact.

![multiple_sequence_alignment](images/Picture11.png)


**Neighborhood Conservation View**. This view presents the target gene in the middle with a red line across the best ortholog in each species in the tree plus 10 flanking genes upstream and downstream color-coded by gene family. The target gene and its orthologs, for example, are shown in green and shaded based on similarity with the gene of interest. Genes from unrelated families are shown in gray. Non-coding genes are depicted as smaller gray boxes (with shading intensity proportional to number of genes in the corresponding group). The colorful scheme allows researchers to identify structural variants and Presence/Absence variants in the region in question. 

![neigborhood_view](images/Picture12.png)


At the bottom of the Homology view, you will find a link to the corresponding Ensembl Gene Tree view. The trees displayed in the Oryza PanGenome Search interface are the same as those in Ensembl Plants, which were built using the EnsemblCompara pipeline (Vilella et al, 2019). 


### Germplasm Tab

The Germplasm tab lists accessions which bear a protein-truncating variant or PTV, its predicted consequence, whether it is in homozygous or heterozygous form, and the genotyping study from which it was identified. The table includes links to IRRI or GRIN, as well as a way to search for other genes with a PTV in a given germplasm accession. The indexed PTVs include the following predicted functional effects: start lost, stop gained, stop lost, splice site acceptor, and splice site donor.

![Germplasm View](images/germplasm_search.png) - _Swap with rice image_

See also the Genetic Variation section below.


### Sequences Tab

This tab provides quick access to three kind of sequences: Genomic, Transcript and Peptide, where CDS and UTRs are color-coded.

![Sequences View](images/sequences_search.png) - _Swap with rice image_



### Location Tab

Switch to the “Location” tab to observe the gene structure and alternative transcripts for your target gene. Exons are shown as red boxes, introns as lines, and UTRs as orange boxes. Use the sizing tool to modify the region under observation. The search filters allow users to list all genes in the chromosome or all the genes in the region specified in the field. Links to the Oryza PanGenome Browser and PhytoMine are provided at the bottom of the tab.

![location](images/Picture13.png)


### Expression Tab

Curated gene expression data for Japonica Nipponbare is available in this tab for baseline experiments and expression of paralogs for the reference study, processed through the EMBL-EBI Expression Atlas.


#### Expression Atlas (All Studies)

As of GrameneOryza release 8, the curated EBI Expression Atlas set consists of 15 _Oryza sativa_ studies with baseline expression, and 95 _Oryza_ spp. studies with differential expression (including 14 in _O. sativa indica_). Differential experiments are available at the [Expression Atlas](https://www.ebi.ac.uk/gxa/plant/experiments). 

This view depicts baseline gene expression data for a whole plant (top anatogram on the left of the results box) and for the plant’s reproductive organs (bottom anatogram). Experiments are organized by study on the left side, and by tissue or developmental stage on the top of the graph. 
Unique data points are colored in blue, with intensity increasing in proportion to the level of expression. In other words, higher expression data points are shown in darker blue. 
When you hover the cursor over a data point, the data point is highlighted in yellow, and a more detailed data summary pops up. The corresponding tissue is also colored in pink in the anatograms.

![expression_plant](images/Picture14.png)


If instead, you hover over a tissue on the anatogram on the left, the name of the tissue will pop up, and the points corresponding to expression data from that tissue will light up. 

![expression_seed](images/Picture15.png) - _remove or swap with above rice image?_


![Expression Atlas View](images/expression_search.png) - _remove or swap with above rice image?_

Baseline gene expression is also available from the gene pages of the Genome Browser, see for example [Expression for Os08g0531600](https://oryza-ensembl.gramene.org/Oryza_sativa/Gene/ExpressionAtlas?g=Os08g0531600;r=8:26501167-26506198;t=Os08t0531600-01).


#### Expression Atlas Paralogs (Reference Study - All paralogs)

This is a visualization of gene expression of the paralogs for the query gene from the reference study described in the header.

![Paralogs Expression View](images/paralogs_search.png) - _swap with rice image_


See also the Expression section below.



### Pathways Tab

Examples of manually curated biological pathways for rice (Os Japonica) in the Plant Reactome include classical intermediary metabolism, signaling, transcriptional regulation and developmental pathways. In the future, curatorial work will be extended to cell cycle, apoptosis and resistance to pathogen infection.

From the literature, we know that GW8 is part of the “Regulation of seed size” pathway. Accordingly, the Pathways panel shows that this gene product catalyzes two black box reactions in this pathway.
When you hover the cursor over the reaction in the hierarchy on the left side, the diagram on the right will show the reaction in the context of the corresponding pathway. 
Under “Search Filters”, you have the option of getting a list of all genes in a reaction or an entire pathway. You may also navigate to the Gene and corresponding Reaction pages in the Plant Reactome site, where you will be able to perform more complex analyses of omics data, including pathway-based comparisons across species.


![pathways](images/Picture16.png)



### Papers Tab (_Add Papers_)

Genes that have undergone functional curation (e.g., Os08g0531600) will have scientific literature associated with them in this tab. However, an [easy-to-fill form](https://docs.google.com/forms/d/e/1FAIpQLSey-xPyTysdd9c2phXT6kcbjEDeCppG4dLG7LjZCeLpx_KGog/viewform) allows researchers to also _Submit a gene function_ for review.

![Papers](images/papers_search.png) - _swap with rice image_



### Cross-References Tab

In the Xref tab, you will find references to your gene of interest in other databases, such as UniProt, UniParc, UniGene, ENA, and PanOryza pan-gene.

![xrefs](images/xrefs_search.png) - _ADD image_


---

## Ensembl Gene & Transcript pages {#gene-pages}

From the Location tab, click on the Ensembl Browser link and you will be taken to the gene summary page (shown below). Click on any of the transcripts from the Transcripts Table and you will reach the selected transcript page. Here are the links for the corresponding Os08g0531600 gene page and transcript page (tabs) in the Oryza PanGenome browser. Click on the options on the left menu to visualize a gene tree, obtain a list of orthologs or paralogs, gene ontology associations, gene expression anatograms, sequence (cDNA, exons, protein), protein domains, etc. 

![ensembl_gene_page](images/Picture17.png)


The image below corresponds to the Exons sequence view of the Os08t0531600-01 transcript.

![ensembl_exons_view](images/Picture18.png)


## Comparative Genomics {#comparative-genomics}

**Gene trees** (Ensembl Compara pipeline) - GRAIN-WIDTH 8 Gene Tree Example

![GW8_ensembl_gene_tree](images/Picture22.png)


In addition to phylogenetic trees, available from both, the Oryza PanGenome Search Interface and Genome Browser, whole-genome pairwise alignments (81 for the Japonica reference), as well as synteny maps (19 for the Japonica reference) for 10 of the Oryza genomes are available in the Gramene website. Click here for a GW8 region comparison or a synteny map for the GW8 region between Os japonica and O. rufipogon in the Gramene Genome Browser.
New alignments and synteny maps with the new Oryza genomes will be made available here in future releases.
 
**Synteny maps** for *Oryza sativa Japonica* with:

 - *Zea mays* V5 
 - *Sorghum bicolor* (see [example](https://oryza-ensembl.gramene.org/Oryza_sativa/Location/Synteny?db=core;g=Os08g0531600;r=8:26476169-26526170;t=Os08t0531600-01)). Note the inverted order of genes in sorghum chromosome 7 relative to rice chromosome 8.

![Ensembl Synteny](images/Picture26.png)
![Synteny_table](images/Picture27.png)

## Baseline Gene Expression (EBI-Atlas) {#gene-expression}

Baseline gene expression data from 15 datasets for _O. sativa japonica_ was curated and processed by the EMBL-EBI Expression Atlas is available from the GrameneOryza Search, the Ensembl PanGenome gene pages, and the corresponding Plant Reactome panels. The Expression panel of the Search results was described above in detail. The same Expression Atlas view for the GW8 gene is available from the Gramene browser gene page and the Plant Reactome Expression panel (a link to the Plant Reactome is provided at the bottom of the Pathways panel of the Search results).

![GW8_expression_ensembl_browser](images/Picture23.png)

GW8 gene expression in the Gramene browser gene page


![GW8_expression_plant_reactome](images/Picture24.png)

GW8 gene expression in the Plant Reactome Expression panel


![GW8_expression_Atlas](images/Picture25.png)

GW8 gene expression in the Expression Atlas


## Genetic, Structural & Phenotypic Variation {#variation}

Gramene Oryza release 8 features genetic variation data mapped to the following reference assemblies:

* _O. sativa_ Japonica Nipponbare (IRGSP1):

  - 27 million SNPs determined in _O. sativa_ Japonica Nipponbare IRGSP1 with corresponding standard identifiers or rsIDs imported from the European Variation Archive (EVA). A complete list of the data sets that were assigned rsIDs is provided below and also in [GrameneOryza release notes for version 7.0](https://oryza.gramene.org/News?section=PanOryza%20Release%207). Corresponding genotypes and allele/genotype frequencies by study population are also available in the [Gramene database](https://ensembl.gramene.org/Oryza_sativa/).

  - 6.5 million SNPs determined in the USDA Rice Mini-Core Collection (URMC) of 190 rice accessions in Kumar et al (2021). rsIDs are provided for co-localized SNPs in this data set. 
     
  - 12 million SNPs determined in two collections at the Japanese NARO Genebank: 68 accessions of the World Rice Core Collection (NARO WRC) (Tanaka et al, 2020a) and 50 accessions of the Rice Core Collection of Japanese Landraces (JRC) (Tanaka et al, 2020b), data kindly provided by the RAP-DB resource. rsIDs are provided for co-localized SNPs in this data set. 

* [MAGIC16](https://doi.org/10.1038/s41597-020-0438-2) genomes:

  - Approximately 19 million SNPs called on 8 of the [MAGIC16](https://doi.org/10.1038/s41597-020-0438-2) genomes from the [3K rice genome project](https://doi.org/10.1186/2047-217x-3-7): Nipponbare, MH63, IR64, Azucena, ARC 10497, Zhenshan 97, Liu Xu, and N22. Data generated by KAUST scientists using the Genome Analysis Toolkit GATK4 and introduced in the GrameneOryza site releases 6 & 7. 



Large-scale rice studies with rsIDs assigned by the EVA:

1) The 3000 Rice Genome Project (2015), an international effort to sequence the genomes of 3,024 rice varieties from 89 countries providing 365,710 variant loci (SNPs and InDels).

2) Whole-genome sequencing of 104 elite rice cultivars (Duitama et al. 2015), described as "a comprehensive information resource for marker assisted selection providing 25,769,548 variant loci".

3) Chip-based analysis of 1,310 SNPs across 395 samples (Zhao et al. 2010), described as "revealing the impact of domestication and breeding on the rice genome".

4) Chip-based analysis of approximately 160k SNPs across 20 diversity rice accessions (OryzaSNP, McNally et al. 2009), described as "revealing relationships among landraces and modern varieties of rice".

5) The Oryza Map Alignment Project (OMAP 2007): approximately 1.6M variant loci detected by comparing BAC End Sequences from four rice varieties to Japonica. [dbSNP]
 
6) Adaptive loss-of-function in domesticated rice (BGI 2004): A collection of approximately 3M variant loci from the comparison of the Indica (93-11) and Japonica (Nipponbare) genomes. [dbSNP]


In addition, the following genetic markers were remapped to the IRGSP-1.0 assembly by industry collaborator KeyGene, and are associated with phenotypic traits:

- 20,483 Quantitative Trait Locus (QTL): 19,435 from Gramene's legacy QTLs database and 1,048 from the Q-Taro database

- 1,278 genetic markers (990 RFLPs and 288 SSRs) from Gramene's legacy markers database


Click here for an [image](https://oryza-ensembl.gramene.org/Oryza_sativa/Gene/Variation_Gene/Image?g=Os08g0531600;r=8:26501167-26506198;t=Os08t0531600-01) or a [table](https://oryza-ensembl.gramene.org/Oryza_sativa/Gene/Variation_Gene/Table?g=Os08g0531600;r=8:26501167-26506198;t=Os08t0531600-01) of genetic variation for the GW8 gene in the Gramene Ensembl browser. In addition, the inquisitive researcher will notice that **RM502** is a structural or copy number variant (Gramene marker) in the GW8 gene region, that is associated with seven distinct QTLs in the [archival Gramene QTL database](https://archive.gramene.org/db/markers/marker_view?marker_name=RM502&vocabulary=markers&search_box_name=marker_name&search_box_id=marker_search_for&action=marker_search&x=14&y=8). Those seven [Phenotypic (QTL) associations](https://oryza-ensembl.gramene.org/Oryza_sativa/Gene/Summary?g=Os08g0531600;r=8:26501167-26506198;t=Os08t0531600-01) correspond to five distinct phenotypes or traits: tiller number, root thickness, filled grain percentage, seed density, and gelatinization temperature. Make sure that the "Phenotype annotations" track that is under the Variation section of the “Configure this image” option of the Gnee Page is selected (with a check mark). The corresponding traits are also searchable from the homepage.

Additional genetic variation (SNPs, RFLP and SSR markers) is available for *O. sativa Japonica* and *Indica*, *O. glaberrima* and *O. glumaepatula* in the main Gramene website.


## Literature References {#references}


Chen Erwang, Xuehui Huang, Zhixi Tian, Rod A.Wing, and Bin Han. 2019. "The Genomics of Oryza Species Provides Insights into Rice Domestication and Heterosis." Annu. Rev. Plant Biol. 70:639–65. doi: [10.1146/annurev-arplant-050718-100320](https://doi.org/10.1146/annurev-arplant-050718-100320).

Hufford, Matthew B., Arun S. Seetharam, Margaret R. Woodhouse, Kapeel M. Chougule, Shujun Ou, Jianing Liu, William A. Ricci, et al. 2021. “De Novo Assembly, Annotation, and Comparative Analysis of 26 Diverse Maize Genomes.” Science. 373(6555):655-662. doi:[10.1126/science.abg5289](https://doi.org/10.1126/science.abg5289).

Jiao, Yinping, Paul Peluso, Jinghua Shi, Tiffany Liang, Michelle C. Stitzer, Bo Wang, Michael S. Campbell, et al. 2017. “Improved Maize Reference Genome with Single-Molecule Technologies.” Nature. 546 (7659): 524–27. doi: [10.1038/nature22971](https://doi.org/10.1038/nature22971).

Kumar A, Gupta C, Thomas J, Pereira A. 2021. "Genetic Dissection of Grain Yield Component Traits Under High Nighttime Temperature Stress in a Rice Diversity Panel." Front Plant Sci. 12:712167. doi: [10.3389/fpls.2021.712167](https://doi.org/10.3389/fpls.2021.712167).

Lu Z, Marand AP, Ricci WA, Ethridge CL, Zhang X, Schmitz RJ. 2019. "The prevalence, evolution and chromatin signatures of plant regulatory elements." Nature Plants. doi: [10.1038/s41477-019-0548-z](https://doi.org/10.1038/s41477-019-0548-z).

Tanaka N, Shenton M, Kawahara Y, et al. 2020. "Whole-genome sequencing of the NARO World Rice Core Collection (WRC) as the basis for diversity and association studies." Plant and Cell Physiology 61(5):922-932. doi: [10.1093/pcp/pcaa019](https://doi.org/10.1093/pcp/pcaa019).

Tanaka N. Shenton M, Kawahara Y, et al. 2020. "Investigation of the Genetic Diversity of a Rice Core Collection of Japanese Landraces using Whole-Genome Sequencing." Plant and Cell Physiology 61(12):2087-2096. doi: [10.1093/pcp/pcaa125](https://doi.org/10.1093/pcp/pcaa125).

Vilella AJ, Severin J, Ureta-Vidal A, Heng L, Durbin R, Birney E. EnsemblCompara GeneTrees: Complete, duplication-aware phylogenetic trees in vertebrates. 2009. Genome Res. 19(2):327-35. doi: [10.1101/gr.073585.107](https://doi.org/10.1101/gr.073585.107).

Wang S,Wu K, Yuan Q, Liu X, Liu Z, et al. 2012. "Control of grain size, shape and quality by OsSPL16 in rice." Nat. Genet. 44:950–54. doi:[10.1038/ng.2327](https://doi.org/10.1038/ng.2327).

Zhou, Yong, Dmytro Chebotarov, Dave Kudrna, Victor Llaca, Seunghee Lee, Shanmugam Rajasekar, Nahed Mohammed, et al. 2020. “A Platinum Standard Pan-Genome Resource That Represents the Population Structure of Asian Rice.” Sci. Data. 7 (1): 113. doi: [10.1038/s41597-020-0438-2](https://doi.org/10.1038/s41597-020-0438-2)


**_Zea mays_ PanGenome User Guide**

Author: Marcela Karey Tello-Ruiz, PhD

This user guide refers to the contents of the First Public Release (August 2021) of the Maize PanGenome. Currently, the PanGenome hosts 35 genomes including 25 NAM maize founder genomes (Hufford _et al_, 2021; Gage _et al_, 2020; Yu _et al_, 2008; McMullen _et al_, 2009), 3 versions of the B73 _Zea mays_ reference* (Hufford _et al_, 2021; Jiao _et al_, 2017; Schnable _et al_, 2009), and 7 outgroups (_Arabidopsis thaliana_, _Oryza sativa _Japonica, _Sorghum bicolor, Vitis vinifera ssp. vinifera PN40024, Selaginella moellendorffii_, _Chlamydomonas reinhardtii_, and _Drosophila melanogaster_).

_Note that most data types are only available for B73 version 4_.

---

Let’s begin!

Go to [http://maize-pangenome.gramene.org/](http://maize-pangenome.gramene.org/)

Locate the search icon at the top right corner of the page. Click on this icon or hit the slash character (/) on your keyboard to convert the header to a search bar. Click on the “X” or type the esc key to revert to the navigation bar.

**PanGenome Search Interface**

**Querying a Gene**

Search Results Summary

The results of a gene search are organized in five data categories:



* Location - Genomic context
    * Ensembl Browser (Gramene Maize PanGenome)
    * Phytomine
* Expression - Baseline gene expression from [EBI-Expression Atlas](https://www.ebi.ac.uk/gxa)
* Homology - Customizable Ensembl Compara gene family trees with displays:
    * Alignment Overview (full-length gene)
    * Multiple-Sequence Alignment (zoom into the amino acid level)
    * Neighborhood Conservation View (zoom out +/- 10 flanking genes)
* Pathways - Association to pathways in [Gramene’s Plant Reactome](https://plantreactome.gramene.org)
* Xrefs - Cross-references to other databases

Let’s start by typing “lox” in the search box and observe the auto-completion suggestions that pop-up, as well as the various data categories in which the potential results are organized.



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")


The example below shows the default view of the [results from searching for lox9](http://maize-pangenome.gramene.org/?filters={%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:3,%22children%22:[{%22fq_field%22:%22_terms%22,%22fq_value%22:%22lox9%22,%22name%22:%22lox9%22,%22category%22:%22Gene%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:true}],%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20}&genomes=) (lipoxygenase 9). Depending on how the gene name, locus name, gene synonyms and gene description were assigned to a gene model, you may get one or multiple hits for this query. 

More complex queries can be constructed using junctions such as AND/OR to combine genes, a list of genes in a pathway, sharing an interpro domain or a Gene Ontology function. In addition query terms may be deleted, copied, moved or negated.



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")


To reproduce the screen capture shown below, select the “lox9” gene from the suggested results. Please note that searching for lox9 also yields results for LOX9 (capitalized letters), which are not necessarily identical. LOX9 has a number 2 next to it, which indicates two genes associated with it; meanwhile lox9 has a number 1 next to it, which indicates that there is a single gene associated with it. 

To limit the results to maize genomes, click on the spider gear icon and deselect the non-maize outgroups (e.g., _Arabidopsis_, _Oryza_, _Sorghum_, _Vitis_, _Selaginella_, _Chlamydomonas_, and _Drosophila_). This filtering step should render one or more of the following results:

GRMZM2G017616 (B73 _Zea mays _v3)

Zm00001d027893 (B73 _Zea mays_ v4) 

Zm00001eb005920 (B73 _Zea mays_ v5)



<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")


The above screen capture corresponds to the one gene result that shows up for “lox9” (small letters): Zm00001eb005920. Note that this is reflected in the karyotype view on top, where every chromosome of a genome is represented as a colorful box and every hit of a query is represented as a tick mark overlaid on its corresponding karyotype. Because it is unique, it defaults to the Homology view (of the five results categories). Maize v5 genes are likely to display their v4 (Zm00001d027893) and v3 (GRMZM2G017616) counterparts as synonyms, and often the same will appear as the gene’s closest homologs in the gene family tree. For the following exercises, I suggest that you focus on the v4 gene model as these currently have the most types of data (e.g., gene expression, pathways) associated with them. 

To focus on the v4 gene in the family tree that shows up for Zm00001eb005920 (v5 gene), click on the v4 gene name/id to copy the name of the gene from the pop-up panel, and redo your search with the v4 gene id. _Note: You could also select the “Focus on this gene” option and bring the v4 gene to the top of the tree but if you do this, the focus of the rest of the results will still be the v5 gene.  _



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")


**Homology Views**

Click on the “Display Mode” drop-down menu to select one of three displays for the Homology view: Alignment overview, Multiple Sequence Alignment, and Neighborhood conservation.



<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")




1. The** Alignment Overview** allows you to view the entire length of the protein. Proteins are color-coded by InterPro domain. Click anywhere in the colored protein domain to reveal its name and some statistics. 

    

<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.png "image_tooltip")



    You may expand collapsed taxonomic clades, which are symbolized by triangles along the branches of the tree, by clicking on the black (speciation) or red (duplication) nodes and selecting the option “Expand”. Already expanded clades can be contracted by selecting the option “Collapse” that appears upon clicking a node.




<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")



    Please note that resizing the gray slider that surrounds the entire protein allows you to navigate along it. Also, at the bottom of the panel notice the number of Homologs, Orthologs, and Paralogs. By clicking on any of them, the corresponding gene list will be displayed. See for example, the list of 13 paralogs in the figure below.


    

<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image8.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image8.png "image_tooltip")




2. The **Multiple-Sequence Alignment** allows you to zoom into the amino acid level. Drag the slider along the length of the protein to change the area of detail. This view allows you to observe the degree of amino acid sequence conservation and identify areas where lack of conservation could indicate biologically significant differences such as alternatively spliced forms or mere annotation artifacts. See for example how the v4 gene differs in the middle of the C-terminal lipoxygenase domain (orange box).



<p id="gdcalert9" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image9.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert10">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image9.png "image_tooltip")




3. Neighborhood Conservation View

    This view presents the target gene in the middle with a red line across the best ortholog in each species in the tree plus 10 flanking genes upstream and downstream color-coded by gene family. This allows you to identify structural variants and Presence/Absence variants in the region in question.


    

<p id="gdcalert10" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image10.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert11">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image10.png "image_tooltip")



    **Location**


    Switch to the “Location” tab to observe the gene structure and alternative transcripts for your target gene. Exons are shown as red boxes, introns as lines, and UTRs as orange boxes. Use the sizing tool to modify the region under observation. The search filters allow users to list all genes in the chromosome or all the genes in the region specified in the field. Links to the [Maize PanGenome Browser](http://maize-pangenome-ensembl.gramene.org/zea_maysb73v4/Gene/Summary?g=Zm00001d027893) and [PhytoMine](https://phytozome.jgi.doe.gov/phytomine/keywordSearchResults.do?searchTerm=Zm00001d027893&searchSubmit=Search) are provided at the bottom of the tab.


    

<p id="gdcalert11" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image11.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert12">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image11.png "image_tooltip")



    **Expression**


    This view depicts baseline gene expression data for a whole plant (top anatogram on the left of the results box) and for the plant’s reproductive organs (bottom anatogram). Experiments are organized by study on the left side, and by tissue or developmental stage on the top of the graph. 


    Unique data points are colored in blue, with intensity increasing in proportion to the level of expression. What this means is that higher expression data points are shown in darker blue. 


    When you hover the cursor over a data point, the data point is highlighted in yellow, and a more detailed data summary pops up. The corresponding tissue is also colored in pink in the anatograms.


    If instead, you hover over a tissue on the anatogram on the left, the name of the tissue will pop up, and the points corresponding to expression data from that tissue will light up. 


    

<p id="gdcalert12" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image12.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert13">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image12.png "image_tooltip")



    

<p id="gdcalert13" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image13.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert14">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image13.png "image_tooltip")



**	Pathways**

From the literature, we know that lox9 is part of the jasmonic acid (JA) biosynthesis pathway. 


    Accordingly, the Pathways panel shows that this gene product catalyzes a reaction in two pathways, JA biosynthesis, and 13-LOX/13-HPL.


    When you hover the cursor over the reaction in the hierarchy on the left side, the diagram on the right will show the reaction in the context of the corresponding pathway. 


    Under “Search Filters”, you have the option of getting a list of all genes in a reaction or an entire pathway. You may also navigate to the Gene and corresponding Reaction pages in the Plant Reactome site, where you will be able to perform more complex analyses of omics data, including pathway-based comparisons across species.


    An example of such an analysis is illustrated in a short video in the Gramene series where transcriptomics data is overlaid onto orthology-based projected pathways to compare expression between mutant and wild-type tissues at distinct developmental stages.


    

<p id="gdcalert14" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image14.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert15">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image14.png "image_tooltip")



    **Cross-References**


    In the Xref tab, you will find references to your gene of interest in other databases, including UniProt, UniParc, and UniGene.


    

<p id="gdcalert15" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image15.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert16">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image15.png "image_tooltip")


**Gene & Transcript pages**

A [gene page](http://maize-pangenome-ensembl.gramene.org/Zea_maysb73v4/Gene/Summary?db=core;g=Zm00001d027893;r=1:16948608-16955122;t=Zm00001d027893_T001) and [transcript page](http://maize-pangenome-ensembl.gramene.org/Zea_maysb73v4/Transcript/Summary?db=core;g=Zm00001d027893;r=1:16948608-16955122;t=Zm00001d027893_T001) (tabs) in the Maize Pan-Genome browser.



<p id="gdcalert16" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image16.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert17">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image16.png "image_tooltip")




<p id="gdcalert17" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image17.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert18">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image17.png "image_tooltip")


**Comparative Genomics**

The following comparative genomics data for B73 v4 are available in the Maize Pan-Genome Browser:



* Gene trees (Ensembl Compara pipeline) - [Example](http://maize-pangenome-ensembl.gramene.org/Zea_maysb73v4/Gene/Compara_Tree?db=core;g=Zm00001d027893;r=1:16948608-16955122;t=Zm00001d027893_T001)



<p id="gdcalert18" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image18.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert19">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image18.png "image_tooltip")



    **Regulation**


#### **Epigenomics & RNA-Seq Gene Expression (MaizeCODE)**

For the B73 genome there are 188 data tracks available under Regulation. You can get a complete list of all 188 Regulation tracks by clicking on the spider gear symbol for “Configure this page” (left side menu) or “Configure this image” (Location panel), see the inset in the image below. Click on the square that precedes the name of the track to turn it on or off and configure it with the available options being: Wiggle plot, Compact, and Manhattan plot.



<p id="gdcalert19" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image19.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert20">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image19.png "image_tooltip")


These correspond to the following [MaizeCODE data sets](http://www.maizecode.org/data/b73.html):



1. Four genome-wide epigenetic marks (MARK: H3K27ac, H3K4me, H3K4me3, and Input) for five B73 tissues (TISSUE: ears, endo, pollen, root, and cn?) in duplicate (2 repetitions or REP: rep1 and rep2). Corresponding tracks are named as follows: TISSUE_REP (B73 MARK). For example, look for root_rep1 (B73 H3K27ac) in the [image below](http://maize-pangenome-ensembl.gramene.org/Zea_maysb73v4/Location/View?db=core;g=Zm00001d027893;r=1:16924966-17020967;t=Zm00001d027893_T001).



<p id="gdcalert20" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image20.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert21">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image20.png "image_tooltip")




2. RNA annotation and mapping of promoters for analysis of gene expression (RAMPAGE; Batt & Gingeras, 2013) and RNAseq expression data (ASSAYS) is available for four SPECIES (B73, NC350, Ti11, and W22). The corresponding tracks have names in the form of TISSUE_REP STRAND (SPECIES ASSAY), where STRAND is forward or reverse. Find, for example, root_rep1 forward (NC350 RNAseq) in the [image below](http://maize-pangenome-ensembl.gramene.org/Zea_maysb73v4/Location/View?r=1:16947867-16955868;site=ensemblthis;time=1627334587390.39;db=core). 



<p id="gdcalert21" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image21.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert22">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image21.png "image_tooltip")



#### 
    **Baseline Gene Expression (Atlas)**

Baseline gene expression data from 25 B73 datasets curated and processed by the [EMBL-EBI Expression Atlas](https://www.ebi.ac.uk/gxa/) are also available from the Maize PanGenome Search, the Ensembl PanGenome gene pages, and the corresponding Plant Reactome panels. The Expression panel of the Search results was described above in detail. The same Expression view for the lox9 gene is available from the [PanGenome browser gene page](http://maize-pangenome-ensembl.gramene.org/Zea_maysb73v4/Gene/ExpressionAtlas?db=core;g=Zm00001d027893;r=1:16947867-16955868;t=Zm00001d027893_T004) and the [Plant Reactome Expression panel](https://plantreactome.gramene.org/PathwayBrowser/#/R-ZMA-1119332&DTAB=EX) (find a link to the Plant Reactome at the bottom of the Pathways panel of the Search results).



<p id="gdcalert22" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image22.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert23">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image22.png "image_tooltip")


lox9 gene expression in the [PanGenome browser gene page](http://maize-pangenome-ensembl.gramene.org/Zea_maysb73v4/Gene/ExpressionAtlas?db=core;g=Zm00001d027893;r=1:16947867-16955868;t=Zm00001d027893_T004)



<p id="gdcalert23" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image23.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert24">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image23.png "image_tooltip")


lox9 gene expression in the [Plant Reactome Expression panel](https://plantreactome.gramene.org/PathwayBrowser/#/R-ZMA-1119332&DTAB=EX)


### 
    **Genetic, Structural & Phenotypic Variation**

Coming soon...


    **Literature References**


    Gage, Joseph L., Brandon Monier, Anju Giri, and Edward S. Buckler. 2020. “Ten Years of the Maize Nested Association Mapping Population: Impact, Limitations, and Future Directions.” _The Plant Cell_ 32 (7): 2083–93.


    Hufford, Matthew B., Arun S. Seetharam, Margaret R. Woodhouse, Kapeel M. Chougule, Shujun Ou, Jianing Liu, William A. Ricci, et al. 2021. “De Novo Assembly, Annotation, and Comparative Analysis of 26 Diverse Maize Genomes.” _bioRxiv_. https://doi.org/[10.1101/2021.01.14.426684.](http://dx.doi.org/10.1101/2021.01.14.426684)


    Jiao, Yinping, Paul Peluso, Jinghua Shi, Tiffany Liang, Michelle C. Stitzer, Bo Wang, Michael S. Campbell, et al. 2017. “Improved Maize Reference Genome with Single-Molecule Technologies.” _Nature_ 546 (7659): 524–27.


    McMullen, Michael D., Stephen Kresovich, Hector Sanchez Villeda, Peter Bradbury, Huihui Li, Qi Sun, Sherry Flint-Garcia, et al. 2009. “Genetic Properties of the Maize Nested Association Mapping Population.” _Science_ 325 (5941): 737–40.


    Schnable, Patrick S., Doreen Ware, Robert S. Fulton, Joshua C. Stein, Fusheng Wei, Shiran Pasternak, Chengzhi Liang, et al. 2009. “The B73 Maize Genome: Complexity, Diversity, and Dynamics.” _Science_ 326 (5956): 1112–15.


    Yu, Jianming, James B. Holland, Michael D. McMullen, and Edward S. Buckler. 2008. “Genetic Design and Statistical Power of Nested Association Mapping in Maize.” _Genetics_ 178 (1): 539–51.

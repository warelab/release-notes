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
- [Databases](#databases)
- [Statistics](#statistics)

# This info needs to be updated

## Overall Highlights {#overall-highlights}
- Five sorghum reference genomes: *Sorghum bicolor* (L.) Moench subsp. *bicolor* BTx623
  (Paterson et al, 2009; McCormick et al, 2017), RTx430 (Deschamps et al, 2018), RTx436
  and Tx2783 (Wang et al, 2021), and Rio (Cooper et al, 2019).
- Six plant outgroup species (Japonica rice, B73 maize, Arabidopsis thaliana, grapevine,
  a vascular plant, and a single-celled green algae) and Drosophila melanogaster were
  used to build 21,429 protein-coding gene family trees.
- Our comparative genomics collection includes a total of five pairwise DNA alignments
  for each of the sorghum genomes aligned to Japonica rice.
- We also have genetic, structural and phenotypic variation, gene expression and
  orthology-based pathway projections for the reference genome S. bicolor BTx623.

## Databases {#databases}
### Comparative Genomics

[**Gene Trees.**](https://ensembl.sorghumbase.org/prot_tree_stats.html) A total of
21,429 protein-coding gene family trees were constructed using the peptide encoded by
the canonical transcript (i.e., a representative transcript for a given gene) for each
of 317,845 individual genes (350,099 input proteins) from 11 plant genomes.

[**Whole-Genome Alignments**](https://ensembl.sorghumbase.org/compara_analyses.html).
There are pairwise genomic alignments for each one of the sorghum genomes against
Japonica rice:
- [Sorghum bicolor BTx623](https://ensembl.sorghumbase.org/sorghum_bicolor/Location/Compara_Alignments/Image?align=23;db=core;r=4:41625307-41663480)
- [Sorghum RTx430](https://ensembl.sorghumbase.org/sorghum_tx430nano/Location/Compara_Alignments/Image?align=30;db=core;r=Scaffold_2:9298671-9344179)
- [Sorghum RTx436](https://ensembl.sorghumbase.org/sorghum_tx436pac/Location/Compara_Alignments/Image?align=29;db=core;r=4:40945993-40992222)
- [Sorghum Tx2783](https://ensembl.sorghumbase.org/sorghum_tx2783pac/Location/Compara_Alignments/Image?align=28;db=core;r=4:38544936-38590672)
- [Sorghum bicolor Rio](https://ensembl.sorghumbase.org/sorghum_rio/Location/Compara_Alignments/Image?align=31;db=core;r=4:37447216-37493025)

### Variation

Genetic variation data sets for over 6.7 million sorghum single nucleotide
polymorphisms (SNPs) (Morris et al, 2013; Mace et al, 2013) and 1.5 million chemically
induced by ethyl methanesulfonate (EMS) point mutations (Xin et al, 2008); 27,884
structural variants (Zheng et al, 2011) from the [Database of Genomic Variation Archive](https://www.ebi.ac.uk/dgva/)
(DGVa); and nearly 6,000 QTLs and GWAS from the [Sorghum QTL Atlas](https://aussorgm.org.au/).

### Expression

Gene expression data for the S. bicolor BTx623 genome reference was curated and
processed through the [EMBL-EBI Expression Atlas](https://www.ebi.ac.uk/gxa/plant/experiments).
The set consists of seven studies with baseline expression in BTx623 (Davidson et al,
2012; Makita et al, 2014; Wang et al, 2018; Emms et al, 2016; Turco et al, 2017; and
two unpublished studies with SRA projects SRP062564 and SRP029353). At the Expression
Atlas site, baseline expression is also available for a bioenergy sorghum genotype
R.07020 (Kebrom et al, 2017), and differential expression for three studies
(Varoquaux et al, 2019; Dugas et al 2011; Gelli et al, 2014), including one
(Dugas et al, 2011) in the BTx623 reference.

For the baseline studies in SorghumBase, sampling was done in a single site
(e.g., stem internode), a discrete cell type (e.g., bundle sheath, leaf mesophyll),
organism parts (including seed, spikelet, stem, leaf, flag leaf, inflorescence, pistil,
embryo, endosperm, anther, pericarp, pollen, root, shoot, floral meristem, flower,
vegetative meristem, vascular/ non-vascular system) or the whole organism, at one or
multiple developmental stages. For example, Wang and collaborators (Wang et al. 2018)
examined 11 matched tissues of maize B73 and sorghum BTx623 at different developmental
stages for gene expression profiling totalling 165 experimental assays.

To be included in Expression Atlas each experiment must meet all the following criteria:
- Experiment measures gene or protein expression.
- Raw data are available.
- All samples within the dataset belong to a single species.
- Samples come from non-bacterial species.
- The species genome is available through [Ensembl](http://www.ensembl.org/index.html).
- Annotations for microarray probes are available.
- Sufficient sample annotation is provided.

Additional “softer” guidelines to determine whether or not an experiment is eligible
for inclusion into Expression Atlas:
- (differential): The experiment should have at least 2 experimental groups, with 3 biological replicates each and also have a clear control/reference group
- (baseline): The experiment design does not involve any perturbations and the dataset should have at least 3 experimental groups with 3 biological replicates each
- The experiment addresses a relevant biological question (is not technical or proof of principle study)
- Experimental metadata are of high quality and confidence
- The experimental design is not too complex (e.g. not too many factors) and allows for straightforward one-to-one comparisons

If an experiment is judged to be of particular interest and its inclusion in
Expression Atlas is highly valuable for the community, the Expression Atlas
team may decide to include it even if it fails some of the above guidelines.
Please do not hesitate to [contact the Expression Atlas team](https://www.ebi.ac.uk/support/gxa)
if you have any questions about how experiments for Expression Atlas are selected or you wish to recommend a dataset(s) that you feel should be ingested and displayed in SorghumBase.

### Pathways

269 orthology-based sorghum pathways associated with 1,248 S. bicolor BTx623 genes.
These were projected from curated Japonica rice pathways and are linked to [Gramene’s Plant Reactome](http://gramene.org/).

## Statistics {#statistics}
| Species   | Classification | Note | Assembly | Literature reference | Accession | Variation | Expression | Whole Genome Alignments | Phylogenetic Trees | Pathways |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| *Arabidopsis thaliana* | *Eudicotyledons* | Dicot model plant | TAIR10 | | GCA_000001735.1 | - | - | - | Y | Y |
| *Vitis vinifera* | *Eudicotyledons* | Dicot reference | IGGP_12x | | GCA_000003745.2 | - | - | - | Y | Y |
| *Zea mays* | *Liliopsida* | Monocot reference | AGPv4 | | GCA_000005005.6 | - | - | - | Y | Y |
| *Oryza sativa Japonica* | *Liliopsida* | Monocot reference | AGPv4 | | GCA_001433935.1 | - | - | Y | Y | Y |
| *Sorghum bicolor BTx623* | *Liliopsida* | Sorghum reference genome | Sorghum_bicolor_NCBIv3 | Paterson et al (2009); McCormick et al (2017) | GCA_000003195.3 | 8 M SNPs (Morris et al, 2013; Mace et al, 2013) and EMS-induced mutations (Xin et al, 2008); ~28K structural variants (Zheng et al, 2011) from the DGVa; and ~6K QTLs and GWAS from the Sorghum QTL Atlas. | Baseline expression for seven studies (Davidson et al, 2012; Makita et al, 2014; Wang et al, 2018; Emms et al, 2016; Turco at al, 2017; and two unpublished studies with SRA projects SRP062564 and SRP029353) | Y | Y | 269 orthology-based pathways associated with 1,248 genes |
| *Sorghum bicolor RTx430* | *Liliopsida* | | Corteva_Sorghum_ONT_TX430_1.0 | Deschamps et at (2017) | - | - | - | Y | Y | |
| *Sorghum bicolor RTx436* | *Liliopsida* | Recombinant male parental line | Sorghum_bicolor-Tx436-Reference-CSHL-USDA-1.0 | Wang et at (bioRxiv) | - | - | - | Y | Y | |
| *Sorghum bicolor Tx2783* | *Liliopsida* | Sugarcane aphid (SCA) resistant | Sorghum_bicolor-Tx2783-Reference-CSHL-USDA-1.0 | Wang et at (bioRxiv) | - | - | - | Y | Y | |
| *Sorghum bicolor Rio* | *Liliopsida* | Sweet sorghum | JGI-v2.0 | Cooper et at (2019) | SbRio | - | - | Y | Y | |
| *Selaginella moellendorffii* | *Lycopodiophyta* | Vascular model plant | v1.0 | | GCA_000143415.1 | - | - | - | Y | Y |
| *Chlamydomonas reinhardtii* | *Chlorophyta* | Single-cell green alga | Chlamydomonas_reinhardtii_v5.5 | | GCA_000002595.3 | - | - | - | Y | Y |

## References {#references}
Aken, Bronwen L., Sarah Ayling, Daniel Barrell, Laura Clarke, Valery Curwen, Susan Fairley, Julio Fernandez Banet, et al. 2016.
"The Ensembl Gene Annotation System."
*Database: The Journal of Biological Databases and Curation*.
PMID: 27337980. https://doi.org/10.1093/database/baw093.

Brenton, Zachary W., Elizabeth A. Cooper, Mathew T. Myers, Richard E. Boyles, Nadia Shakoor, Kelsey J. Zielinski, Bradley L. Rauh, William C. Bridges, Geoffrey P. Morris, and Stephen Kresovich. 2016.
"A Genomic Resource for the Development, Improvement, and Exploitation of Sorghum for Bioenergy."
*Genetics* 204 (1): 21–33.
PMID: 27356613. https://doi.org/10.1534/genetics.115.183947.

Casa, Alexandra M., Gael Pressoir, Patrick J. Brown, Sharon E. Mitchell, William L. Rooney, Mitchell R. Tuinstra, Cleve D. Franks, and Stephen Kresovich. 2008.
"Community Resources and Strategies for Association Mapping in Sorghum."
*Crop Science* 48 (1): 30–40.
https://doi.org/10.2135/cropsci2007.02.0080.

Davidson, Rebecca M., Malali Gowda, Gaurav Moghe, Haining Lin, Brieanne Vaillancourt, Shin-Han Shiu, Ning Jiang, and C. Robin Buell. 2012.
"Comparative Transcriptomics of Three Poaceae Species Reveals Patterns of Gene Expression Evolution."
*The Plant Journal: For Cell and Molecular Biology* 71 (3): 492–502.
PMID: 22443345. https://doi.org/10.1111/j.1365-313X.2012.05005.x.

Emms, David M., Sarah Covshoff, Julian M. Hibberd, and Steven Kelly. 2016.
"Independent and Parallel Evolution of New Genes by Gene Duplication in Two Origins of C4 Photosynthesis Provides New Insight into the Mechanism of Phloem Loading in C4 Species."
*Molecular Biology and Evolution* 33 (7): 1796–1806.
PMID: 27016024. https://doi.org/10.1093/molbev/msw057.

Gladman, N. et al. "Sorghum root epigenetic landscape during limiting phosphorus conditions." *Manuscript in preparation*.

Goodstein, David M., Shengqiang Shu, Russell Howson, Rochak Neupane, Richard D. Hayes, Joni Fazo, Therese Mitros, et al. 2012.
"Phytozome: A Comparative Platform for Green Plant Genomics."
*Nucleic Acids Research* 40 (Database issue): D1178–86.
PMID: 22110026. https://doi.org/10.1093/nar/gkr944.

Jiao, Yinping, John J. Burke, Ratan Chopra, Gloria Burow, Junping Chen, Bo Wang, Chad Hayes, Yves Emendack, Doreen Ware, and Zhanguo Xin. 2016.
"A Sorghum Mutant Resource as an Efficient Platform for Gene Discovery in Grasses."
*The Plant Cell*.
PMID: 27354556. https://doi.org/10.1105/tpc.16.00373.

McCormick, Ryan F., Sandra K. Truong, Avinash Sreedasyam, Jerry Jenkins, Shengqiang Shu, David Sims, Megan Kennedy, et al. 2018.
"The Sorghum Bicolor Reference Genome: Improved Assembly, Gene Annotations, a Transcriptome Atlas, and Signatures of Genome Organization."
*The Plant Journal: For Cell and Molecular Biology* 93 (2): 338–54.
PMID: 29161754. https://doi.org/10.1111/tpj.13781.

Mace, Emma S., Shuaishuai Tai, Edward K. Gilding, Yanhong Li, Peter J. Prentis, Lianle Bian, Bradley C. Campbell, et al. 2013.
"Whole-Genome Sequencing Reveals Untapped Genetic Potential in Africa’s Indigenous Cereal Crop Sorghum."
*Nature Communications* 4: 2320.
PMID: 23982223. http://doi.org/10.1038/ncomms3320.

Makita, Yuko, Setsuko Shimada, Mika Kawashima, Tomoko Kondou-Kuriyama, Tetsuro Toyoda, and Minami Matsui. 2015.
"MOROKOSHI: Transcriptome Database in Sorghum Bicolor."
*Plant & Cell Physiology* 56 (1): e6.
PMID: 25505007. https://doi.org/10.1093/pcp/pcu187.

Morris, Geoffrey P., Punna Ramu, Santosh P. Deshpande, C. Thomas Hash, Trushar Shah, Hari D. Upadhyaya, Oscar Riera-Lizarazu, et al. 2013.
"Population Genomic and Genome-Wide Association Studies of Agroclimatic Traits in Sorghum."
*Proceedings of the National Academy of Sciences of the United States of America* 110 (2): 453–58.
PMID: 23267105. https://doi.org/10.1073/pnas.1215985110.

Olson, Andrew, Robert R. Klein, Diana V. Dugas, Zhenyuan Lu, Michael Regulski, Patricia E. Klein, and Doreen Ware. 2014.
"Expanding and Vetting Sorghum Bicolor Gene Annotations through Transcriptome and Methylome Sequencing."
*The Plant Genome* 7 (2): plantgenome2013.08.0025. https://doi.org/10.3835/plantgenome2013.08.0025.

Paterson, A. H., J. E. Bowers, R. Bruggmann, I. Dubchak, J. Grimwood, H. Gundlach, G. Haberer, et al. 2009.
"The Sorghum Bicolor Genome and the Diversification of Grasses."
*Nature* 457 (7229): 551–56.
PMID: 19189423. https://doi.org/10.1038/nature07723.

Turco, Gina M., Kaisa Kajala, Govindarajan Kunde-Ramamoorthy, Chew-Yee Ngan, Andrew Olson, Shweta Deshphande, Denis Tolkunov, et al. 2017.
"DNA Methylation and Gene Expression Regulation Associated with Vascularization in Sorghum Bicolor."
*The New Phytologist* 214 (3): 1213–29.
PMID: 28186631. https://doi.org/10.1111/nph.14448.

Xin, Zhanguo, Ming Li Wang, Noelle A. Barkley, Gloria Burow, Cleve Franks, Gary Pederson, and John Burke. 2008.
"Applying Genotyping (TILLING) and Phenotyping Analyses to Elucidate Gene Function in a Chemically Induced Sorghum Mutant Population."
*BMC Plant Biology*.
PMID: 18854043. https://doi.org/10.1186/1471-2229-8-103.

Wang, Bo, Michael Regulski, Elizabeth Tseng, Andrew Olson, Sara Goodwin, W. Richard McCombie, and Doreen Ware. 2018.
"A Comparative Transcriptional Landscape of Maize and Sorghum Obtained by Single-Molecule Sequencing."
*Genome Research* 28 (6): 921–32.
PMID: 29712755 https://doi.org/10.1101/gr.227462.117.

Zheng, Lei-Ying, Xiao-Sen Guo, Bing He, Lian-Jun Sun, Yao Peng, Shan-Shan Dong, Teng-Fei Liu, et al. 2011.
"Genome-Wide Patterns of Genetic Variation in Sweet and Grain Sorghum (Sorghum Bicolor)."
*Genome Biology* 12 (11): R114.
PMID: 22104744. http://dx.doi.org/10.1186/gb-2011-12-11-r114.


### Phenotypic Variation {#phenos}

#### Quantitative Trait Locus (QTLs) {#qtls}
 
Data corresponding to 5,843 QTL features for 148 sorghum traits were imported from [OZ Sorghum QTL Atlas](https://aussorgm.org.au/sorghum-qtl-atlas/), and 7,123 rice QTLs from [Gramene](https://www.gramene.org/). All QTLs are searchable, for example: [sorghum grain mold](https://sorghumbase.org/genes?filters=%7B%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:3,%22children%22:%5B%7B%22fq_field%22:%22QTL_TO__ancestors%22,%22fq_value%22:%2220008%22,%22name%22:%22sorghum%20grain%20mold%22,%22category%22:%22QTLs%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:true%7D%5D,%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20%7D&genomes=).

Check another [example region](https://ensembl.sorghumbase.org/Sorghum_bicolor/Location/View?db=core;g=SORBI_3006G095600;r=7:61190510-61277060;sv=nsv856002;svf=54084;t=OQU81659;vdb=variation) with QTLs associated with multiple traits including lignin content, tiller height, leaf clorophyl content, fresh biomass, seed length, flag leaf height, greenbug resistance (not all may be shown - limit is five stacked traits - when track is collapsed).

You may need to turn on the QTLs track and select how you would like the data displayed on your browser. For the figure shown below, I selected "Collapsed" style, which limits the dispaly to only 5 QTLs in the image. Click on a track to disclose more information about that data point (for example, QTL name, location, associated phenotype and data source). In the example below, if you click on a phenotype/trait, such as "Lignin content", you will be taken to a page listing all the genomic locations of QTL features associated with Lignin content. See an [example of such list for Lignin content](https://ensembl.sorghumbase.org/Sorghum_bicolor/Phenotype/Locations?ph=97).

![Configure QTLs track](qtls_configure.png)

Hint: For additional regions with QTL data in sorghum assembly v3, use the [physical or genetic (cM) coordinates](http://aussorgm.org.au/dev/wp-content/uploads/2018/08/Consensus-Map_cM-and-bp-coordinates.xlsx) kindly provided by the Sorghum QTL Atlas team.

![QTL tracks](images/qtl_tracks.png)

#### GWAS hits

The most significant trait associations determined in the GWAS meta-analysis of 234 phenotypes evaluated on SAP accessions in 25 studies, as performed by [Ravi Mural et al (2021)](https://www.sorghumbase.org/post/inadvertent-introgression-pleiotropy-and-the-sorghum-genome), are displayed on the karyotype ideogram. See for example, [chromosome 6](https://ensembl.sorghumbase.org/Sorghum_bicolor/Location/Chromosome?r=6:57678033-61277060). Use the configuration icon to turn on/off the various tracks (i.e., GWAS, QTLs, genes, etc.) on the display.

![karyotype](images/karyotype_chr6.png)

Significant associations for a given SNP estimated by two different methods (MLM & MashR) are shown, see for example that [rs872512714 is associated with various lipid and protein content related traits](https://ensembl.sorghumbase.org/Sorghum_bicolor/Variation/Phenotype?db=core;r=2:57664706-57664706;source=EVA;v=rs872512714;vdb=variation;vf=32471764)(MLM, P < 1.0e-6).

![GWAS hits](images/rsid_phenos.png)

By clicking on a trait name, you will see a list of all loci that had been found associated with that trait (see "Associated Loci" on the left bar menu), for example: [Protein](https://ensembl.sorghumbase.org/Sorghum_bicolor/Phenotype/Locations?db=core;name=Protein;ph=319;r=2:57664706-57664706;v=rs872512714;vdb=variation;vf=32471764) or related conditions defined by a Trait Ontology (TO) term, such as [TO:0000598 - protein content](https://ensembl.sorghumbase.org/Sorghum_bicolor/Phenotype/RelatedConditions?r=2%3A57664706-57664706&db=core&vf=32471764&ph=319&vdb=variation&v=rs872512714&oa=TO%3A0000598) (click on "Related conditions" on the left bar menu, and select the condition from the drop-down menu).


![loci associated with protein content](images/protein_gwas.png)




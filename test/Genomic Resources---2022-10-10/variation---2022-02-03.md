## Genetic Variation {#variation}

Variation in SorghumBase is available for short variants (genetic variation, which in turn may be naturally occurring or chemically induced).


### Genetic Variation

Genetic variation data sets are available for the reference genome assembly BTx623 v3 as over 59 million sorghum variants including more than 46 million naturally ocurring Single Nucleotide Polymorphisms (SNPs), and almost 13 million chemically-induced variants (i.e., ethyl methanesulfonate (EMS)-induced mutations). In addition, there are ~32.5 million SNPs called in Tx2783, as described below.

### Naturally occurring genetic variation - SNPs

Currently in SorghumBase, there are three SNPs data sets, two on sorghum BTx623 and one on Tx2783.

#### BTx623

- The Lozano SNP dataset [(Lozano et al, 2021)](https://www.sorghumbase.org/paper/comparative-evolutionary-genetics-of-deleterious-load-in-sorghum-and-maize) consists of about 13 million SNPs in 499 sorghum accessions, including lines from the TERRA-MEPP and TERRA-REF population panels, and the samples previously reported by Emma Mace and collaborators [(Mace et al, 2013)](https://www.sorghumbase.org/paper/21275).

- The Boatwright SNP dataset [(Boatwright et al, 2022)](https://www.sorghumbase.org/paper/20741) consists of over 33 million SNPs and indels genotyped in 378 Sorghum Association Panel (SAP) accessions via whole-genome sequencing (WGS).

#### Tx2783

- About 32.5 million SNPs were called in 400 SAP lines by Rod Wing's group at King Abdullah University of Science and Technology with the GATK4 pipeline [Zhou et al (2024)](https://www.sorghumbase.org/paper/23243), and are now available from the Tx2783 genome browser. See for example [4_6047465_C_T](https://ensembl.sorghumbase.org/Sorghum_tx2783pac/Variation/Sample?db=core;r=4:6046965-6047965;v=4_6047465_C_T;vdb=variation;vf=11387812), a SNP predicted to introduce a STOP codon and result in a truncated [SbiRTX2783.04G076100](https://ensembl.sorghumbase.org/Sorghum_tx2783pac/Gene/Summary?db=core;g=SbiRTX2783.04G076100;r=4:6046424-6048133;t=SbiRTX2783.04G076100.1;v=4_6047465_C_T;vdb=variation;vf=11387812) protein product.


### Chemically induced genetic variation -  EMS-induced mutations
Currently in SorghumBase, there are three collections of EMS-induced mutant lines. EMS is a chemical commonly used to cause point mutations, that is, to change single nucleotides in the DNA of a plant seed.

- The Jiao_2016 dataset [(Jiao et al, 2016)](https://www.sorghumbase.org/paper/21276) includes over 1.7 million EMS-induced G/C to A/T transition mutations annotated from 252 M3 mutant family pools selected from the 6,400 sorghum mutant library in BTx623 background described by Xin and colleagues (Xin et al. 2008). Genomic DNA used for sequencing was pooled from 20 x M3 plants per M2 family (Jiao et al. 2016).
  
- The Addo-Quaye dataset [(Addo-Quaye et al, 2018)](https://www.sorghumbase.org/paper/19942) with over 2.5 million variations identified in 486 sorghum accessions from the M3 generation of an EMS-mutagenized sorghum population.

- The Jiao_2023 dataset [(Jiao et al, 2023)](https://www.sorghumbase.org/paper/23165) includes 8.9 million EMS mutations in 890 accessions, also available from the SorbMutDB resource. This set superseded the 1.7 million mutations originally called in the Jiao_2016 study.

Genetic variation data for a sorghum gene is available graphically and in tabular form, and for each variant, a Variant page provides more detailed information. Below are provided examples of each of these data representations.

- An [image](https://ensembl.sorghumbase.org/Sorghum_bicolor/Transcript/Variation_Transcript/Image?db=core;g=SORBI_3006G095600;r=6:46566240-46571064;t=SORBI_3006G095600.2;v=tmp_3_61561138_G_A;vdb=variation;vf=3821694) of all the genetic variants mapping to the smaller transcript of the Sobic.006G095600 gene.

  ![Variant image](images/variation_image.png)

- A [table](https://ensembl.sorghumbase.org/Sorghum_bicolor/Transcript/Variation_Transcript/Table?db=core;g=SORBI_3006G095600;r=6:46566240-46571064;t=SORBI_3006G095600.2;v=tmp_3_61561138_G_A;vdb=variation;vf=3821694) of all the Protein Truncated Variants (PTVs) mapping to the smaller transcript of the Sobic.006G095600 gene.

  ![PTVs table](images/variation_table_ptvs.png)
  
- An example of a [Variant summary page](https://ensembl.sorghumbase.org/Sorghum_bicolor/Variation/Explore?db=core;g=SORBI_3006G095600;r=6:46566240-46571064;t=SORBI_3006G095600.2;v=rs5437819034;vdb=variation;vf=47523480)
  for a deletion variant (rs5437819034 with alleles TA/-) that results in a frameshift in about 17% of the SAP.

  ![SNP summary](images/snp_summary.png)


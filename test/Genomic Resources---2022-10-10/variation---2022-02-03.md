## Genetic and Phenotypic Variation {#variation}

Genetic variation in SorghumBase is available for naturally occurring short variants (i.e., less than 50 nucleotides) and chemically induced point mutations. Naturally occuring short variants include Single Nucleotide Polymorphisms (SNPs) and Insertions/Deletions (indels). Over 78 million sorghum variants including more than 65 million SNPs genotyped in almost 900 accessions, and almost 13 million ethyl methanesulfonate (EMS)-induced variants in populations with a mutagenized BTx623 background, are available for version 3 of the reference genome assembly BTx623 (NCBIv3). In addition, a subset of 39.1 million SNPs is available in BTx623 version 5 (JGI_v5.1), which is subject to the [Fort Lauderdale accord](https://www.sanger.ac.uk/wp-content/uploads/fortlauderdalereport.pdf). Importantly, standard rsID identifiers assigned by the European Variation Archive (EVA) were mapped to approximately 41 million variants in both BTx623 assemblies, as well as 46 ex-PVP lines. 
In addition, approximately 32.5 million SNPs were called in Tx2783. Source studies for this genetic variation data follow.

### Naturally occurring genetic variation - SNPs & indels

Currently in SorghumBase, there are six SNPs data sets, five on sorghum BTx623 (four mapped to the NCBIv3 assembly and one to JGI_5.1), plus one on Tx2783.

#### BTx623 (NCBIv3)

- [Lozano et al (2021)](https://www.sorghumbase.org/paper/comparative-evolutionary-genetics-of-deleterious-load-in-sorghum-and-maize) - nearly 13M SNPs, 499 sorghum accessions from the TERRA-MEPP, TERRA-REF population panels, and lines previously genotyped by [Mace et al (2013)](https://www.sorghumbase.org/paper/21275)
- [Boatwright et al (2022](https://www.sorghumbase.org/paper/20741) - 33M SNPs and 5M indels genotyped by sequencing (**GBS**) 400 SAP lines
- [Kumar et al (2024)](https://www.sorghumbase.org/paper/24501) - 19.7M SNPs and 2.7M indels, whole-genome sequencing (**WGS**) 365 accessions (including 332 BAP)
- [Lasky et al (2015)](https://www.sorghumbase.org/paper/24502) - 405K SNPs, 2327 landraces (1943 georeferenced)

#### BTx623 (JGI_v5.1)

- [Global Sorghum Initiative](https://www.globalsorghuminitiative.org/) - 36.1 million SNPs called in 940 resequenced genomes from this Gates-funded initiative. Data kindly provided by Dr. Nadia Shakoor from the Donald Danforth Plant Science Center, Dr. John Lovell from the HudsonAlpha Institute for Biotechnology, and Dr. Geoff Morris from Colorado State University. The JGI_v5 assembly is subject to the Fort Lauderdale accord restrictions.

#### Tx2783

- [Zhou et al (2024)](https://www.sorghumbase.org/paper/23243) - 32.5M SNPs called in 400 SAP lines with the GATK4 pipeline. Example: [4_6047465_C_T](https://ensembl.sorghumbase.org/Sorghum_tx2783pac/Variation/Sample?db=core;r=4:6046965-6047965;v=4_6047465_C_T;vdb=variation;vf=11387812), a SNP predicted to introduce a STOP codon and result in a truncated [SbiRTX2783.04G076100](https://ensembl.sorghumbase.org/Sorghum_tx2783pac/Gene/Summary?db=core;g=SbiRTX2783.04G076100;r=4:6046424-6048133;t=SbiRTX2783.04G076100.1;v=4_6047465_C_T;vdb=variation;vf=11387812) protein product.


### Chemically induced genetic variation -  EMS-induced mutations
Currently in SorghumBase, there are three collections of EMS-induced mutant lines. EMS is a chemical commonly used to cause point mutations, that is, to change single nucleotides in the DNA of a plant seed.

- [Addo-Quaye et al (2018)](https://www.sorghumbase.org/paper/19942) - Over 2.5 million variations, 486 sorghum accessions from the M3 generation of an EMS-mutagenized sorghum population.
  
- [Jiao et al (2016)](https://www.sorghumbase.org/paper/21276) - Over 1.7 million EMS-induced G/C to A/T transition mutations annotated from 252 M3 mutant family pools selected from the 6,400 sorghum mutant library in BTx623 background described by Xin and colleagues (Xin et al, 2008). Genomic DNA used for sequencing was pooled from 20 x M3 plants per M2 family.

- [Jiao et al (2023)](https://www.sorghumbase.org/paper/23165) - 8.9 million EMS mutations in 890 accessions, also available from the SorbMutDB resource. This set superseded the 1.7 million mutations originally called in the Jiao et al (2016) study.

Genetic variation data for a sorghum gene is available graphically and in tabular form, and for each variant, a Variant page provides more detailed information. Below are provided examples of each of these data representations.

- An [image](https://ensembl.sorghumbase.org/Sorghum_bicolor/Transcript/Variation_Transcript/Image?db=core;g=SORBI_3006G095600;r=6:46566240-46571064;t=SORBI_3006G095600.2;v=tmp_3_61561138_G_A;vdb=variation;vf=3821694) of all the genetic variants mapping to the smaller transcript of the Sobic.006G095600 gene.

  ![Variant image](images/variation_image.png)

- A [table](https://ensembl.sorghumbase.org/Sorghum_bicolor/Transcript/Variation_Transcript/Table?db=core;g=SORBI_3006G095600;r=6:46566240-46571064;t=SORBI_3006G095600.2;v=tmp_3_61561138_G_A;vdb=variation;vf=3821694) of all the Protein Truncated Variants (PTVs) mapping to the smaller transcript of the Sobic.006G095600 gene.

  ![PTVs table](images/variation_table_ptvs.png)
  
- An example of a [Variant summary page](https://ensembl.sorghumbase.org/Sorghum_bicolor/Variation/Explore?db=core;g=SORBI_3006G095600;r=6:46566240-46571064;t=SORBI_3006G095600.2;v=rs5437819034;vdb=variation;vf=47523480)
  for a deletion variant (rs5437819034 with alleles TA/-) that results in a frameshift in about 17% of the SAP.

  ![SNP summary](images/snp_summary.png)


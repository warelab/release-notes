## Searching for a gene – Gene ID equivalences {#gene-search}

The SorghumBase search interface is not case sensitive and it allows you to search older sorghum gene identifiers (IDs) of the form SbXXX (MIPS/JGI Sbi1.4 in Phytozome) as well as Ensembl gene IDs of the form SORBI_3* and Sobic.* gene IDs (JGI v2.1). Thus, you may search for our exemplar MSD2 gene using SORBI_3006G095600, Sb06g018040, Sobic.006G095600.1 or Sobic.006G095600.2 (gene synonyms or different versions of the same gene model).

You may convert any Sobic.* to its corresponding SbXXX gene ID (JGI v2.1) using [JGI’s conversion file](https://genome.jgi.doe.gov/portal/Phytozome/download/_JAMO/55fca1de0d8785306f968fa1/Sbicolor_255_v2.1.locus_transcript_name_map.txt) (password-protected). The file provides mapping of *S. bicolor* gene IDs from MIPS/JGI Sbi1.4 to v2.1 and higher builds.

The file looks like this:

Sbi1.4 [Sobic.006G095600] ⇔ v2.1 [Sb06g018040]

#new-locusName    old-locusName

Sobic.006G095600	Sb06g018040

#new-transcriptName    old-transcriptName

Sobic.006G095600.1	Sb06g018040.1


The following rule applies for the conversion between Sobic.* and Ensembl gene nomenclature in use at SorghumBase:

Sobic.* => SORBI_3*


For example:

Sobic.006G095600 = SORBI_3006G095600

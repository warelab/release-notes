## Searching for a gene – Gene ID equivalences {#gene-search}

_**NOTE: Gene models mapped to the v5.1 assembly have a ".v5.1" suffix appended to the corresponding Sobic gene identifier like so: [Sobic.006G095600.v5.1](https://ensembl.sorghumbase.org/sorghum_bicolorv5/Gene/Summary?g=Sobic.001G121600.v5.1). However, searching for the Sobic gene identifier (Sobic.006G095600) will return both models (v3 and v5).**_


The SorghumBase search interface is not case sensitive and it allows you to search sorghum gene identifiers (IDs) of the form Sobic.* (JGI v2.1 and above), older gene IDs of the form SbXXX (MIPS/JGI Sbi1.4 or JGI v5.1 in Phytozome), and Ensembl gene IDs of the form SORBI_3*. Thus, you may search for our exemplar MSD2 gene using Sb06g018040, SORBI_3006G095600, Sobic.006G095600 or Sobic.006G095600.v5.1 (i.e., gene synonyms or different versions of the same gene model).

You may convert any Sobic.* to its corresponding SbXXX gene ID (JGI v2.1) using a synonyms mapping file such as Sbicolor_730_v5.1.synonym.txt (or [Sbicolor_255_v2.1.locus_transcript_name_map.txt](https://genome.jgi.doe.gov/portal/Phytozome/download/_JAMO/55fca1de0d8785306f968fa1/Sbicolor_255_v2.1.locus_transcript_name_map.txt) from Phytozome. Gene identifiers may be converted to JGI v5.1 by adding the '.v5.1' suffix to the JGI v2.1 identifer. The file provides mapping of *S. bicolor* gene IDs from MIPS/JGI Sbi1.4 to v2.1 and higher builds.

The file looks like this:

new MIPS/JGI Sbi2.1 [Sobic.006G095600] ⇔ old MIPS/JGI Sbi1.4 [Sb06g018040]

#new-locusName    old-locusName

Sobic.006G095600	Sb06g018040


The following rule applies for the conversion between Sobic.* and Ensembl gene nomenclature in use at SorghumBase:

Sobic.* => SORBI_3*


For example:

Sobic.006G095600 = SORBI_3006G095600

and

Sobic.006G095600.v5.1 = Sobic.006G095600


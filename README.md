# KASPspoon
Fine mapping becomes a routine trial following quantitative trait loci (QTL) mapping studies to shrink the size of genomic segments underlying causal variants. The availability of whole genome sequences can facilitate the development of high marker density and predict gene content in genomic segments of interest. Correlations between genetic and physical positions of these loci require handling of different experimental genetic data types, and ultimately converting them into positioning markers using a routine and efficient tool.
In order to convert classical QTL markers into KASP assay primers, KASPspoon simulates a PCR reaction by running an approximate-match searching analysis on user-entered primer pairs against the provided sequences, and then comparing in vitro and in silico PCR results. KASPspoon reports amplimers close to or adjoining genes/SNPs/simple sequence repeats and those that are shared between in vitro and in silico PCR results in order to select the most appropriate amplimers for gene discovery. KASPspoon compares physical and genetic maps, and reports the primer set genome coverage for PCR-walking. KASPspoon could be used to design KASP assay primers in order to convert QTL acquired by classical molecular markers into high-throughput genotyping assays and to provide major SNP resource for the dissection of genotypic and phenotypic variation. In addition to human-readable output files, KASPspoon creates Circos configurations that illustrate different in silico and in vitro results.

# INSTLATION
# FOR LINUX
You need to install perl 5, version 18, subversion 2 (v5.18.2) and TK Module. Or You can run spoon with "Spoon-without-GUI.pl" which does not need to install Tk from CPAN but you need to configure your run through config.info
sudo sh Install.sh 
perl Spoon.pl
or
Spoon-without-GUI.pl  CONFIGURATION-FILE  
For tutorial Please watch this vedio:
https://youtu.be/hLPcLNej4z4
# For windows
Run through EXE

# License
Spoon is free no license is required

# For Bugs please contact 

Smahmoud@ageri.sci.eg 

# Please Cite 
Alsamman, M.A., Ibrahim, S.D. and Hamwieh, A., 2019. KASPspoon: an in vitro and in silico PCR analysis tool for high-throughput SNP genotyping. Bioinformatics.btz004.

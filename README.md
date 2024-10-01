# Typhoid Genomics Consortium Paper: Typhi Mykrobe (2024)

This repository holds the tabulated data and code behind the paper of the [Global Typhoid Genomics Consortium](https://typhoidgenomics.org/), "Typhi Mykrobe: fast and accurate lineage identification and antimicrobial resistance genotyping directly from sequence reads for the typhoid fever agent _Salmonella_ Typhi" (preprint available in [BioRxiv](https://doi.org/10.1101/2024.09.30.613582)).

## Licenses and and re-use:

* The code in this repository is shared under a GNU general public license v3.0.

* The data, figures and tables in this repository form part of the publication noted above, which is published under a Creative Commons 4.0 License. If you use material in this repository, you should cite both the paper and this repository as the source.


## Main data files
`Supplementary_Table_1.csv`

* Tabulated Typhi Mykrobe output table, for all genomes included in validation analyses.

`Supplementary_Table_2.csv`

* Line list of all genomes used for validation, including sequence data accessions; plus genome-derived genotype, AMR and plasmid variables (where available) for mapping-based GenoTyphi lineage calls, and PathogenWatch.

`Supplementary_Table_3.xlsx`

* Details of AMR genotype calls comparison (in `/AMRplasmid` directory)
  
`Supplementary_Table_4.csv`

* csv file of all isolates with publicly availble antimicrobial susceptibility testing (AST) data sourced from three separate datasets used for validation of phenotype prediction. Includes minimum inhibitory concentration (MIC) data from the [UK Health Security Agency (UKHSA)](https://doi.org/10.1099/mgen.0.000633) for n=852 isolates (following EUCAST standards), and the [US Centres for Disease Control and Prevention (US CDC)](https://wwwn.cdc.gov/narmsnow/) for n=720 isolates (following CLSI standards), and disk diffusion data (following CLSI standards) for n=2,446 isolates collected and analysed from three countries as part of the [Surveillance for Enteric Fever in Asia Project (SEAP)](https://doi.org/10.1016/s2666-5247(22)00093-3).

`Supplementary_Table_5.csv`

* Comparison and error rates for AMR genotype and phenotype data (in `/AST` directory)

`Supplementary_Table_6.csv`

* Details of genomes used for validation of typing from nanopore reads (i.e. with matched Illumina and ONT data), including data accessions, ONT sequencing details and Mykrobe calls from both sequence data types.

## Genotype analysis

`/genotypes` directory

* `Mykrobe_genotypes.Rmd` = R markdown file for validation of genotype calls (Typhi Mykrobe vs mapping-based)
  
* `Mykrobe_genotypes.html` = knitR output of Rmd file, including all figures and numbers included in manuscript text
  

## AMR and plasmid analysis

`/AMRplasmid` directory

* `Mykrobe_AMRplasmid.Rmd` = R markdown file for validation of AMR and plasmid typing calls (Typhi Mykrobe vs Pathogenwatch)

* `Mykrobe_AMRplasmid.html` = knitR output of Rmd file, including all figures and numbers included in manuscript text

* figure files (PNG and PDF format; output from executing Rmd file)

* supplementary table files (CSV format; output from executing Rmd file)

## AST AMR analysis

`/AST` directory

* `Mykrobe_AMR_AST.Rmd` = R markdown file for validation of AMR prediction (Typhi Mykrobe predictions vs lab phenotype)

* `Mykrobe_AMR_AST.html` = knitR output of Rmd file, including output figures

* figure files (PNG and PDF format; output from executing Rmd file)

* supplementary table files (CSV format; output from executing Rmd file)

## Mykrobe on ONT data 

`/ONT` directory

* `Mykrobe_ONT.Rmd` = R markdown file for validation of typing from ONT reads (Typhi Mykrobe results for Illumina vs ONT reads)

* `Mykrobe_ONT.html` = knitR output of Rmd file, including output figures


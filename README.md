# Typhoid Genomics Consortium Paper: Typhi Mykrobe (2024)

This repository holds the tabulated data and code behind the Myrkobe paper of the [Typhoid Genomics Consortium](https://typhoidgenomics.org/), "Typhi Mykrobe: fast and accurate lineage and antimicrobial resistance genotyping direct from sequence reads for the typhoid fever agent Salmonella Typhi" (Add preprint link).

## Licenses and and re-use:

* The code in this repository is shared under a GNU general public license v3.0.

* The data, figures and tables in this repository form part of the publication noted above, which is published under a Creative Commons 4.0 License. If you use material in this repository, you should cite both the paper and this repository as the source. **This work represents the culmination of 20 years of typhoid genomics, with over 150 authors. It is here for the benefit of all, but please respect and acknowledge the effort of the authors when you come to re-use the data and ensure you cite appropriately.**


## Main data file 

`Supplementary_Table_1.csv`

* line list of all genomes including data accessions, plus genome-derived genotype and AMR and plasmid variables (where available) for original implementation, Mykrobe and PathogenWatch



## Genotype analysis

`/genotypes` directory

* `Mykrobe_genotypes.Rmd` = R markdown file for all analysis, generating tables and figures

* `Mykrobe_genotypes.html` = knitR output of Rmd file, including all figures and numbers included in text

* figure files (PNG and PDF format; output from executing Rmd file)

* supplementary table files (CSV format; output from executing Rmd file)

## AMR and plasmid analysis

`/AMRplasmid` directory

* `Mykrobe_AMRplasmid_summary.Rmd` = R markdown file for all analysis, generating tables and figures

* `Mykrobe_AMRplasmid_summary.html` = knitR output of Rmd file, including all figures and numbers included in text

* figure files (PNG and PDF format; output from executing Rmd file)

* supplementary table files (CSV format; output from executing Rmd file)

## Plotting phylogenetic trees

`/AST` directory

* `Mykrobe_AMR_AST.Rmd` = R markdown file for all analysis, generating tables and figures

* `Mykrobe_AMR_AST.html` = knitR output of Rmd file, including output figures

* figure files (PNG and PDF format; output from executing Rmd file)

* supplementary table files (CSV format; output from executing Rmd file)

## Mykrobe on ONT data 

`/ONT` directory

`Supplementary_Table_4.csv`

* line list of all genomes, including data accessions, and Mykrobe calls for genome-derived genotype and AMR and plasmid variables for matched Typhi isolates

* `Mykrobe_ONT.Rmd` = R markdown file for all analysis, generating tables and figures

* `Mykrobe_ONT.html` = knitR output of Rmd file, including output figures

* figure files (PNG and PDF format; output from executing Rmd file)

* supplementary table files (CSV format; output from executing Rmd file)

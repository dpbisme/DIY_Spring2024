# Overview of this repo

> This repo houses all of the R code, metadata, and ancillary files for the Spring 2024 offering of the [DIYtranscriptomics course](https://diytranscriptomics.com/). All sequencing data are on the course website as well as the Sequence Read Archive (SRA) under the study accession numbers [PRJNA875085](https://www.ncbi.nlm.nih.gov/sra/?term=PRJNA875085).

# Directory listing

- **/code** - contains all code used to produce all primary and supplementary figures from the manuscript. Note, neither of the shell scripts below are run as part of this code capsule, however they are provided here for reproducibility.
    - */code/readMapping.sh* - Script for automating quality control of reads and mapping to an indexed reference transcriptome file.
    - */code/Step1_Tximport.R* - Handles importing Kallisto count data into R.

- **/kallisto_outputs** - each folder corresponds to the Kallisto output from mapping a single fastq file to the human reference transcriptome. Kallisto version 0.50.1 was used.





# Analysis Code for lectin-anchored, synthetic biotinylated RNA (sbRNA)-based cell hashing
This repository contains the code for the data analysis performed in the manuscript **“RNA-based cell hashing enables sample multiplexing without dedicated barcode capture”**.

## Repository Contents
This repository contains the analysis of Smart-seq3xpress ([SS3x](SS3x/)) and 10x chromium ([droplet_scRNAseq](droplet_scRNAseq/)) data sets of sbRNA-labelled cell lines, and the analyses for comparison of cell detachment methods, viability assay, and lectin stainings ([detachment_viability_staining](detachment_viability_staining/)). The code files produce the numbers and figures presented in the manuscript.

The analyses and files required to reproduce the figures of the manuscript are organized in individual sub-directories. These contain `.Rproj` and `.Rmd` files among other files used in the analyses, and the generic sbRNA FASTA reference for the 10x experiment.

## Software information
The analysis was done in [R](https://www.r-project.org/) (version 4.4.2) and [RStudio Server](https://posit.co/products/open-source/rstudio-server/) (version 2023.12.1). Packages including versions used for the analyses are recorded using [renv](https://rstudio.github.io/renv/) (version 1.0.11).

## Data Availability
The datasets (e.g. sequencing FASTQ files and count matrices) generated for this manuscript are available on ArrayExpress under accession numbers *E-MTAB-17623 (SS3x)* and *E-MTAB-17624 (10x)*.

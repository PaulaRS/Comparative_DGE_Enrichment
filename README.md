# Code for "Transcriptomic responses of adult versus juvenile atlantids to ocean acidification"

[![CC BY 4.0][cc-by-shield]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

_Author_: Mari-Lee Odendaal
_Date_: 01-02-2022

This code accompanies the manuscript '_Transcriptomic responses of adult versus juvenile atlantids to ocean acidification_'.

## Description

This repository contains the Rmd-scripts ([`scripts/`](scripts/)) used to generate the results within the manuscript. The aim of this project was to study the transcriptomic responses of adult and juvenile _Atlanta ariejansseni_ to past, present and future ocean chemistry.

Reads used in this study were deposited at NCBI BioProject PRJNA742523. The Transcriptome Shotgun Assembly has been deposited at DDBJ/EMBL/GenBank under the accession GJHI00000000. Formatted input-files are available upon request.

The included code was ran in R version 4.0.4.

## File description
([`scripts/`](scripts/)) 

- [`differential_gene_expression.Rmd`](scripts/differential_gene_expression.Rmd): Differential gene expression analysis with DESeq2
- [`correlation_analysis.Rmd`](scripts/correlation_analysis.Rmd): Pearson correlation analysis
- [`enrichment_analysis.Rmd`](scripts/enrichment_analysis.Rmd): Visualization of the GO enrichment analysis

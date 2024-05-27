# Metabolic injury signature in human CD samples
This repository contains R code which was used to study the expression of a metabolic injury signature discovered in mice in a [human Crohn's Disease cohort](https://doi.org/10.1093/ecco-jcc/jjac021).
Two R notebooks are included:
- ibd_prediction.Rmd: Compares the expression patterns of the signature between humans and mice
- DEG Analysis.Rmd: Contains a differential expression analysis for the human data, highlighting the signature genes

## Usage
Clone the repository:

```bash
https://github.com/biomedbigdata/gene_signatures.git
```
Navigate to the directory:

```bash
cd gene_signatures
```
Install dependencies by opening an R session and running:
```R
renv::install()
```
Run the R notebooks, e.g. with RStudio.

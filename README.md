# A. mexicanum annotation

This repository contains the files used for the analysis described by Del Moral et al in the manuscript titled ¨Transcriptomics of A. mexicanum Regeneration: A Comparative Study of Aged Axolotl Limbs Reveals Key Proteins And Pathways for Limb Regeneration.¨

The gene_annotation.txt file contains the gene names assigned as described in the paper.

The Amex.v6.annotation.sqlite.tar.gz file is the compressed TxDb file that can be used by the GenomicFeatures package for R.

To load it first clone the repository and decompress the file:
```bash
tar -xvf Amex.v6.annotation.sqlite.tar.gz
```
To load the Txdb object into R:

```R
library(GenomicFeatures)
txdb <- loadDb("path/to/Amex.v6.annotation.sqlite")
```
The org.Amexicanum.eg.db.tar.gz is the compressed OrgDb directory required to load this package for its use with AnnotationDbi.

To load it first clone the repository and decompress the file:
```bash
tar -xvf org.Amexicanum.eg.db.tar.gz
```
To use the OrgDB package in R:

```R
install.packages("file.path( path/to/org.Amexicanum.eg.db", "org.Amexicanum.eg.db"), 
                 type = "source", repos=NULL)
library(org.Amexicanum.eg.db)
```


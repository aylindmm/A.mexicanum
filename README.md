# A. mexicanum annotation

This repository contains the files used for the analysis described by Del Moral et al in the manuscript titled ¨Transcriptomics of A. mexicanum Regeneration: A Comparative Study of Aged Axolotl Limbs Reveals Key Proteins And Pathways for Limb Regeneration.¨

The gene_annotation.txt file contains 

To use the OrgDB package:

```R
install.packages(file.path( path/to/org.Amexicanum.eg.db file, "org.Amexicanum.eg.db"), 
                 type = "source", repos=NULL)
```
To use the Txdb object

library(GenomicFeatures)
```R
txdb <- loadDb("path/to/Amex.v6.annotation.sqlite")
```


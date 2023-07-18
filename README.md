# A.mexicanum

To use the OrgDB package:
in R: 
install.packages(file.path( path/to/org.Amexicanum.eg.db file, "org.Amexicanum.eg.db"), 
                 type = "source", repos=NULL)

To use the Txdb object

library(GenomicFeatures)

txdb <- loadDb("path/to/Amex.v6.annotation.sqlite")
```


# -RGeneDamIDSeq-
All in R DamID sequencing pipeline (use genes as bin)

Includes adapter removal, Mapping and enrichment finding for DamID-Seq reads.
This version includes gene level bins. 

For more information see also: [Tools for DNA adenine methyltransferase identification analysis of nuclear organization during C. elegans development](http://onlinelibrary.wiley.com/doi/10.1002/dvg.22925/abstract)

install
-------

1) Install R (only 64 bit version!)  
[R Project](https://www.r-project.org/ "The R Project for Statistical Computing")


2) Download GeneDamIDseq_0.1.4.tar.gz

3) install additional packages needed for the pipeline in R   

`install.packages(c('corrplot', 'aqfig'))`  
`source("https://bioconductor.org/biocLite.R")`  
`biocLite()`  
`biocLite(c("QuasR", "ShortRead", "GenomicRanges", "S4Vectors", "IRanges",`   
`"BiocInstaller", "Biobase", "Biostrings", "BSgenome", "GenomicFeatures", `    
`"GenomicAlignments", "BiocParallel", "GenomeInfoDb", "rtracklayer", `    
`"GenomicFiles", "Rbowtie", "biomaRt"))`  

4) install GeneDamIDSeq in R   
(exchange `PATH` with the path to the installation file on your disk)  

`install.packages("PATH/GeneDamIDseq_0.1.4.tar.gz", repos = NULL, type = "source")`  

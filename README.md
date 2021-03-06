# tximport

Import and summarize transcript-level estimates for gene-level analysis

---

Imports transcript-level abundance, estimated counts and 
transcript lengths, and summarizes into matrices for use with downstream
gene-level analysis packages such as edgeR, DESeq2, limma-voom. 
Average transcript length, weighted by 
sample-specific transcript abundance estimates, is provided as a matrix
which can be used as an offset for different expression of 
gene-level counts.

See examples in [vignette](https://github.com/mikelove/tximport/blob/master/vignettes/tximport.md)

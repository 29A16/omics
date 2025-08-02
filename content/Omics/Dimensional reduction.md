---
OMICS: "[[1 Inbox/Archive/Omics 1/L11 Single cell Transcriptomics]]"
---
[[Batch Integration]]
Since each sampled gene represents one dimension the data is very complex even if the relation of genes is not considered. Another *'course'* that comes with increased dimensions is the higher distance between data points, which makes clustering/grouping of cells hard.![[scRNAseq2.pdf#page=28&rect=474,35,932,391|scRNAseq2, p.28]]
Dimensions can be reduced if only genes with high variability are selected (as mentioned before, these genes are assumed to be the cause of biological difference between samples). PCA is the simplest method used and utilizes linear transformation, which accurately represents the distance between the cells. For more complex data, where finer clustering is required either **tSNE or UMAP** are used. Both are better in displaying different data but the distance between datapoints is not represented accurately, and therefore no quantification can be performed. They are mainly used to visualize different clusters/groups.

---
Created: 2024-12-22 16:13
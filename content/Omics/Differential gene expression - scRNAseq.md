---
OMICS: "[[1 Inbox/Archive/Omics 1/L11 Single cell Transcriptomics]]"
---
Many statistical tools exist to validate the difference between [[Clustering scRNAseq|clusters]] and treatments/conditions within the same cluster.
These methods can be categorized as **Parametric or non-parametric**. Parametric methods like **DESeq2** assume a specific distribution of the data and can be very efficient for large datasets if the assumptions hold true. Non-parametric methods like **Seurat's Wilcoxon test** on the other hand don't rely on assumptions about the distribution of data.

---
Created: 2024-12-22 17:01
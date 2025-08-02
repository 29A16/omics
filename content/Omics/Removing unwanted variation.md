---
OMICS: "[[1 Inbox/Archive/Omics 1/L11 Single cell Transcriptomics]]"
---
## Variation
The data obtained from [[Single cell RNA sequencing (scRNAseq)|scRNAseq]] has a lot of variation. 
Technical variations arise (among others) from the quality of the cells, the preparation efficiency or batch effects, while unwanted biological variation can stem from the cell cycle, sex, age, transcriptional bursting or the cell size. The only Biological variation that is of interest is the cell type and its state.
## Filtering
Some unwanted variation can be removed by filtering out:
- Low capture genes
- Non-viable cells and cells with low viability
- Doublets (droplets with multiple cells)
- Empty droplets
## Normalization
Some reasons for differing UMI count (assumed to correlate 1:1 to mRNA count) are:
- Variation in capture, translation (cDNA) and sequencing efficiency between cells
- Cell size
- Cell cycle
- Batch effect
- Transcriptional burst
We are only interested in the biological effect e.g. of a treatment. In **LogNormalization** we make the assumption, that all the sampled cells have the same molecular composition — this invalid, when different cell types are compared.
Another normalization method is **SCTransform**. Gene expression is often assumed to follow a Poisson distribution, where the mean is equal to the variance. This is typically not true, variance that is bigger than the mean can be often found — **overdispersion** and therefore SCTransform utilizes negative binomial transformation instead of assuming Poisson distribution. SCTransform can also regress out (remove the effect of) some covariation discussed above. The dimensionality of the sample is also reduced by selecting highly variable genes that are assumed to correspond to the biological effect.

---
Created: 2024-12-22 15:19
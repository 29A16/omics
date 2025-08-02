---
OMICS: "[[1 Inbox/Archive/Omics 1/L13 Multiomics]]"
---
MOFA is an [[Supervised vs. Unsupervised multiomics|unsupervised]] multiomics method, that tries to identify the shared and unique source of variation between the different omics that are analysed. This requires dimensional reduction just like PCA. It allows for **sparsity** (missing values between omics) and uses **regularization**, which selects the most important features (with the highest weight) to reduce the dimensionality of the data (similar to the highest components in PCA). To account for different data types, the underlying distribution has to be known (Normal, Poisson — count data, Gauss — continuous data, Bernoulli — binary)
The input matrix (Y) collects the measured features for each sample and used to generate the weight matrix (W) that matches the features with factors and assigns weights to the factors, that are proportional to their influence on the features (e.g. this gene/mutation explains the factor well). The latent factors (Z) — describing the variation across the sample are then mapped back to the samples.
![[Multi-Omics Integration.pdf#page=13&rect=452,21,712,321|Multi-Omics Integration, p.13]]
A factor wide sparsity (in W) means, that there is no connection to the underlying data set (Y) (e.g. factor 1 in w2). Genes with high weight of different factors are orthogonal/independent of each other.

---
Created: 2024-12-23 18:01
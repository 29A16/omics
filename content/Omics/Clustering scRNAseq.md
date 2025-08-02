---
OMICS: "[[1 Inbox/Archive/Omics 1/L11 Single cell Transcriptomics]]"
---
The [[Dimensional reduction|reduced]] data can be structured into clusters of cells with similar gene expression profiles. PCA is performed on the data and the distance between the data points is used to identify the nearest neighbours. The lines in the resulting KNN graph are called edges and the data points/cells are nodes. When the edges get a weight assigned to them, a SNN graph is created, which is used in a final step to find clusters/groups.
**Modularity** is a measurement to evaluate the quality of the clustering, by comparing the density of the edges within clusters to the expected density of randomly distributed edges.
$$
Q = \frac{1}{2m}\sum_{ij}{[A_{ij}-\frac{k_ik_j}{2m}]}\delta(c_i,c_j)
$$
An algorithm used for modularity optimization is Leiden.
## Resolution and quality evaluation
The higher the resolution we chose, the finer the clustering. Here a balance has to be found, since to high resolutions can split one cell type into populations, that do not exist and low resolution might miss rare cell types.
To help with setting the right resolution, **Siluette scoring** (measuring the density of cells), automatic annotation (before clustering) or the identification of specific genes can be used to identify the correct clusters. 

---
Created: 2024-12-22 16:38
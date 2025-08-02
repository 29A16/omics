---
OMICS: "[[L12 Spatial omics]]"
---
Similar to scRNAseq processing, where the spatial barcode corresponds to the location of the cell. A correction step is included, that removes duplicated reads from the same cell.
1. Quality Control of FASTQ file — remove low quality barcodes/UMI
2. Barcode/UMI correction
3. Mapping of the reads to genome
4. Feature matrix
5. Visualization in a heatmap superimposed onto the tissue image
Image based methods have to create [[Image pre-processing|segments]], that represent cells from the tissue. The positioning is given by the spatial barcode in sequencing based methods like Visium.
## Increased resolution by single cell deconvolution
Machine learning in connection with statistical models can be used with reference data (also form scRNAseq) to increase the resolution of spots containing multiple cells in e.g. Visium derived images. 

---
Created: 2024-12-23 16:49
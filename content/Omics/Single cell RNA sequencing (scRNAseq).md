---
OMICS: "[[1 Inbox/Archive/Omics 1/L11 Single cell Transcriptomics]]"
---
#startingpoint 
The difference between transcriptomics/bulk RNAseq and scRNAseq is the amount of cells that are analysed. While bulk RNAseq pools multiple cells to measure differential transcription, scRNAseq focusses on single cells and therefore can differentiate between different cell types (smoothy vs. fruit salat).  
## scRNAseq steps
1. Sample preparation
2. Cell capture (chambers/wells/droplets) with specific tags
3. The cells are lysed in the **library preparation step**
	1. mRNA of the cells is captured with oligonucleotide tag, including a Unique Molecular Identifier (UMI) — to arrive at the amount of captured mRNA after PCR (it is assumed, that each UMI corresponds to one mRNA molecule)
	2. Translation into cDNA
4. Sequencing
5. Analysis
Differentiation and correct sorting of cells is very important to map the transcription to a cell type. Initial scRNAseq techniques like SMART-seq focussed on well based sorting. This is often labour intensive and relatively expensive. Newer techniques like **10x Genomics** utilize microfluidics to capture single cells in droplets and identify them with oligo-tagged beads.
[[Removing unwanted variation]]

---
Created: 2024-12-22 14:55
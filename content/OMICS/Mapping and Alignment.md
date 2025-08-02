---
OMICS: "[[L3 Transcriptomics]]"
---
## Alignment
The sequenced transcriptome can be aligned with a reference genome or transcriptome. 
There is a distinction between **global- and local alignment**. In a global alignment, the whole sequence undergoes alignment (for closely related species), where local alignment focuses on regions with high similarities (for more divergent sequences).
The so called **Pseudoalignment** aligns to a transcriptome reference, which makes it faster than the conventional alignment to a genomic reference. This enables different modes of analysis, like the analysis of gene splicing but also limits its potential for the discovery of novel transcripts/variants.
If no reference genome exists or the aim of the experiment is to find complex mutants/study polymorphism, **denovo assembly** has to be considered.

The generated alignment data is stored in [[SAM;BAM files]] and MultuQC can be used for Alignment QC.
![](../Attachments/KIMN20_Transcriptomics_intro_-521013114.png)(^^good to know QC statistics)
## Mapping
The [[Differential gene expression]] levels found on a transcriptomic level are transferred to the genome level in the mapping step.
![](../Attachments/KIMN20_Transcriptomics_intro_-521013114%201.png)

---
Created: 2024-11-27 16:00
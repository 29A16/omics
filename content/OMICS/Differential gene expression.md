---
OMICS: "[[L3 Transcriptomics]]"
---
After the [[Library and sequencing|sequencing]] is complete, the DGE is used to gain insight into the cellular response to a change in conditions/treatment.
![](../Attachments/KIMN20_Transcriptomics_intro_-521013114%202.png)
## Quality control
When paired end sequencing was used, both R1 and R2 reads are used for quality control (QC) and annotation.
Most of the same tools and data formats utilized in Genomics are also used for the evaluation of transcriptomic data.
[[FASTQ files]] are the typical output of mRNA sequencing data and [[FastQC]] is often used for QC (MultiQC is used to summarize FastQC data of multiple sequences).
## Trimming
Trimming is an important step, where the adapter sequences, still present in our sample, are removed. Today alignment tools include this step automatically.
## Indexing
An index is created to make the alignment more efficient. The index provides a target for the alignment on the reference genome.
## Genome builds
Genomes are constantly updated and therefore the same version of the genome has to be used for all analysis. There are so called *'lift over'* processes but they are error prone.


---
Created: 2024-11-27 15:37
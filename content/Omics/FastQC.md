---
OMICS: "[[L2 Denovo Assambly]]"
---
To address the quality of the [[Denovo Assembly|de novo]] sequence from [[Illumina technology|Illumina sequencing]], FastQC provides a quick way to check on some basic statistics. 
![[denovoAssembly_KIMN020.pdf#page=4&rect=461,81,827,432|denovoAssembly_KIMN020, p.4]]
## Quality score - Per base sequence quality
The Quality score in the top right shows the [[FASTQ files|Phred]] score for each base. The quality of the sample degrades over the length of the sequence/the probability for errors increases. 
## GC distribution - Per sequence GC content
An optimal distribution o GC content is shown in blue and compared to the actual GC distribution within the sample. A deviation, like additional peaks, might indicate contamination by either foreign DNA or the presence of specific motifs like adapters.
## Over-represented sequences
Sequences that are found in high abundance are matched with known contaminates.
## Adapter content
The adapter content is also analyzed to reveal the presence of known adapter sequences.

---
Created: 2024-11-27 09:06
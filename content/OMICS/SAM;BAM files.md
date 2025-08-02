---
OMICS: "[[L1 Genomics and NGS]]"
---
Sequence Alignment Map (SAM) files are created after aligning to [[Sequencing|sequences]] with each other, e.g. when comparing a sequenced sample to a reference from a database. The file contains information on the accuracy of the alignment and also includes the genome coordinates of the sequence (Position of the gene in the genome). Binary Alignment Map (BAM) contains the same information but is in a compressed format, that is not human-readable.

~~~
@HD    VN:1.6    SO:coordinate  
@SQ    SN:chr1   LN:248956422  
read1  0         chr1   100    255   50M   *   0   0   ACGT...   IIII...
~~~
Where the two headers give information on the sorting and reference sequence. The third line gives information on the reference sequence name, Alignment position and the quality of the mapping.

---
Created: 2024-11-26 09:24
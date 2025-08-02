---
OMICS: "[[L2 Denovo Assambly]]"
---
To qualify whether the assembly is missing parts of the sequence in a [[Burijin alignment]] after filtering the data e.g. when [[Removing contamination|removing contaminations]], the k-mers included in the consensus sequence (red) are compared with the excluded ones (black). 
![[denovoAssembly_KIMN020.pdf#page=28&rect=131,35,817,356&color=yellow|denovoAssembly_KIMN020, p.28]]
The figure shows the k-mer analysis for one chromosome, the graph can look different if there are more than one. Sometimes one might also want to exclude a chromosome/different peaks.![[denovoAssembly_KIMN020.pdf#page=29&rect=6,77,823,341&color=yellow|denovoAssembly_KIMN020, p.29]]
Where do the missing k-mers on the left come from?
When observing a heterozygous region (containing similar/the same information on one gene) in the genome, the alignment decides on one of the two options. The k-mers of the part of the sequence, that was not chosen, show up as missing in the final assembly.![[denovoAssembly_KIMN020.pdf#page=30&rect=104,182,865,333&color=yellow|denovoAssembly_KIMN020, p.30]]

---
Created: 2024-11-27 11:16
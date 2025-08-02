---
OMICS: "[[L2 Denovo Assambly]]"
---
To qualify whether the assembly is missing parts of the sequence in a [[Burijin alignment]] after filtering the data e.g. when [[Removing contamination|removing contaminations]], the k-mers included in the consensus sequence (red) are compared with the excluded ones (black).![](../Attachments/denovoAssembly_KIMN020%203.png)
The figure shows the k-mer analysis for one chromosome, the graph can look different if there are more than one. Sometimes one might also want to exclude a chromosome/different peaks.
![](../Attachments/denovoAssembly_KIMN020%204.png)Where do the missing k-mers on the left come from?
When observing a heterozygous region (containing similar/the same information on one gene) in the genome, the alignment decides on one of the two options. The k-mers of the part of the sequence, that was not chosen, show up as missing in the final assembly.
![](../Attachments/denovoAssembly_KIMN020%205.png)

---
Created: 2024-11-27 11:16
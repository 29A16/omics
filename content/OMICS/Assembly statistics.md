---
OMICS: "[[L2 Denovo Assambly]]"
---
Basic statistics can be generated from either [[Overlap Layout Consensus Alignment]] or [[Burijin alignment]], when comparing **contigs** and **scaffolds** with each other. Contigs are aligned sequences without any gaps, where scaffolds are groups of contigs, that are aligned with each other but contain gaps.
The size of the contigs also plays a role. Small contigs often represent sequencing errors or sequencing errors and are often filtered out since they don't contribute new relevant information to the consensus sequence![](../Attachments/denovoAssembly_KIMN020%201.png)
## N50
N50 is a statistical value, that represents the size of the smallest contig in the set of largest contigs, that make up 50% of the assembly sample.
![](../Attachments/denovoAssembly_KIMN020%202.png)This allows for some fast insight into the distribution of contigs and their lengths. 
But N50 still has some disadvantages:
- No information on how correct the assembly is
- Not comparable between species with different genome size
- Bias is introduced, when smaller sequences are removed
## NG50
NG50 adresses some short commings of N50 and compares the size of the smallest contig in the set of largest contigs, that make up 50% of the estimated **genome** size (not the assembly).

## Quast
Quast is a tool, that allows the comparison of different assemblies, including basic statistics mentioned above.

---
Created: 2024-11-27 10:53
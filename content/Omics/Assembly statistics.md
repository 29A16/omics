---
OMICS: "[[L2 Denovo Assambly]]"
---
Basic statistics can be generated from either [[Overlap Layout Consensus Alignment]] or [[Burijin alignment]], when comparing **contigs** and **scaffolds** with each other. Contigs are aligned sequences without any gaps, where scaffolds are groups of contigs, that are aligned with each other but contain gaps.
The size of the contigs also plays a role. Small contigs often represent sequencing errors and are often filtered out since they don't contribute new relevant information to the consensus sequence.![[denovoAssembly_KIMN020.pdf#page=23&rect=94,35,774,415&color=yellow|denovoAssembly_KIMN020, p.23]]
## N50
N50 is a statistical value, that represents the size of the smallest contig in the set of largest contigs, that make up 50% of the assembly sample.![[denovoAssembly_KIMN020.pdf#page=24&rect=70,14,906,301|denovoAssembly_KIMN020, p.24]]This allows for some fast insight into the distribution of contigs and their lengths. 
But N50 still has some disadvantages:
- No information on how correct the assembly is
- Not comparable between species with different genome size
- Bias is introduced, when smaller sequences are removed
## NG50
NG50 adresses some short commings of N50 and compares thes size of the smallest contig in the set of largest contigs, that make up 50% of the estimated **genome** size (not the assembly).

## Quast
Quast is a tool, that allows the comparison of different assemblies, including basic statistics mentioned above.

---
Created: 2024-11-27 10:53
---
OMICS: "[[1 Inbox/Archive/Omics 1/L6 Proteomics - Data]]"
---
Although we are able to [[Identify peptides with tandem MS|identify]] the peptides present in the sample, we are primary interested in the proteins present in the sample.
To arrive at the protein, the peptide sequences are overlapped, similar to alignment processes of genomics and transcriptomics. Although he sequence length is reduced in proteomics, the amount of variable building blocks is increased (20 AA). The sequence overlap is also smaller, since the peptides are generated with specific enzymatic cuts.
The inference is complicated by different isoforms of the same protein. 
![[KIMN20_data_identification_quantification_2067540178.pdf#page=57&rect=151,43,716,445|KIMN20_data_identification_quantification_2067540178, p.57]]
The peptides are then grouped into possible alignments and the simplest solution is chosen (Orcamz razor). If this is not possible aka the peptide groups are indistinguishable from each other, both groups are reported. If there is at least one unique peptide between the groups, we know both species are present but not their distribution. 
![[KIMN20_data_identification_quantification_2067540178.pdf#page=60&rect=167,62,493,444|KIMN20_data_identification_quantification_2067540178, p.60]]
FDR can also be generated with targeted decoys on the protein level.
## Scaling up problem
When the amount of samples is increased, the FDR also increases. To combat this, decoys are used for each peptide. (just know that scale up is a problem)

---
File Creation date: 2024-10-20 09:07

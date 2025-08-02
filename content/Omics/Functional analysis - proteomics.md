---
OMICS: "[[1 Inbox/Archive/Omics 1/L7 Proteomics data analysis]]"
---
After [[Validation of found clusters|validating]] the clusters, one can proceed to map the identified proteins to their biological pathway. 
The data can be used in a pathway enrichment analysis to establish the differential abundance of proteins (cut-off required) or in a gene enrichment analysis, where a relation is made to the gene level (no cut-off required).
Pathway and network analysis are more sophisticated methods, that relate the differential expression to their pathways. There are different tools like **KEGG**, that visualize the network with up- and down regulated proteins, enabling better understanding of the pathway.
![[KIMN20_data_analysis_270742404.pdf#page=26&rect=122,6,732,454|KIMN20_data_analysis_270742404, p.26]]
**GSEA** is used to determine whether a protein is up- or down regulated by assigning either a positive or negative value, allowing a pathway analysis without looking up the function of the proteins.
![[KIMN20_data_analysis_270742404.pdf#page=45&rect=57,19,525,427|KIMN20_data_analysis_270742404, p.45]]

**STRING** networks can be created to identify upregulated genes, that are *'hot-spots'* — representing high connectivity. The tool also connects the nodes in the network to relevant literature.![[KIMN20_data_analysis_270742404.pdf#page=46&rect=39,35,909,485|KIMN20_data_analysis_270742404, p.46]]


---
Created: 2024-12-20 10:08
---
OMICS: "[[L10  Metabolomics - Data handeling]]"
---
The feature annotation of metabolomics data is the true bottleneck in the procedure, which is created by the massive amount of information. As much as possible **orthogonal information**, like the molecule mass, isotope pattern retention time and MS/MS spectra help with the annotation process. 
Known metabolite spectra can be utilized in **database matching** with either public data or own libraries (most of the public retention time indexes are for GC/MS).
To assure the presence of specific metabolites, **chemical standards** can be of great help, but might be too expensive for most cases.

Confidence levels are used to clarify the certainty of the annotation. ![[Metabolomics3.pdf#page=13&rect=101,94,707,423|Metabolomics3, p.13]]All levels above level three require at least a comparison to a reference database/library (most metabolomics go up to level two).
Even when a standard is used and both retention time and peak are aligning, the metabolite could still be an isomer. To differentiate isomers, the sample is spiked with the reference.
The identified metabolites are then captured in a feature table with all relevant information
![[Metabolomics3.pdf#page=17&rect=46,17,824,494|Metabolomics3, p.17]]

---
Created: 2024-12-22 11:22
---
OMICS: "[[L6 Proteomics - Data]]"
---
To reveal the [[Errors in assigning peptides]] and estimate the **false discovery rate (FDR)** decoy databases can be used (for large scale data). The decoy consists of data, that doesn't match the sample. 
They can be created by **reversing** the actual sequence, **shuffling** or **randomly** distributing it.

The FDR (expected number of false positives) is calculated by a ratio of decoy hits and normal hits (above a defined score cutoff). A FDR of 0.1 would mean, that 10% of the sequences can be expected to be identified incorrectly. 
$$
FDR = \frac{decoy\_hits}{hits}
$$
The FDR can be adjusted by changing the cutoff. The resulting reduction of false positives also comes with a reduction of true identifications. Most commonly a FDR of 1% is chosen.

---
Created: 2024-12-12 08:32
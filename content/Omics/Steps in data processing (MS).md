---
OMICS: "[[L10  Metabolomics - Data handeling]]"
---
[[Metabolomics - Data processing]]
1. [[Peak picking and filtering]] (e.g. exclusion of peaks, that are unique to one sample)
2. [[Peak grouping]] of isotope envelopes
3. Identification based on the isotope envelope/group
4. [[Spectral alignment|Alignment]] corrects for shifts in the data (can also be done before ==peak grouping==)
5. Recursive analysis/gap filling assures the completeness of the data by comparing the identified peaks with each other (if necessary thresholds can be adjusted to not loose important data)
6. [[Feature annotation|Feature table]] is generated
7. Statistical analysis to confirm weather differences are significant.
Also [[Normalization of metabolomic data]]

---
Created: 2024-12-21 16:17
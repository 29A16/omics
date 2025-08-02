---
OMICS: "[[L10  Metabolomics - Data handeling]]"
---
[[Metabolomics - Data processing]]
## Univariant statistics — t-test
Tests for significant difference between two well-defined groups (one metabolite at a time), assuming normally distributed data — since natural data is often log normal distributed, transformation of the data might be required. If a high number of tests are performed a correction for multiple testing is necessary (FDR). 
The metabolome shows high degrees of co-variation (one metabolite is affected by others) and the tests can therefore be simplified.
But the data is frequently not easily dividable into two distinct groups.

## Multivariant statistics — ANOVA
Deals with multiple factors and compares the total variation to the variation of the different factors. The variation that is left over should follow normal distribution if all factors are accounted for.
An F-test is used to compare the variation of treatments/conditions with the general variation. 
A multivariant analysis is required, if there are **interactions** of different factors (response of one factor depends on another)

---
Created: 2024-12-22 11:55
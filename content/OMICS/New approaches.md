---
OMICS: "[[L6 Proteomics - Data]]"
---
## Open search
Open source approach, that allow matching of unknown modifications.
## Spectral library search
This approach doesn't rely on the use of theoretical spectra but takes previous measurements performed with the same setup to generate an annotated library for use on samples. This allows to use rel world peak intensities and removes the reliance on external databases and trust in their quality.
Some disadvantages are the specificity of the used setup and the time-consuming library generation. As with databases, only samples with a reference already in the library can be analyzed.
## Spectra prediction
There are some AI driven methods available, that are able to predict the MS spectra from the sequence. These also consider the retention time of HPLCs and can be used for *denovo* sequencing. Some of these predictions are even better than generated libraries.
[[Identify peptides with tandem MS]]

---
Created: 2024-12-12 09:30
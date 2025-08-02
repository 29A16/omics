---
OMICS: "[[L10  Metabolomics - Data handeling]]"
---
[[Steps in data processing (MS)]]
The alignment can remove confounding effects. 
In NMR based metabolomics a shift in the ppm dimension can occur due to different pH, ionic strengths or protein content (…).
GC/LC-MS shifts mainly occurs in the time dimension and can be caused by aging phases, solvent evaporation or temperature change (…).
There are two types of alignment, **spectral alignment** that is performed before peak picking and **peak based alignment** that is performed after peak picking.
The spectral alignment is nonlinear and maximises the correlation between the spectra of different samples (time/ppm axes). It sometimes requires a selection of reference spectra, which **might introduce biases**.
Peak based alignment assumes minimal drift in the m/z dimension and performs binning in m/z intervals.

---
Created: 2024-12-21 16:39
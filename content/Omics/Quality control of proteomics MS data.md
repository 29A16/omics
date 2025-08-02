---
OMICS: "[[1 Inbox/Archive/Omics 1/L7 Proteomics data analysis]]"
---
To ensure the quality of the MS data, some important parameters should be considered:
- Data distribution of different samples (see [[Normalization of MS data|normalization]])
- Total intensities of different samples
- Missing values between different samples
- Dimensionality reduction with e.g. PCA
These can also be used to remove outliers (based on technical errors).
## Volcano plot
A prominent method to for quality control is a **Volcano Plot**. The plot shows the log2 fold change in relation to the adjusted p-value (see [[Clustering]]) between two conditions. The fold change is a value that represents the abundance of a protein — where a positive value represents high abundance and a negative value low abundance. Since the fold change is log2 transformed, a value of 1 would mean a 2 times higher abundance of the species. A symmetric volcano plot indicates normal distribution of the data. 
![[KIMN20_data_analysis_270742404.pdf#page=44&rect=161,54,939,418|KIMN20_data_analysis_270742404, p.44]]

---
Created: 2024-12-13 14:40
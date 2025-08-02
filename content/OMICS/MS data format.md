---
OMICS: "[[L7 Proteomics data analysis]]"
---
#startingpoint 
The data produced by the Instrument, although vendor specific, has some standards. The text format mzML is one example of a format, that looks similar to html and stores the data as well as metadata about the platform used. This enables backtracking of the data to the instrument and the techniques used, but also often ends up in large file sizes. The structure of the file is also quite complex and isn't readable without decoding.![](content/Attachments/KIMN20_data_analysis_270742404%202.png)
## Results
The results of the MS run are normally stored in a text table, where each roe represents a protein/protein group with associated abundance values. **MaxQuant** is a package, that allows to view this data, besides the already mentioned values it also shows the associated genes, the number of proteins (of the protein group) and the peptides that were detected for that group. The actual intensities are also shown.

---
Created: 2024-12-13 14:08
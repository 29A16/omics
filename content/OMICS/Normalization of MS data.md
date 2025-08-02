---
OMICS: "[[L7 Proteomics data analysis]]"
---
To compare the [[MS data format|data]] between runs, and enable detection of the underlying biological cause, the data has to be normalized.
The assumption, made for the normalization, is that the total amount of protein is similar between different sample groups.![](content/Attachments/KIMN20_data_analysis_270742404.png)
All the samples in the second measurement are higher in this example. When normalizing for the total amount of sample, we see, that there is no difference in the distribution of proteins between the samples.
## Complex data
When we consider more complex data, more complex normalization strategies are necessary, like **Global LOESS**. Here, we assume, that the median of the different samples should be similar. This assumption might not be usable for all cases, and normalization strategies therefore differ between experiments.![](content/Attachments/KIMN20_data_analysis_270742404%201.png)
Actual differences between runs might be completely overlooked, if the data is not normalized

---
Created: 2024-12-13 14:26
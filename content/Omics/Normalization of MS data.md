---
OMICS: "[[1 Inbox/Archive/Omics 1/L7 Proteomics data analysis]]"
---
To compare the [[MS data format|data]] between runs, and enable detection of the underlying biological cause, the data has to be normalized.
The assumption, made for the normalization, is that the total amount of protein is similar between different sample groups.
![[KIMN20_data_analysis_270742404.pdf#page=12&rect=54,114,915,349|KIMN20_data_analysis_270742404, p.12]]
All the samples in the second measurement are higher in this example. When normalizing for the total amount of sample, we see, that there is no difference in the distribution of proteins between the samples.
## Complex data
When we consider more complex data, more complex normalization strategies are necessary like **Global LOESS**. Here, we assume, that the median of the different samples should be similar. This assumption might not be usable for all cases, and normalization strategies therefore differ between experiments.
![[KIMN20_data_analysis_270742404.pdf#page=13&rect=93,117,837,416|KIMN20_data_analysis_270742404, p.13]]
Actual differences between runs might be completely overlooked, if the data is not normalized

---
Created: 2024-12-13 14:26
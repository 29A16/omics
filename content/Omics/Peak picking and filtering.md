---
OMICS: "[[L10  Metabolomics - Data handeling]]"
---
[[Steps in data processing (MS)]]
The peaks can either be picked with **bin-based analysis** or **peak-based methods**. 
The first method defines *bins*/regions on the time axis by which to separate the peaks. This is mostly used for NMR data and runs the risk of correctly identifying multiple peaks in close proximity to each other.
Peak based methods require pre set parameters, like peak hight, width or area. If the parameters are set correctly the identification can be automated.

The filtering of peaks is concerned with the identification of false positives. To exclude these, the threshold for including peaks is set by their abundance in the whole dataset. Common thresholds for false positives are peaks, that are only found in less than 50% or less than 75% of the samples. 
Low intensity signals that represent chemical or electronic noise are also removed.

---
Created: 2024-12-21 16:26
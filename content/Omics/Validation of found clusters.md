---
OMICS: "[[1 Inbox/Archive/Omics 1/L7 Proteomics data analysis]]"
---
To find out whether the difference between the [[Clustering|clusters]] was found by chance or represents a difference in biology, statistical validation is necessary. The simplest approach to determine if the difference between two groups is statistically relevant is the use of a **t-test**. If the amount of groups is more than two **ANOVA** tests are the better choice for a statistical test. T-test and ANOVA assume normal distribution and therefore often requires prior logarithmic transformation of the data. Both assign the probability of the detected difference stemming from chance with a **p-value**. When the amount of clusters, that are compared are increased, a set p-value is not sufficient anymore (when e.g. standard value of 5%, we would expect a false positive of 1 out of 20 samples) and an **adjusted p-value** (p-corr) or **False Discovery Rate (FDR)** is used instead.

---
Created: 2024-12-20 09:52
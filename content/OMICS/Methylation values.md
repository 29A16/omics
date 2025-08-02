---
OMICS: "[[L4 Epigenomics]]"
---
When measuring multiple cells, the question of methylation isn't binary (there is also a deviation due to an imperfect bisulfate conversion). Therefore, the signal produced after measurement with [[Bisulfate conversion#Infinium Bead Technology|infinium bead technology]] is converted into a ratio of two signals, one from the methylated locus and one from the unmethylated locus. This ratio is the $\beta$-value, to adjust for low signals the Constance $\alpha$ is also added.
$$
\beta = \frac{M}{M+U+\alpha}
$$
Another way to express this is the M-value, which utilizes log transformation instead of absolute values
$$
M_{val} = \log_2{\frac{M+\alpha}{U+\alpha}}
$$
Both values can be used to in further statistical analysis to determine the methylation of the sample

---
Created: 2024-12-10 09:37
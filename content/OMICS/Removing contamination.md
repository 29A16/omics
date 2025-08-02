---
OMICS: "[[L2 Denovo Assambly]]"
---
There is always a trade off between excluding actual contamination and possibly loosing relevant data, which is highly dependent on the project, analysis method and database used for comparison.
In general, contaminating sequences can be removed, after identifying the specific sequence with [[Blast;Kaiju]], aligning the reads to the contaminating sequences and then filtering out the reads that align.

As mentioned above, this can cause over filtering, which might not be of relevance if specific sequences are looked at in the project but could be critical for a meta-genomic project.

---
Created: 2024-11-27 10:03
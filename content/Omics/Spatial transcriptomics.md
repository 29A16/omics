---
OMICS: "[[L12 Spatial omics]]"
---
[[Spatial omics]]
## Image based
Specific mRNA sequences expressed by the cells are identified with a hybridization probe, has anneals to the transcript with one part of its structure, while the other part is free for identification by another (secondary) probe. As in the spatial proteomics procedures, the process oh hybridization and signal detection is repeated multiple times.
An alternative to the hybridization probe is a padlock probe, that gets elongated after hybridization via rolling circle mechanism. The elongated sequence contains multiple copies of motifs recognized by the secondary probe, enabling signal amplification.![[Spatial_omics_lecture_slides_2024.pdf#page=18&rect=38,41,883,286|Spatial_omics_lecture_slides_2024, p.18]]This method has a single molecule resolution but only limited plexity (100-1000 primary probes). It also takes a long time to generate the image and requires cell segmentation.
## Sequence based - Visium
Arrayed spots are used to capture the mRNA of lysed cells. The resolution is determined by the beads capturing the transcripts and can go up to a single cell resolution. It is also possible to get a whole transcriptome readout. This is possible, because the mRNA is not captured sequence specific but by their 3' poly-A tail.
The probe on the array consists of a spatial bar code, that is unique for the location on the chip, allowing mapping of the transcripts. Besides the poly(dT) tail (to capture the poly-A mRNA) it also carries a Unique Molecular Identifier (UMI) to filter out multiple copies and correct errors during sequencing.
![[Spatial_omics_lecture_slides_2024.pdf#page=21&rect=50,29,934,300|Spatial_omics_lecture_slides_2024, p.21]]
The workflow follows these steps:
1. Fixation of tissue is stained and then applied to the microarray
2. Enzymatic preperation releases the mRNA and lets it bind to the probes
3. Reverse transcription 
4. The cDNA with spacial bar code is then sequenced, providing information on the transcription profile at the location of the sample.
A big advantage of Visium is its compatibility with Formalin-fixated paraffin embedded (FFPE) tissue, which is the standard for preserving tissue. In reality this is a limited advantage, since RNA is unstable and degrades over time.

---
Created: 2024-12-22 18:42
---
OMICS: "[[L12 Spatial omics]]"
---
[[Analysis of spatial data]]
To extract meaningful information from the generated image and the [[Cell type annotation|annotated cells]], the amount of cells in a region and their distance is used in **spatial statistics**.
>[!cite]- G-function
>The G-function gives information on the distance between cells of different types. Can give information on clustering and distribution of cells
![[Spatial_omics_lecture_slides_2024.pdf#page=44&rect=11,34,467,294|Spatial_omics_lecture_slides_2024, p.44]]
>

>[!cite]- K-function
>The K-function gives information on the abundance of cells of one cell population within a radius of cells from another population
![[Spatial_omics_lecture_slides_2024.pdf#page=44&rect=473,24,915,298|Spatial_omics_lecture_slides_2024, p.44]]
>

>[!cite]- Moran's Index
>Measures the clustering/distribution of a specific cell type
![[Spatial_omics_lecture_slides_2024.pdf#page=45&rect=383,0,939,449|Spatial_omics_lecture_slides_2024, p.45]]
>

>[!cite]- Nearest neighbour distance
>Identification of the nearest neighbour by distances to cell types
![[Spatial_omics_lecture_slides_2024.pdf#page=46&rect=30,5,930,438|Spatial_omics_lecture_slides_2024, p.46]]
>

>[!cite]- Shannon index
>Measure of cell type richness.
![[Spatial_omics_lecture_slides_2024.pdf#page=49&rect=516,212,956,450|Spatial_omics_lecture_slides_2024, p.49]]
>

>[!cite]- Simpson index
> Assigns a probability, of two cells interacting with each other/clustering with each other.
![[Spatial_omics_lecture_slides_2024.pdf#page=49&rect=59,0,498,312|Spatial_omics_lecture_slides_2024, p.49]]
> 

Besides these statistical values a graphical analysis can also be conducted, where cells are treated as nodes and the distance between them as edges. Machine learning predicts interactions and clusters that are then mapped back onto the tissue sample (Image --> segmentation --> graph)

---
Created: 2024-12-23 17:19
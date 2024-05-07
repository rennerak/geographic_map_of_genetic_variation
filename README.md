# Chromosome 22: Creating a Geographic Map of Genetic Variation

This project is inspired by the study titled [Genes mirror geography within Europe](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2735096/) by Novembre *et al.* and similarly aims to uncover the influence of ancestry on genotype and population data from chromosome 22 downloaded from the [The International Genome Sample Resource](https://www.internationalgenome.org/).

## Rationale:
Studies have demonstrated that genetic variants can differ significantly between populations, reflecting ancestral genetic differences. This correlation has implications for understanding disease susceptibility, treatment response, and population health disparities.

## Research Objective:
This project attempts to assess the correlation of genetic variation with genetic ancestry via:
- parsing data from human chromosome 22 and an associated population data panel
- running dimensionality reduction to assess correlation via geographic map
- dimensionality reduction will include PCA and tSNE and the effectiveness of PCA will be evaluated
  
## Results:
The analysis of genetic variants on human chromosome 22, collected from the 1000 Genomes Project, reveals distinct clustering based on patient ancestry, with European and American ancestries showing significant overlap. Thus the findings from this project support the results from Novembre *et al.*. 
Regarding evaluation of PCA effectiveness,  principal component 1 exhibits greater variation than principal component 2, however both components hold relatively low proportions of variance (8.25% and 5% respectively), suggesting limited effectiveness in dimensionality reduction. Therefore, to enhance analysis in future projects, considering additional principal components may provide valuable insights.


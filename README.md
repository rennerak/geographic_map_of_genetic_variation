# Chromosome 22: Creating a Geographic Map of Genetic Variation

This project is inspired by the study titled [Genes mirror geography within Europe](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2735096/) by Novembre *et al.* and similarly aims to uncover the influence of ancestry on genotype and population data from chromosome 22 downloaded from the [The International Genome Sample Resource](https://www.internationalgenome.org/). Additionally, the project follows, where applicable, the amazing and helpful instructions from the bioinformatics youtube channel [OMGenomics](https://www.youtube.com/@OMGenomics). 

## Rationale:
Studies have demonstrated that genetic variants can differ significantly between populations, reflecting ancestral genetic differences. This correlation has implications for understanding disease susceptibility, treatment response, and population health disparities.

## Research Objective:
This project attempts to assess the correlation of genetic variation with genetic ancestry via:
- parsing data from human chromosome 22 and an associated population data panel
- running dimensionality reduction to assess correlation via geographic map
- dimensionality reduction will include PCA and tSNE and the effectiveness of PCA will be evaluated

## Tools & Languages used
- WSL Ubuntu for downloading and screening Chr.22 data
- Python on Linux for using Unix-built packages (i.e. pysam) and creating matrix [see here for the code](vcf_to_matrix.py). The matrix is a representation of the genotype data, where rows correspond to samples and columns correspond to variants.
- running PCA on [Jupyter Notebook](geographic_map_of_genetic_variation.ipynb) using Python on Windows
  
## Results:
Delving into genetic variants on human chromosome 22, sourced from the 1000 Genomes Project, uncovers fascinating patterns of patient ancestry. Notably, European and American ancestries exhibit intriguing overlaps, echoing the insights gathered by Novembre *et al.*.
Assessing the efficacy of principal component analysis (PCA) reveals intriguing dynamics. Principal component 1 exhibits greater variation than principal component 2, however both components hold relatively low proportions of variance (8.25% and 5% respectively), suggesting limited effectiveness in dimensionality reduction. Looking ahead, increasing the number of principal components might enrich future analyses with deeper insights. Furthermore, as the dataset was subsetted to increase time efficiency, analyzing the whole data of chromosome 22 will prove to provide more nuanced perspectives.


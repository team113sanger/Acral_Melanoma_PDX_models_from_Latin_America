# Acral Melanoma - PDX models from Latin America

This repository serves as the central landing page for multiple sub-analyses related to the manuscript:

> **_Comprehensive molecular and functional characterization of brazilian acral melanoma reveals aberrant genetic landscape and therapeutic vulnerabilities_**

The analyses were conducted by several authors in the Possik, Robles-Espinoza and Adams groups. Each sub-analysis repository linked below contains its own **README.md** with details of the methods, code, and data required for reproducing the results. Large files and figures from the paper can be accessed at the corresponding [FigShare for the project]()

Users can download any datasets from Figshare with: 
```
curl -k -o bundle.zip https://figshare.com/ndownloader/articles/MY_NUMARTICLE/versions/1
unzip bundle.zip
```

## Project Overview

| Sub-analysis | Directory | Authors | Links | Checklist? |
|--------------|-----------|---------|-------|------------|
| MesKit analysis of acral melanoma  samples | `MesKit` |(<jb62@sanger.ac.uk>) | [GitHub repository](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_MesKit) [Zenodo DOI Badge](#) | ❌ |
| Genomic hailstorm analysis of acral melanoma samples | `Hailstorm` | (<af31@sanger.ac.uk>) | [GitHub repository](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_Hailstorm) [Zenodo DOI Badge](#) | ❌ |
| Molecular and functional profiling of acral melanoma samples | `Heatmap_figures` | (<af31@sanger.ac.uk>) | [GitHub repository](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_Heatmap_Figures) [Zenodo DOI Badge](#) | ❌ |
| Filtering, processing, counting and QC analysis of the RNAseq sequencing data | `RNAseq` | (<mdc1@sanger.ac.uk>) | [GitHub repository](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_RNAseq) [Zenodo DOI Badge](#) | ❌ |
| Filtering, processing, counting and QC analysis of the WES DNA sequencing data | `WES` | (<mdc1@sanger.ac.uk>) <jb62@sanger.ac.uk> | [GitHub repository](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_WES) [Zenodo DOI Badge](#) | ❌ |


## Author checklist
As the author of a sub-analysis, I have checked the following:
- [ ] a README.md with a short description of the analysis
- [ ] a README.md which explains how to run my scripts
- [ ] a README.md which explains how I install dependencies (if _renv_ or _poetry_, a link to their documentation)
- [ ] a README.md that explains something about my **input data** (what directory? or if figshare, a link?)
- [ ] a repository without licensed data (e.g. nothing from COSMIC)
- [ ] an APGL3 LICENSE file
- [ ] a tag for my repository (e.g. `1.0.0`)
- [ ] a Zenodo DOI and badge

See [Checklist Google Sheet](https://docs.google.com/spreadsheets/d/1UMCJjRy7vWmuTq3qGdkLeqAc6xG7Co7YrJq9wKTADXU/edit?gid=0#gid=0) for more tracking progress.

## Project Overview (old format)

~~The sub-analyses of the project, authors who performed them and repositories they correspond to are:~~  
- ~~Transcriptome analysis of PDX models from Latin America: `PDX_models_from_Latin_America_RNAseq` [![DOI](https://zenodo.org/badge/MYPAPER.svg)](https://doi.org/) (mdc1@sanger.ac.uk) ~~
- ~~Somatic calling of SNVs, MNVs,and INDELs from WES of PDX models from Latin America: `PDX_models_from_Latin_America_WES` [![DOI](https://zenodo.org/badge/MYPAPER.svg)](https://doi.org/) (mdc1@sanger.ac.uk) ~~

## Contact 
- Annie Cristhine Sousa Squiavinato (<as81@sanger.ac.uk>)
- Antonio Facciolo (<af31@sanger.ac.uk>)
- Patricia Basurto Lozada (<pbasurto@liigh.unam.mx>)
- Martin Del Castillo Velasco-Herrera (<mdc1@sanger.ac.uk>)
- Jesús René Wong (<rene.wong@helsinki.fi>)
- Jacqueline Boccacino (<jb62@sanger.ac.uk>)
- David J Adams (<da1@sanger.ac.uk>)
- Carla Daniela Robles-Espinoza(<drobles@liigh.unam.mx>)
- Patricia Possik (<ppossik@inca.gov.br>)

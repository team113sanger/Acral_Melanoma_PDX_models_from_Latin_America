# Acral Melanoma - PDX models from Latin America

This repository serves as the central landing page for multiple sub-analyses related to the manuscript:

> **_Comprehensive molecular and functional characterization of brazilian Acral Melanoma reveals aberrant genetic landscape and therapeutic vulnerabilities_**

The analyses were conducted by several authors in the Possik, Robles-Espinoza and Adams groups. Each sub-analysis repository linked below contains its own **README.md** with details of the methods, code, and data required for reproducing the results. Large files and figures from the paper can be accessed at the corresponding [FigShare for the project](https://figshare.com/account/home#/projects/249119).

Users can download any datasets from Figshare with: 

```bash
curl -k -o bundle1.zip https://figshare.com/ndownloader/files/54688241
curl -k -o bundle2.zip https://figshare.com/ndownloader/files/54607436
unzip bundle1.zip
unzip bundle2.zip
```

## Project Overview
| Sub-analysis                                                                         | Directory & Authors                                             | GitHub                                                                                                                                                                          | DOI                                                                                                         |
|--------------------------------------------------------------------------------------|-----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| MesKit analysis of Acral Melanoma samples                                            | `MesKit`<br>(<jb62@sanger.ac.uk>)                               | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_MesKit)             | [Zenodo DOI Badge](#)                                                                                       |
| Genomic hailstorm analysis of Acral Melanoma samples                                 | `Hailstorm`<br>(<af31@sanger.ac.uk>)                            | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_Hailstorm)          | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16324433.svg)](https://doi.org/10.5281/zenodo.16324433) |
| Molecular and functional profiling of Acral Melanoma samples                         | `Heatmap_figures`<br>(<af31@sanger.ac.uk>)                      | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_Heatmap_Figures)    | [![DOI](https://zenodo.org/badge/987703042.svg)](https://doi.org/10.5281/zenodo.16324717)                   |
| Filtering, processing, counting and QC analysis of the transcriptome sequencing data | `RNAseq`<br>(<mdc1@sanger.ac.uk>)                               | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_RNAseq)             | [Zenodo DOI Badge](#)                                                                                       |
| Somatic calling of SNVs, MNVs, and INDELs from WES DNA sequencing data               | `WES`<br>(<mdc1@sanger.ac.uk>)<br>(<jb62@sanger.ac.uk>)         | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_WES)                | [Zenodo DOI Badge](#)                                                                                       |
| Generation of BAGEL essentiality scores for cell lines in DepMap (24Q4)              | `DepMap_Resource`<br>(<jb63@sanger.ac.uk>)                      | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/acral_melanoma_depmap_pancaner_resource)            | [Zenodo DOI Badge](#)                                                                                       |
| DepMap analysis of Acral Melanoma samples                                            | `DepMap`<br>(<rf17@sanger.ac.uk>)                               | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_DepMap)             | [Zenodo DOI Badge](#)                                                                                       |
| CRISPR driven analysis of shared vulnerabilities in Acral Melanoma cell lines        | `Crispr_Shared_Hits`<br>(<rf17@sanger.ac.uk>)                   | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_Crispr_Shared_Hits) | [Zenodo DOI Badge](#)                                                                                       |
| Multiple different analyses of Acral Melanoma samples                                | `Mixed_analyses`<br>(<annie.sousa@ensino.inca.gov.br>)          | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_mixed_analyses)                  | [Zenodo DOI Badge](#)                                                                                       |
| Figures for somatic calling                                                          | `Somatic_calling_figures`<br>(<annie.sousa@ensino.inca.gov.br>) | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_Somatic_Calling_Figures)             | [Zenodo DOI Badge](#)                                                                                       |
| CNA, STAR-Fusion and Signature analysis of Acral Melanoma samples                    | `CNA_Fusions_Signatures`<br>(<rene.wong@helsinki.fi>)           | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/JReneWong/AcralMelanoma_CNVs-FusionTranscripts-MutSigns)          | [Zenodo DOI Badge](#)                                                                                       |
| Single cell RNA sequencing analysis of Acral Melanoma samples                        | `SingleCell_RNAseq`<br>(<pedrosodrerb@gmail.com>)               | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/Pedrosrb/scRNA_analysis)                                          | [Zenodo DOI Badge](#)                                                                                       |

## Author checklist
As the author of a sub-analysis, I have checked the checklist below. This block & the checklist column will be removed once all items are completed.

See [Checklist Google Sheet](https://docs.google.com/spreadsheets/d/1UMCJjRy7vWmuTq3qGdkLeqAc6xG7Co7YrJq9wKTADXU/edit?gid=0#gid=0) for more tracking progress.

## Contact 
- Annie Cristhine Sousa Squiavinato (<annie.sousa@ensino.inca.gov.br>)
- Antonio Facciolo (<af31@sanger.ac.uk>)
- Patricia Basurto Lozada (<pbasurto@liigh.unam.mx>)
- Martin Del Castillo Velasco-Herrera (<mdc1@sanger.ac.uk>)
- Jesús René Wong (<rene.wong@helsinki.fi>)
- Jacqueline Boccacino (<jb62@sanger.ac.uk>)
- Jamie Billington (<jb63@sanger.ac.uk>)
- Rafaela Fagundes (<rf17@sanger.ac.uk>)
- Rene Wong Ramirez (<rene.wong@helsinki.fi>)
- Pedro Sodré (<pedrosodrerb@gmail.com>)
- David J Adams (<da1@sanger.ac.uk>)
- Carla Daniela Robles-Espinoza(<drobles@liigh.unam.mx>)
- Patricia Possik (<ppossik@inca.gov.br>)

## EGA Access to Data
The data used in this project is available at the European Genome-phenome Archive (EGA).

| EGA Accession ID | Description | Sequence Type | Xenofiltered? |
|------------------|-------------|----------------|----------------|
| EGAS00001005663  | PDX models from Latin America | Whole Exome | No |
| EGAS00001008150  | PDX models from Latin America | RNAseq | No |
| EGAS00001008230  | CRISPR Screening of Brazilian Acral Melanoma Cell Lines | CRISPR KO | No |
| EGAS00001008231  | PDX models from Latin America | Whole Exome | Yes |
| EGAS00001008232  | PDX models from Latin America | RNAseq | Yes |

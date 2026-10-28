# Modelling Acral Melanoma in Admixed Brazilians Uncovers Genomic Drivers and Targetable Pathways

This repository serves as the central landing page for multiple sub-analyses related to the manuscript:

> **_Modelling Acral Melanoma in Admixed Brazilians Uncovers Genomic Drivers and Targetable Pathways_**

The analyses were conducted by several authors in the Possik, Robles-Espinoza and Adams groups. Each sub-analysis repository linked below contains its own **README.md** with details of the methods, code, and data required for reproducing the results. Large files and figures from the paper can be accessed at the corresponding [FigShare for the project](https://doi.org/10.6084/m9.figshare.34745433).


Users can download our dataset from Figshare with: 

```bash
curl -fL -o segments.zip 'https://api.figshare.com/v2/articles/34745433/versions/1/download?folder_path=segments'
unzip segments.zip
```

## Cloning all submodules

This repository contains multiple submodules for each sub-analysis. To clone all submodules, use the following command:

```bash
git clone --recurse-submodules https://github.com/team113sanger/Acral_Melanoma_PDX_models_from_Latin_America.git
```


## Project Overview
| Sub-analysis                                                                         | Directory & Authors                                             | GitHub                                                                                                                                                                          | DOI                                                                                                         |
|--------------------------------------------------------------------------------------|-----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| MesKit analysis of Acral Melanoma samples                                            | `MesKit`<br>(<jb62@sanger.ac.uk>)                               | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_MesKit)             | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16326172.svg)](https://doi.org/10.5281/zenodo.16326172)                                                                                       |
| Genomic hailstorm analysis of Acral Melanoma samples                                 | `Hailstorm`<br>(<af31@sanger.ac.uk>)                            | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_Hailstorm)          | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16324433.svg)](https://doi.org/10.5281/zenodo.16324433) |
| Molecular and functional profiling of Acral Melanoma samples                         | `Heatmap_figures`<br>(<af31@sanger.ac.uk>)                      | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_Heatmap_Figures)    | [![DOI](https://zenodo.org/badge/987703042.svg)](https://doi.org/10.5281/zenodo.16324717)                   |
| Filtering, processing, counting and QC analysis of the transcriptome sequencing data | `RNAseq`<br>(<mdc1@sanger.ac.uk>)                               | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_RNAseq)             | -                                                                                       |
| Somatic calling of SNVs, MNVs, and INDELs from WES DNA sequencing data               | `WES`<br>(<mdc1@sanger.ac.uk>)<br>(<jb62@sanger.ac.uk>)         | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_WES)                | -                                                                                       |
| Generation of BAGEL essentiality scores for cell lines in DepMap (24Q4)              | `DepMap_Resource`<br>(<jb63@sanger.ac.uk>)                      | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/acral_melanoma_depmap_pancaner_resource)            | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16328795.svg)](https://doi.org/10.5281/zenodo.16328795)                                                                                       |
| DepMap analysis of Acral Melanoma samples                                            | `DepMap`<br>(<rf17@sanger.ac.uk>)                               | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_DepMap)             | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16326204.svg)](https://doi.org/10.5281/zenodo.16326204)                                                                                     |
| CRISPR–Cas9 Screens with pyCROQUET Processing and BAGEL Essentiality Inference           | `Crispr_Screens`<br>(<im13@sanger.ac.uk>)                   | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/acral_melanoma_genome_wide_crispr_screens)              | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17507856.svg)](https://doi.org/10.5281/zenodo.17507856)                                                                                       |
| CRISPR driven analysis of shared vulnerabilities in Acral Melanoma cell lines        | `Crispr_Shared_Hits`<br>(<rf17@sanger.ac.uk>)                   | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_models_LatAm_Crispr_Shared_Hits) | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16328904.svg)](https://doi.org/10.5281/zenodo.16328904)                                                                                       |
| Multiple different analyses of Acral Melanoma samples                                | `Mixed_analyses`<br>(<annie.sousa@ensino.inca.gov.br>)          | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_PDX_mixed_analyses)                  | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16412634.svg)](https://doi.org/10.5281/zenodo.16412634)                                                                                       |
| Figures for somatic calling                                                          | `Somatic_calling_figures`<br>(<annie.sousa@ensino.inca.gov.br>) | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/team113sanger/Acral_Melanoma_Somatic_Calling_Figures)             | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16412888.svg)](https://doi.org/10.5281/zenodo.16412888)                                                                                       |
| CNA, STAR-Fusion & Signature analysis of Acral Melanoma samples                    | `CNA_Fusions_Signatures`<br>(<rene.wong@helsinki.fi>)           | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/JReneWong/AcralMelanoma_CNVs-FusionTranscripts-MutSigns)          | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16412737.svg)](https://doi.org/10.5281/zenodo.16412737)                                                                                       |
| Single cell RNA sequencing analysis of Acral Melanoma samples                        | `SingleCell_RNAseq`<br>(<pedro.barros@ensino.inca.gov.br>)               | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/Pedrosrb/scRNA_analysis)                                          | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16412785.svg)](https://doi.org/10.5281/zenodo.16412785)                                                                                      |
| Genetic ancestry analysis of Acral Melanoma samples using PCA and ADMIXTURE          | `Genetic_ancestry`<br>(<isimonin@liigh.unam.mx>)               | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/CGBio-Lab/Acral_Melanoma_PDX_Ancestry)                                          | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23553257.svg)](https://doi.org/10.5281/zenodo.23553257) |
| Differential expression & splicing analysis following SF3B4 depletion | `Splicing`<br>(<monica.salinas@crg.eu>) | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white)](https://github.com/msalpe/Acral_Melanoma_Cell_Lines_Splicing_Analysis) | - |

## Contact 
- Annie Cristhine Sousa Squiavinato (<annie.sousa@ensino.inca.gov.br>)
- Antonio Facciolo (<af31@sanger.ac.uk>)
- Patricia Basurto Lozada (<pbasurto@liigh.unam.mx>)
- Irving Simonin (<isimonin@liigh.unam.mx>)
- Martin Del Castillo Velasco-Herrera (<mdc1@sanger.ac.uk>)
- Ishan Mehta (<im13@sanger.ac.uk>)
- Jesús René Wong (<rene.wong@helsinki.fi>)
- Jacqueline Boccacino (<jb62@sanger.ac.uk>)
- Monica Salinas Pena (<monica.salinas@crg.eu>)
- Jamie Billington (<jb63@sanger.ac.uk>)
- Rafaela Fagundes (<rf17@sanger.ac.uk>)
- Rene Wong Ramirez (<rene.wong@helsinki.fi>)
- Pedro Sodré (<pedro.barros@ensino.inca.gov.br>)
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

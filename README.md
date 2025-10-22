Host Biomarker Discovery for Tuberculosis Treatment Response
====================================================================================================================================
## Paper Title
### Using a consensus machine learning approach to identify host biomarkers associated with treatment response in pulmonary tuberculosis

## Overview
### This repository contains the complete code base for the paper presenting a consensus machine learning framework to identify host-derived biomarkers predictive of treatment response in pulmonary tuberculosis. The analysis integrates multiple feature selection methods, machine learning models, and validation strategies to establish robust biomarker signatures.

## Key Features
### Multi-method feature selection (Boruta, LASSO, Decision Trees, XGBoost)
### Ensemble machine learning modeling (Random Forest, XGBoost, Decision Trees, LASSO)
### Comprehensive validation framework (cross-validation, external datasets)
### Consensus analysis across feature selection methods
### Public dataset validation using GEO datasets
## Data Availability
### Primary Dataset: MS.csv - Host expression data with treatment response labels
### Public Validation Datasets: GSE89403, GSE40553 from GEO database
## Installation & Requirements
### R Environment
#### R version ≥ 4.1.0
### Required R Packages
#### Package	Version
#### caret	7.0.1	
#### randomForest	4.7.1.2	
#### xgboost	1.7.11.1	
#### rpart	4.1.23	
#### glmnet	4.1.10	
#### Boruta	9.0.0	
#### e1071	1.7.16	
#### pROC	1.18.5	
#### PRROC	1.4	
#### ROCR	1.0.11	
#### limma	3.62.2	
#### GSVA	2.0.5
#### GSEABase	1.68.0	
#### Biobase	2.66.0	
#### tidyverse	2.0.0
#### reshape2	1.4.4	
#### ggplot2	3.5.1	
#### pheatmap	1.0.12	
#### kableExtra	1.4.0
#### readxl	1.4.3	
#### parallel	4.4.0	
#### doParallel	1.0.17
#### irr	0.84.1	
#### psych	2.5.6	
#### reportROC	3.6	
#### pacman	0.5.1	
#### OptimalCutpoints	1.1.5	
#### party	1.3.18	
#### rpart.plot	3.1.3	
#### partykit	1.2.24	
#### cowplot	1.1.3	

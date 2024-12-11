# Dominance and Independence within Bacterial Transcriptional Regulation

This repository contains the codes and data for the manuscript 'Dominance and Independence within Bacterial Transcriptional Regulation'.

## Repository Structure

````
Bacterial_TRN_Dominance_and_Independence/
├── README.md
│
├── Data/
│   ├── RegulonDB_v13_08042024/ #E.coli experimental TRN from RegulonDB v13
│   ├── mg1655/ #E.coli K-12 MG1655 genomic information
│   └── p1k/ #PRECISE-1K dataset
│
├── Data_Prep_Notebooks/
│   ├── Create_P1K_Merged.ipynb #Calculate exploratory metrics for all the genes
│   └── Create_RegulonDB_TRN.ipynb #Convert RegulonDB information to presence matrix
│
├── 1_Compare_Inference_Methods/
│   ├── Presence_Matrices/ # Gene presence/absence matrices for all the evaluated methods
│   ├── Results/ # Original Output from all the evaluated methods
│   ├── 1_Matrix_Deomposition_sklearn.ipynb
│   ├── 1.1_Run_InfoMax_and_Picard_ICA.ipynb
│   ├── 1.2_Run_FLAME.ipynb
│   ├── 2_Create_gene_presence_matrices.ipynb
│   ├── 3_Compare_matrix_factorization.ipynb
│   ├── 4_Compare_Performances_PyModulon_Optimized.ipynb
│   ├── 5_Exp_Var_all_methods.ipynb
│   ├── 6_High_MI_PCs.ipynb
│   ├── 6.1_High_MI_NMF.ipynb
│   ├── 7_Compare_GENIE3_Clutering_Biclustering.ipynb
│   └── 8_Benchmark_Clustering_Biclustering.ipynb
│
├── 2_Expression_Survey/
│   ├── Gene_Category/ # Figure 3 Gene Category
│   ├── 0_Import_Data.ipynb
│   ├── 1_Expression_Survey.ipynb
│   ├── 2_Find_the_Best_Split.ipynb
│   ├── 3_Decision_Tree.ipynb
│   ├── 4_Case_Study_Plotting.ipynb
│   └── 5_Genes_captured_by_ICA.ipynb
│
├── 3_Regulator_Survey/
│   ├── data/
│   └── notebooks/
│       ├── 1_compare_all_methods.ipynb
│       ├── 2_regulator_captured_sunburst.ipynb
│       └── 3_reg_size_boxplot.ipynb
│
├── 4_Case_Study/
│   ├── Figure_4_ArgR.ipynb
│
├── 5_Co_expression_confidence/
    ├── A_confidence_P1K.ipynb
    └── A_confidence_case_study_plotting.ipynb
````

## Datasets

All the datasets analyzed in this study have been deposited in this repository.

You could also explore and download the PRECISER-1K dataset from https://imodulondb.org/dataset.html?organism=e_coli&dataset=precise1k

## Environment Setup

Two environments were used in this study:

1. python 3.7 'modulome' from https://github.com/SBRG/iModulonMiner
   - pymodulon 0.2.1
   - scikit-learn 1.0.2
   - matplotlib 3.5.3
   - numpy 1.21.6
   - pandas 1.3.5
   - seaborn 0.12.2

2. python 3.12.4
   - scikit-learn 1.5.1
   - matplotlib 3.8.4
   - numpy 2.0.0
   - pandas 2.2.2
   - seaborn 0.13.2

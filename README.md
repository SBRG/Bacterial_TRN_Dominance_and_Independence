# Dominance and Independence within Bacterial Transcriptional Regulation

This repository contains code and data for the manuscript 'Dominance and Independence within Bacterial Transcriptional Regulation'.

## Repository Structure

````
```plaintext
Bacterial_TRN_Dominance_and_Independence/
├── README.md
├── Data/
│   ├── RegulonDB_v13_08042024/ #E.coli experimental TRN from RegulonDB v13
│   ├── mg1655/ #E.coli K-12 MG1655 genomic information
│   └── p1k/ #PRECISE-1K dataset
├── Data_Prep_Notebooks/
│   ├── Create_P1K_Merged.ipynb #Calculate exploratory metrics for all the genes
│   └── Create_RegulonDB_TRN.ipynb #Convert RegulonDB information to presence matrix
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
│   ├── 8_Benchmark_Clustering_Biclustering.ipynb
├── 2_Expression_Survey/
│   ├── Rat data/
├── 3_Regulator_Survey/
│   ├── Rat data/
├── 4_Case_Study/
│   ├── Rat data/
├── 5_Co_expression_confidence/
│   ├── Rat data/

```
````


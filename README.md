# TCGA-Analysis

This project explores the inhibitory effects of fasting on Epithelial to Mesenchymal Transition (EMT) using RACIPE and Genome Scale Metabolic Modeling. This analysis was part of a summer internship study conducted at IISC, Bangalore.

## Overview

The primary goal of this study was to understand how fasting affects the EMT process in breast cancer cell lines. EMT is a crucial process in cancer metastasis, and understanding its regulation can provide insights into potential therapeutic strategies.

## Methodology

### 1. RACIPE (Random Circuit Perturbation)
RACIPE was used to model the gene regulatory networks involved in EMT. This approach helps in understanding the dynamic behavior of the gene regulatory circuits under different conditions, such as fasting.

### 2. Genome Scale Metabolic Modeling (GSMM)
GSMM was used to reconstruct context-specific metabolic models based on the categorized cell lines. This involved using the 76gs score to segregate breast cancer cell lines into epithelial, mesenchymal, and hybrid states.

### 3. 76gs Score Calculation
The 76gs score is based on 76 genes identified to be associated with EMT. The steps involved are:
- Selecting common genes from the 76-gene list and the TCGA HiSeq FPKM database.
- Determining weights using Pearson’s coefficient.
- Calculating each cell line’s 76gs score using these weights.

### Data
- **Source**: TCGA HiSeq FPKM database
- **Cell Lines**: Breast cancer cell lines categorized into epithelial, mesenchymal, or hybrid states.

## Files

- `project e2.ipynb`: Jupyter notebook containing the analysis and code for the project.

## Results

The results of this study provide insights into the effects of fasting on EMT in breast cancer cell lines. The categorization of cell lines using the 76gs score enabled the reconstruction of context-specific metabolic models, which can be used for further studies on therapeutic interventions.



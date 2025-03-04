# Tissue-Driven-Metabolic-Specialization-in-Mononuclear-Phagocytes-An-ImmGen-Based-Analysis

## Overview
This repository contains a replication analysis of **large-scale ImmGen transcriptomic data** focusing on **mononuclear phagocytes (MNPs)** across various **tissues and cell types**. The project applies **Principal Component Analysis (PCA) and Uniform Manifold Approximation and Projection (UMAP)** to investigate how tissue environments shape immune cell metabolism.

## Key Features
- **PCA and UMAP visualizations** for both **cell types** (dendritic cells, macrophages, monocytes, microglia) and **tissue types** (e.g., liver, lung, brain, spleen).
- **Dimensionality reduction techniques** to identify dominant metabolic trends in MNPs.
- **Color-coded clustering analyses** to highlight transcriptional similarities and metabolic specialization.
- **R scripts for reproducibility**, including preprocessing, visualization, and interpretation.

## Repository Structure
📂 **/data/** → Processed ImmGen dataset (GSE122108) and metadata.  
📂 **/scripts/** → R Markdown scripts for PCA and UMAP analysis.  
📜 **PCA_cell_type.Rmd** → PCA analysis of gene expression data across cell types.  
📜 **PCA_tissue_type.Rmd** → PCA analysis of gene expression data across tissue types.  
📜 **UMAP_cell_type.Rmd** → UMAP visualization of MNPs based on cell type.  
📜 **UMAP_tissue_type.Rmd** → UMAP visualization of MNPs based on tissue type.  
📜 **README.md** → This document.  

## Installation & Dependencies
To run the analyses, ensure you have **R** and the following packages installed:

```r
install.packages(c("ggplot2", "data.table", "stats", "umap", "hrbrthemes", "RColorBrewer"))
```

## Results & Insights
- **PCA findings:** Tissue-specific metabolic constraints strongly influence clustering, with distinct metabolic signatures in liver, brain, and lung MNPs, while dendritic cells exhibit separate clustering due to their specialized immune roles.
- **UMAP findings:** Preserves local structure, revealing finer metabolic subclusters and highlighting the metabolic plasticity of macrophages and the unique metabolic signature of microglia.
- **Systems Immunology Perspective:** This analysis supports the hypothesis that tissue-driven metabolic adaptation is the dominant factor shaping MNP function, with additional contributions from cell-type-intrinsic metabolic programs.

# JnJ-Comparative-Evalutation-of-Tools-for-scRNA-seq-Analysis
## Introduction

This project aims to compare various advanced tools for analyzing single-cell/ single-nuclie RNA sequencing data. Given the complexity of biological data, it is crucial to evaluate and determine the most suitable tool for specific datasets. This comparison will involve a detailed assessment of each tool's algorithms, performance, and compatibility with complex biological data to identify the optimal solution for scRNA-seq/snRNA-seq analysis. We evaluate the computational efficiencies and function versatility of Scanpy in Python and Seurat in R.

## Data

This project utilized the biological data i.e. single cell RNA sequencing or single nucleus RNA sequencing data. As the data contain two million four 
hundred eighty thousand nine hundred fifty-six cells from brain Atlas project from cellxgene Census. We are planning to use all neuron dataset from brain 
that contain 10 tissues.
Link: https://cellxgene.cziscience.com/collections/283d65eb-dd53-496d-adb7-7570c7caa443

## Result

Our findings reveal that Leiden and Louvain-based Phenograph clustering in Scanpy produced more biologically relevant and consistent clusters. We also leveraged scCATCH for automated annotation but faced limitations due to the lack of human brain reference datasets, highlighting the need for advanced annotation tools and expanded references about human brain in the future. Importantly, we found that Scanpy outperformed Seurat in handling large datasets in most cases, offering superior computational efficiency and functional versatility for high-dimensional scRNA-seq analysis. 


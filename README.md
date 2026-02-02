# WCGNA--WEIGHTED-GENE-COEXPRESSION-NETWOK-ANALYSIS
This repository contains an R-based workflow integrating RNA-seq normalization, differential gene expression (DEG) analysis, and Weighted Gene Co-expression Network Analysis (WGCNA) to identify high-confidence chlorantraniliprole resistance–associated genes 
Overview of the Analysis Pipeline

RNA-seq Count Data and Sample Metadata Preparation

Experimental Design: Strain and Treatment Classification

Variance Stabilizing Transformation (VST) for Network Analysis

Differential Gene Expression Analysis Using DESeq2

Identification of Resistance-Associated DEGs

Gene Filtering Based on Variance and Quality Control

Sample Clustering and Outlier Detection

Soft-Threshold Power Selection for Scale-Free Network Topology

Construction of Signed Weighted Gene Co-expression Network

Module Detection and Dynamic Tree Cutting

Module Color Assignment and Dendrogram Visualization

Eigengene Calculation and Eigengene Clustering


Module–Trait Relationship Analysis for Resistance Phenotype

Selection of Top Resistance-Associated Modules

Calculation of Module Membership (kME) and Gene Significance (GS)

Identification of Hub Genes Across All Modules

High-Confidence Hub Gene Identification in Blue Module

High-Confidence Hub Gene Identification in Turquoise Module

Integration of Differential Expression and Network Hub Genes

Visualization of Module Membership vs Gene Significance
Identification of Final Resistance-Associated Candidate Genes
Topological Overlap Matrix (TOM) Construction
Extraction of High-Confidence Subnetworks
Network Export for Cytoscape Visualization

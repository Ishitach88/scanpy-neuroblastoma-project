# scanpy-neuroblastoma-project
“Analysis of single-cell neuroblastoma data using Scanpy
# Scanpy Neuroblastoma Project

This project explores single-cell RNA sequencing data using the Scanpy library to analyze neuroblastoma samples.

## File
- `Scanpy_Neuroblastoma.ipynb`: Main Jupyter notebook containing the analysis.

## Tools Used
- Python
- Scanpy
- Anndata
- Seaborn/Matplotlib




About the project  High performance cloud computing Project 

🧠 Scanpy Neuroblastoma Single-Cell Analysis
This project explores how gene expression changes in neuroblastoma cells when the MYCN oncogene is knocked down. Using Scanpy and single-cell RNA sequencing (scRNA-seq) data, I analyzed two samples—one with MYCN knockdown and one control—to understand how MYCN affects cellular behavior at the transcriptomic level.

📁 Project Overview
Dataset: Public GEO data

GSM4979213: MYCN knockdown

GSM4979214: Control sample

Goal: To identify how MYCN silencing impacts gene expression and cell populations in neuroblastoma

🔧 Tools & Technologies
Scanpy, Anndata, Seaborn, Matplotlib

Data preprocessing with gzip and pandas

All analysis done in a single Jupyter Notebook

🔬 What I Did
📥 Loaded scRNA-seq data from compressed .tsv.gz files

🧹 Filtered out low-quality cells, including those with high mitochondrial gene content

📊 Normalized and log-transformed the data for clean visualization

🔎 Used PCA and UMAP to visualize the cellular landscape

🧩 Clustered cells using the Louvain algorithm to uncover subpopulations

🧬 Identified differentially expressed genes (DEGs) between knockdown and control groups

🌟 Key Findings
The MYCN knockdown clearly altered the transcriptional profile of neuroblastoma cells.

UMAP plots showed distinct separation between the knockdown and control groups.

Specific gene signatures emerged in knockdown cells, hinting at changes in pathways related to cell cycle, differentiation, and stress response.

💡 Next Steps
Add gene ontology (GO) analysis to uncover enriched biological processes

Visualize key marker genes across clusters

Test the pipeline with additional replicates for stronger validation

🙋‍♀️ About Me
I’m Ishita Chopra, a graduate student exploring the intersection of computational biology and disease research. This project was part of my hands-on learning with single-cell transcriptomics and Python-based analysis tools. chopraishita40@gmail.com , phn- 5712594890

single cell analysis -scanpy pipline 

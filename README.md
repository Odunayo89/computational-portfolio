# 🧬 Cloud-Enabled Computational Biology Portfolio
RNA-seq and single-cell RNA-seq workflows using AWS EC2/S3, DESeq2, Seurat, and Scanpy.

## Projects


### 1. Cloud-Based RNA-seq Differential Expression Pipeline
https://github.com/Odunayo89/cloud-rnaseq-deseq2-pipeline
- Uploaded RNA-seq count data to AWS S3
- Pulled data into AWS EC2 Linux environment
- Created biological metadata design matrix
- Installed and configured Bioconductor packages on EC2
- Performed DESeq2 differential expression analysis
- Applied adjusted p-value and fold-change thresholds
- Generated PCA and heatmap visualizations
- Exported significant DEG results
- Stored outputs in reproducible cloud project structure

---

### 2. RNA-seq DESeq2 Analysis
https://github.com/Odunayo89/deseq2-analysis  
- Differential expression analysis using DESeq2  
- Bulk RNA-seq pipeline  

---

### 3. PBMC3K Single-cell Analysis
https://github.com/Odunayo89/pbmc3k-singlecell-analysis-  
- scRNA-seq analysis using Seurat  
- Clustering and cell type identification  

---

### 4. PBMC10K Seurat Workflow
https://github.com/Odunayo89/pbmc10k-singlecell-seurat-  
- Advanced single-cell workflow  
- QC → normalization → clustering → markers

---

### 5. PBMC3K Scanpy Workflow
https://github.com/Odunayo89/pbmc3k-single-cell-rnaseq-scanpy-analysis
- scRNA-seq analysis using Scanpy
- QC → normalization → clustering → markers

---

### 6. Benchmarking scRNA-seq Annotation Methods on PBMC 10k
https://github.com/Odunayo89/Benchmarking-scRNA-seq-Annotation-Methods-on-PBMC-10k
- QC and filtering
- Normalization and log transformation
- PCA and UMAP
- Leiden clustering
- Manual marker-based annotation
- Automated annotation with CellTypist
- K-means clustering
- Benchmarking using ARI and silhouette score

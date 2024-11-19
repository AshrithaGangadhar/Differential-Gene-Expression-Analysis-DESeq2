# Differential Gene Expression Analysis Using DESeq2

To identify differentially expressed genes across different experimental conditions (e.g., tumor vs. non-tumor) in RNA-seq datasets of uterine leiomyosarcoma using a statistical software package (DESeq2).


## **Contents**

- `data/`: Contains raw data files such as the counts matrix and metadata.
- `scripts/`: R scripts used to perform DGE analysis and generate plots.
- `results/`: Processed results, including output tables and visualizations.
- `README.md`: Documentation for the project.


## **Requirements**

### **Software and Tools**
- **R**: Version 4.0 or higher
- **RStudio**: Optional but recommended

### **R Packages**
The following R packages are required:
- `DESeq2`: For differential expression analysis
- `ggplot2`: For creating plots and visualizations
- `pheatmap`: For heatmap generation
- `dplyr`: For data manipulation
- `RColorBrewer`: For color palettes

Install the packages using the following commands in R:
```R
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install("DESeq2")
install.packages(c("ggplot2", "pheatmap", "dplyr", "RColorBrewer"))

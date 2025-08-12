# IDH-Mutant Gliomas: Cell-of-Origin Discovery

This repository contains the code and data used for the research paper by *Park et al.*, **"IDH-mutant gliomas arise from glial progenitor cells harboring the initial driver mutation."**

Our study, published in [Journal Name], provides the first direct evidence that IDH-mutant gliomas originate from glial progenitor cells (GPCs), including oligodendrocyte progenitor cells (OPCs). We used advanced deep sequencings (droplet digital PCR, deep panel sequencing, and targeted amplicon sequencing), single-cell RNA sequencing, and spatial transcriptomics to trace the origin of these tumors, offering new insights into their development and potential therapeutic targets.

### Paper Link
Title: IDH-mutant gliomas arise from glial progenitor cells harboring the initial driver mutation

Journal: pending

Link: pending (This section will be updated upon publication.)



## Project Overview
This repository is dedicated to the integrative analysis of spatial transcriptomicsa data from patient brain tissues and single-cell RNA sequencing data from a novel mouse model to investigate the cellular origin of IDH-mutant gliomas.

### Our key goals were:

* To identify the specific cell type in patient-derived normal brain tissues that carries the initial driver mutation.

* To validate our human tissue findings using a genetically engineered mouse model.

### Key Findings
Our analysis revealed several crucial insights:

- **Initial Driver Mutation:** We detected a low-level *IDH1* mutation without any other drivers in the peritumoral cortex of a significant portion of patients (37.9%), suggesting that the initial driver mutation is the *IDH* mutations.

- **Clonal Evolution:** Our genetic analysis showed a clear evolutionary link between these peritumoral mutant cells and the tumor cells, indicating a common ancestor.

- **Cell-of-Origin:** We determined that ***glial progenitor cells (GPCs), including oligodendrocyte progenitor cells (OPCs)***, are the cell types that acquire this initial mutation.

- **Mouse Model Validation:** A novel mouse model, created by introducing glioma-driving mutations into OPCs, successfully reproduced key features (histological & transcriptional) of human IDH-mutant gliomas, confirming our findings.


## Getting Started
To run the analysis code, please set up your environment with the necessary dependencies.

### Environment Setup
This project was developed and tested using Python 3.9.

### Data
The raw data for this study, including spatial transcriptomics from patient-derived brain (peritumoral cortex) and single-cell RNA sequencing data from our murine IDH-mutant glioma, is available at the following location:

- SRA (Sequence Read Archive): PRJNA1149448 (deep sequencing data)

- GEO (Gene Expression Omnibus): GSE275791 and GSE302642 (single-cell RNA sequencing data & spatial transcriptomics data)

### Reproducing Results
You can reproduce the key figures and results from our paper by running the Jupyter Notebooks (e.g. xenium_final_ver2.ipynb) in the specified order.

1. Ensure all dependencies are installed.

2. Download and place the raw data in the appropriate directory as specified in the notebooks.

3. Open the notebooks in your preferred environment (e.g., VS Code, Jupyter Lab) and execute the cells sequentially.

## Contact
For any questions or feedback regarding the code or analysis, please contact:

- Jung Won Park, M.D., Ph.D.: parkjw88 at gmail.com or parkjw88 at kaist.ac.kr

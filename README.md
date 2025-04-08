# README

# Acute Myeloid Leukemia Heatmap Analysis

This repository contains an RNA-seq analysis pipeline for studying gene expression patterns in Acute Myeloid Leukemia (AML) samples. The analysis focuses on identifying and visualizing gene expression clusters across different AML treatment conditions.

## Overview

This analysis uses RNA-seq data from 19 AML model mice samples 
, comparing gene expression patterns across different treatment conditions. The pipeline implements hierarchical clustering and heatmap visualization using the 
 package 
.

## Requirements

### R Packages

* 
: For clustering and heatmap visualization
* 
: For data manipulation using pipe operators
* 
: For reading TSV files
* 
: For data manipulation
* 
: For data frame operations

### Data Requirements

* RNA-seq expression data (TSV format)
* Sample metadata (TSV format)
* R version 4.0 or higher

## Directory Structure

The analysis expects the following folder structure:

```markdown
project_root/
├── data/
│   └── SRP070849/
│       ├── SRP070849.tsv      # Gene expression data
│       └── metadata_SRP070849.tsv  # Sample metadata
├── plots/
│   └── aml_heatmap.png       # Output heatmap
└── results/
    └── top_90_var_genes.tsv   # Filtered gene data
```

## Analysis Pipeline

1. 


2. 


3. 


## Usage

1. Clone the repository
2. Install required R packages
3. Place data files in the correct directory structure
4. Run the R notebook to generate the heatmap

## Output

The analysis produces:



## Citation

This analysis uses data from Shih et al., 2017 
 and was adapted from the refine.bio examples repository 
.

## Contributing

Contributions are welcome. Please submit pull requests with:


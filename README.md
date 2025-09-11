# Expression Quantitative Trait Locus (eQTL) Analysis of ATP1B4 with Genome-Wide Association Study (GWAS)
This study aims to conduct a eQTL analysis using whole genome sequencing dataset to identify genetic variants associated with ATP1B4 expression adjusted with age and sex.

# Study Design
1. Materials and Methods
This study utilize whole genome sequencing data with variants across all chromosomes.

**Data Source:**
I.  GWAS.gds
II. GENESIS_final_pheno.csv

2. Statistical Analysis
Caucasian participants were selected for the analysis. A null model was first generated to investigate the baseline effect on outcome variable by family variables. The summary of null model will be passed to statistical model with genentic variants to identify associated SNPs with ATP1B4 expression. The statistical model was further adjusted with age and sex to analyze potential confounding effect.

    * Null model: 
    ATP1B4 = β0 

    * Full model
    ATP1B4 = β0 + β1 ∙ SNP + β2 ∙ age + β3 ∙ sex

# Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Configuration](#configuration)
- [Contact](#contact)

## Installation

```bash
# Example installation steps
git clone https://github.com/clu89/PWAS_UKB.git
cd ("PWAS_UKB")
```
```r
## Install required packages manually, e.g:
install.packages("GENENSIS")
## Install other packages if necessary
```

## Usage

```bash
## Install R first
Module load R
Rscript PWAS_UKB.R
```

## Features

## Output

## Configuration

## Contact
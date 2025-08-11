# miRNA-LCH-Predictor
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Description
Machine learning bioinformatics project predicting associations between miRNAs and Langerhans Cell Histiocytosis (LCH). Includes genomic preprocessing, feature selection, Random Forest & XGBoost models, plus pathway and GO analysis to interpret key miRNAs and uncover LCH molecular mechanisms.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Methods](#methods)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Overview
This project applies machine learning to identify potential associations between microRNAs (miRNAs) and Langerhans Cell Histiocytosis (LCH). Understanding these associations can help researchers uncover disease mechanisms and identify potential biomarkers for diagnosis or targeted therapy.

## Dataset
- **Samples**: 29 total  
  - 15 Control  
  - 14 LCH patients
- **Source**: [GEO Database - GSEXXXXX]
- **Preprocessing**:  
  - Normalization  
  - Missing value handling  
  - Log transformation

## Methods
1. **Data Preprocessing**: Cleaning, normalization, and transformation of miRNA expression data.
2. **Feature Selection**: Identification of the most relevant miRNAs using statistical and model-based methods.
3. **Machine Learning Models**:  
   - Random Forest  
   - XGBoost  
4. **Biological Interpretation**: Pathway and Gene Ontology enrichment analysis for significant miRNAs.

## Results
- Achieved high accuracy in predicting LCH-associated miRNAs.
- Identified top miRNAs with potential biological significance.
- Highlighted key pathways involved in disease progression.
- 
<img width="1187" height="708" alt="miRNA_contribution" src="https://github.com/user-attachments/assets/4c6644fd-7541-4f21-a422-14c8b6e29b80" />

<img width="1920" height="1440" alt="top_miRNAs" src="https://github.com/user-attachments/assets/eef340d3-c0fa-4ef4-9719-df3d25168d5e" />

## Installation
```bash
git clone https://github.com/yusufharb/miRNA-LCH-Predictor.git
cd miRNA-LCH-Predictor
pip install -r requirements.txt

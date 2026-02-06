# Exploratory Analysis of Serum BDNF in Healthy Controls, MDD and Schizophrenia #
## 1. Background
- Brain-Derived Neurotrophic Factor (BDNF) central role in neuronal survival, synaptic plasticity, and learning and memory.

- Changes in peripheral BDNF levels have been reported in several psychiatric disorders, including Major Depressive Disorder (MDD) and schizophrenia.

- Findings heterogeneous -> influenced by demographics, age, sex and more factors.

## 2. Project Motivation
This small, exploratory project aims to:

- pratice data-driven analysis in neuroscience and digital medicine
- gaining experience working with (clinical biomarker) data
- gaining experience working with statistical workflows

The project is purely intended as a learning exercise.

It does **NOT** aim to:

- make any sort of causal claims
- discover new biomarkers or make any clinical recommendations

## 3. Research Question
**How do serum BDNF protein concentrations differ across diagnostic groups (healthy controls, MDD, schizophrenia), and how are these differences influenced by basic demographic variables?**

## 4. Dataset
This project uses a publicly available dataset containing:

- serum BDNF protein concentration
- diagnostic group (control, MDD, schizophrenia)
- age, sex, BMI
- BDNF Val66Met genotype

Details on dataset origin, license, and preprocessing are provided in data/README.md

## 5. Analysis Strategy
This project follows an **exploratory and descriptive approach**, focusing on:

- distributional characteristics of serum BDNF
- group-level comparisons
- associations between BDNF and demographic variables
- simple regression modeling to account for potential confounders

Key steps:

- Description and visualization
- Group-wise comparison
- Linear regression models adjusting for age, sex and BMI
(- Additionally: Exploratory examination of genoytype effects)

## 6. Methods Overview
- Programming language: Python
- Libraries: pandas, numpy, matplotlib, seaborn, statsmodels

## 7. Limitations
Among others:

- Medication status and disease duration are not available
- Peripheral BDNF may not directly reflext central nervous system levels
- Sample size limits statistical power

# Insurance Coverage and Lung Cancer Diagnosis Analysis

This repository contains the code and data for analyzing the impact of insurance coverage on lung cancer diagnosis rates in the United States. The analysis aims to provide insights into healthcare access and its influence on lung cancer outcomes.

## Table of Contents

1. [Introduction](#introduction)
2. [Data](#data)
3. [Methodology](#methodology)
4. [Results](#results)
5. [Conclusion](#conclusion)
6. [Repository Structure](#repository-structure)
7. [Acknowledgments](#acknowledgments)

## Introduction

Lung cancer ranks as the second leading cause of death in the United States, necessitating effective strategies for prevention and early detection. Access to healthcare coverage, particularly post-Affordable Care Act (ACA), is crucial for improving screening efforts and reducing disparities. This analysis investigates the relationship between insurance coverage and lung cancer diagnosis rates to inform policy interventions.

## Data

The data utilized for the analysis include datasets sourced from the National Health Interview Survey (NHIS), containing information on demographics, insurance coverage, and lung cancer diagnosis from 2000 to 2018. Additionally, supplementary datasets provide context and relevant variables for the analysis.

## Methodology

The methodology involves rigorous statistical analysis, including data preprocessing, matching techniques to balance the dataset, and linear probability regression analyses with controls. Causal inference techniques are employed to ensure meaningful results.

## Results

The results of the analysis reveal a consistent positive correlation between insurance coverage and the likelihood of receiving a lung cancer diagnosis across all time periods. The implementation of the ACA strengthened this relationship, indicating the importance of healthcare access in detecting and managing cancer.

## Conclusion

Sustained efforts to improve and expand health insurance coverage are crucial for enhancing lung cancer detection and management nationwide. Targeted interventions aimed at enhancing access to screening and detection services can mitigate disparities and improve public health outcomes.

## Repository Structure

- **00_Resources:** Contains documentation related to the NHIS dataset.
- **01_Data:** Includes raw and processed datasets used for analysis.
  - **COPD.csv:** Dataset containing information on Chronic Obstructive Pulmonary Disease.
  - **after_Obamacare.csv:** Dataset containing information on insurance coverage post-ACA.
  - **before_Obamacare.csv:** Dataset containing information on insurance coverage pre-ACA.
  - **insurance_data_cleaned.csv:** Cleaned dataset with relevant variables.
  - **nhis.csv.zip:** Compressed NHIS dataset.
- **02_Code:** Contains Jupyter notebooks and scripts for data cleaning, exploratory analysis, matching techniques, regression analysis, and other analyses.
  - **Exploratory Analysis:** Folder containing notebooks for exploratory data analysis.
  - **restructured:** Folder containing notebooks for matching and regression analysis.
- **README.md:** Main README file providing an overview of the repository.

## Acknowledgments

We acknowledge the National Health Interview Survey (NHIS) for providing the dataset used in this analysis. Special thanks to all contributors and researchers who have contributed to the understanding of lung cancer and healthcare access.

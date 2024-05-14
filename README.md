# CS_403_Machine_Learning_project

This repository hosts the source code and documents for the CS 403 course project. In this project, different SVM variants are trained and tested on five Keel datasets - binary class imbalanced datasets. Support Vector Machine (SVM), Least Squares Support Vector Machine (LSSVM), and Improved Density-based Least Squares Support Vector Machine with Class-Imbalanced Learning (IDLSSVM-CIL) are compared with and without the utilization of oversampling & undersampling techniques. Additionally, we will evaluate the effectiveness of the different sampling methods discussed. Hence this github repo is the code implementation of the IDLSSVM-CIL algorithm proposed by [Hazarika et al](https://link.springer.com/article/10.1007/s00521-020-05240-8)

## Contents

1. **CS_403_inference_script.ipynb**: This notebook contains Python code to obtain test result parameters using different KEEL datasets, sampling methods, SVM variants, and the corresponding hyperparameters.
2. **CS_403_generate_results.ipynb**: This notebook contains Python code to generate a CSV result file for all the five KEEL datasets, under and over-sampling methods, SVM variants, and their respective parameters.
3. **IDLSSVM-CIL_Calculation.pdf**: This document elucidates the calculations for IDLSSVM-CIL's fit and predict functions.
4. **project_proposal.pdf**: The project proposal as submitted on 26th March 2024.
5. **project_report.pdf**: The project report as submitted on 2nd May 2024.
6. **project_results.csv**: This CSV file serves as a template to generate results and is used in CS_403_generate_results.ipynb.
7. **results_table_and_plots.xlsx**: An Excel sheet containing all the analysis, including tables and plots of the results obtained.
8. **keel_datasets**: This folder contains the .dat files of the five imbalanced KEEL datasets as used in the Density-weighted SVM for binary class imbalance learning (DSVM-CIL) paper ([link](https://link.springer.com/article/10.1007/s00521-020-05240-8)).

All code notebooks include instructions on how to run them properly. The above resources are also uploaded [here](https://drive.google.com/drive/folders/1dQugKuL-zx1mXT4NcWCNCz1W2tdqMYRR?usp=drive_link).

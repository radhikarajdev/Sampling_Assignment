# Sampling_Assignment
**Sampling Assignment**: Balancing and Evaluating Machine Learning Models
This repository contains the solution for the Sampling Assignment. The code focuses on balancing an imbalanced dataset, creating samples using various sampling techniques, and evaluating different machine learning models on these samples.

## The primary objectives of this project are:
Balance an imbalanced dataset using SMOTE.
Generate five samples using the following sampling techniques:
Simple Random Sampling
Systematic Sampling
Stratified Sampling
Cluster Sampling
Random Undersampling
Train five machine learning models (e.g., Random Forest) on these samples and evaluate their performance.
Identify the best-performing model for each sampling technique.
Save the results in CSV files for further analysis.


## Dataset
The dataset used for this project is the Creditcard_data.csv. It contains credit card transaction records, including a binary classification for detecting fraudulent transactions.

### Imbalanced Nature: 
The dataset has a significant class imbalance, making it ideal for sampling experiments.

### Techniques Used
**Balancing the Dataset**:
Used **SMOTE** (Synthetic Minority Oversampling Technique) to handle class imbalance.


## Sampling Techniques:
Simple Random Sampling: Randomly selects a subset of the dataset.
**Systematic Sampling**: Selects every kth record from the dataset.
**Stratified Sampling**: Ensures class proportions are maintained in the sample.
**Cluster Sampling**: Divides the dataset into clusters and samples entire clusters.
**Random Undersampling**: Reduces the size of the majority class to match the minority class.


## Evaluation:
Accuracy was used as the metric to compare model performance across different samples.


### Outputs:
**sampling_results.csv**: Contains the accuracy of all models for each sampling technique.
**top_models.csv**: Lists the top-performing model and accuracy for each sampling method.

### Results
**The results of the evaluation are saved in CSV files**:
**sampling_results.csv**: All accuracies sorted for each sampling technique.
**top_models.csv**: Best-performing model for each sampling technique.

### Files in the Repository
**SamplingAss.ipnyb**: The main Python script containing the implementation.
**Creditcard_data.csv**: Dataset used for the analysis (ensure it's added manually if not included).
**sampling_results.csv**: Output file with all model accuracies.
**top_models.csv**: Output file with the top-performing models for each sampling technique.
**README.md**: This file.

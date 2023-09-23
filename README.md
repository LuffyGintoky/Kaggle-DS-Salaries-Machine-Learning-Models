# Job Title Categorization for Data Science

## Overview

This machine learning project aims to classify job titles in the field of data sciences based on various features such as salary, location, company size, job type, and more. The project is divided into two main Jupyter notebooks: one for Exploratory Data Analysis (EDA) and another for Feature Engineering and Modeling.

## Dataset

The dataset used for this project contains job postings with associated features. Initially, the classification task focuses on distinguishing between the two most common job categories: "Data Scientist" and "Data Engineer." Due to a significant class imbalance in the dataset, we employed various sampling techniques to address this issue.

## Notebooks

1. **EDA Notebook:** This notebook explores the dataset, visualizes key statistics, and provides insights into the distribution of job titles and features.

2. **Feature Engineering and Modeling Notebook:** In this notebook, we preprocess the data, engineer relevant features, and build classification models. We employed four different algorithms:
   - Logistic Regression
   - k-Nearest Neighbors (KNN)
   - Support Vector Machine (SVM)
   - Random Forest

## Sampling Techniques

To address the class imbalance, we experimented with the following sampling regimes:
1. Original Dataset
2. Random Upsampling
3. Random Undersampling
4. Synthetic Minority Over-sampling Technique (SMOTE)
5. Synthetic Upsampling using Conditional Text Generation Adversarial Neural Networks (CTGANN)

## Future Directions

The project's future direction is to enrich the dataset with more features and data to enable classification among a broader range of job titles within the data science field. Additionally, we plan to explore advanced modeling techniques, fine-tune hyperparameters, and improve the model's overall performance.


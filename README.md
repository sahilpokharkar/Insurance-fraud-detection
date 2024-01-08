# Insurance Fraud Detection

## Overview
This project aims to detect fraudulent activities in insurance transactions using machine learning techniques. The dataset used contains information related to credit transactions, merchant details, and other associated factors.

## Preprocessing
- The dataset is loaded using Pandas from the 'MedicalFraud1.csv' file.
- Data preprocessing steps involve cleaning date-time columns and scaling numerical features using MinMaxScaler.
- Label encoding is applied to categorical columns for model compatibility.

## Data Visualization
- Matplotlib and Seaborn are used for data visualization.
- Visualizations include histograms, bar plots, box plots, and correlation heatmaps to explore data distributions, relationships, and correlations.

## Model Training and Evaluation
- Three machine learning models are used: Logistic Regression, Decision Tree, and Naive Bayes.
- The models are trained and evaluated using accuracy scores, confusion matrices, and classification reports.
- Train-test splitting is performed for model validation.

## Example Input Data
- An example input data format is provided for testing the trained models.
- It showcases the required format and features for making predictions.
- Three trained models (Logistic Regression, Decision Tree, Naive Bayes) are used to predict fraud or authenticity based on the input data.

## Usage
1. Clone the repository.
2. Ensure the necessary libraries and dependencies are installed.
3. Use the provided dataset or replace it with your own dataset.
4. Modify the preprocessing steps as needed.
5. Train models and evaluate their performances.
6. Use the trained models to predict fraud based on new input data.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn


## Overview
This repository contains the implementation of my **CM2604 Machine Learning coursework**. The goal of this project is to predict whether a client will subscribe to a term deposit based on the Bank Marketing Dataset from the UCI Machine Learning Repository. The project involves building and comparing two machine learning models:
1. **Neural Networks**
2. **Random Forest Classifier**

## Project Structure

bank-marketing-ml
├── data/                 # Raw and processed datasets 
├── notebooks/            # Notebooks for data exploration, modeling, and evaluation
├── reports/              # Documentation, results, and other project-related files
├── README.md             # Main project description
├── requirements.txt      # List of Python dependencies

## Dataset
- **Source**: [UCI Machine Learning Repository - Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- The dataset contains information about:
  - **Features**: Client demographics, behavior, and campaign information (e.g., `age`, `job`, `marital`, `education`).
  - **Target**: Whether a client subscribed to the term deposit (`yes` or `no`).

## Steps
The project is divided into the following key steps:

1. **Data Preparation**
   - Handling missing values.
   - Encoding categorical variables.
   - Normalizing/standardizing numerical features.

2. **Model Development**
   - **Neural Networks**: Built using `TensorFlow/Keras`.
   - **Random Forests**: Implemented using `scikit-learn`.

3. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-score, AUC-ROC.
   - Visualization: Confusion matrix, ROC curves.

4. **Discussion**
   - Performance comparison.
   - Ethical considerations and potential limitations.

## Results
- The **Random Forest** model achieved a slightly higher F1-score compared to the Neural Network, but the Neural Network showed better performance on certain imbalanced metrics like recall.
- The final evaluation metrics are summarized below:
  - **Random Forest**:
    - Accuracy: `91%`
    - Precision: `89%`
    - Recall: `91%`
    - F1-Score: `90%`
    - AUC-ROC: `92`
  - **Neural Network**:
    - Accuracy: `90%`
    - Precision: `90%`
    - Recall: `90%`
    - F1-Score: `90%`
    - AUC-ROC: `92%`

## Getting Started
### Prerequisites
Ensure you have the following installed:
- Python 3.8 or above
- Jupyter Notebook
- Required Python libraries (see `requirements.txt`).





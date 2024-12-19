# Bank Marketing Machine Learning Project

This repository contains a Jupyter Notebook that applies machine learning techniques to analyze and predict outcomes related to a bank marketing dataset. The goal is to predict whether a customer will subscribe to a term deposit based on various features.

## Table of Contents

- Overview
- Dataset
- Project Structure
- Setup and Installation
- Key Steps
- Models Implemented
- Evaluation Metrics

## Overview
The project explores a marketing dataset to understand patterns and build predictive models. It includes the following:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model implementation and evaluation

## Dataset
The dataset contains information about customers contacted during a marketing campaign, with features such as age, job, marital status, education, contact method, and campaign details. The target variable indicates whether a customer subscribed to a term deposit (binary: 0 or 1).

## Project Structure
- Data Preprocessing: Handles missing values, encodes categorical variables, and scales numerical features.
- Exploratory Data Analysis (EDA): Visualizes data distributions, correlations, and key patterns.
- Feature Engineering: Selects and transforms features to improve model performance.
- Model Training and Evaluation: Implements machine learning models and evaluates their performance using key metrics.

## Setup and Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open `BankMarketing.ipynb` to run the analysis.

## Key Steps

1. Data Preprocessing:
   - Handled missing values.
   - Encoded categorical variables using one-hot encoding.
   - Scaled numerical features to improve model convergence.

2. Exploratory Data Analysis:
   - Visualized key features using histograms, box plots, and scatter plots.
   - Analyzed correlations to identify important relationships.

3. Feature Engineering:
   - Extracted meaningful features.
   - Removed redundant or less relevant features based on analysis.

4. Model Training and Evaluation:
   - Split the dataset into training, validation, and test sets.
   - Trained multiple machine learning models.
   - Compared model performance using evaluation metrics.

## Models Implemented
- Logistic Regression
- Decision Trees
- Random Forests
- Gradient Boosting (e.g., XGBoost)
- Support Vector Machines (SVM)

## Evaluation Metrics
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## License
This project is licensed under the MIT License. See the LICENSE file for details.


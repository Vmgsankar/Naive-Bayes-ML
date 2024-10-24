
# Naive Bayes Classification - Banking Dataset

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling Process](#modeling-process)
- [Results](#results)

## Overview
This project applies a **Naive Bayes Classification** model to predict whether a client will subscribe to a term deposit based on several features. The model uses a dataset from a banking institution, which contains details of various marketing campaigns.

## Dataset
The dataset used in this project can be found [here](https://raw.githubusercontent.com/gkrishna9790/Logistic-Regression-Binary-Classification/master/Archieve/banking.csv).

### Features in the Dataset:
- `age`: Age of the client.
- `job`: Type of job (e.g., admin, technician, etc.).
- `marital`: Marital status (married, single, divorced).
- `education`: Level of education.
- `default`: Has credit in default? (yes or no).
- `balance`: Average yearly balance.
- `housing`: Has a housing loan? (yes or no).
- `loan`: Has a personal loan? (yes or no).
- `contact`: Contact communication type (cellular, telephone, unknown).
- `day`: Last contact day of the month.
- `month`: Last contact month of the year.
- `duration`: Last contact duration, in seconds.
- `campaign`: Number of contacts performed during this campaign.
- `pdays`: Number of days since the client was last contacted.
- `previous`: Number of contacts performed before this campaign.
- `poutcome`: Outcome of the previous marketing campaign.
- `y`: Has the client subscribed to a term deposit? (yes or no).

## Dependencies
- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Vmgsankar/Naive-Bayes-ML
   ```
2. Navigate to the project directory:
   ```bash
   cd Naive-Bayes-ML
   ```

## Usage
1. Load the dataset using `pandas`.
2. Preprocess the data (e.g., handling missing values, encoding categorical features).
3. Split the dataset into training and test sets.
4. Train a Naive Bayes model using `scikit-learn`'s `GaussianNB` classifier.
5. Evaluate the model using appropriate metrics such as accuracy, precision, recall, and F1-score.
6. Plot confusion matrix and visualize feature importance.

## Results
- Achieved an accuracy of **X%** on the test dataset.
- Detailed results and analysis can be found in the project notebook.

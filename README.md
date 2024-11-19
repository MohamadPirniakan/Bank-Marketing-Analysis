# Bank Marketing Analysis Project

## Overview
This project focuses on predicting customer responses to bank marketing campaigns using machine learning techniques. The project encompasses data preprocessing, feature engineering, model training, and evaluation to optimize customer response predictions.

## Table of Contents
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Methodology](#methodology)
- [Dependencies](#dependencies)


## Installation
1. Clone this repository:
    ```
    https://github.com/MohamadPirniakan/Bank-Marketing-Analysis.git
    cd Bank-Marketing-Analysis
    ```

2. Create a virtual environment:
    ```
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```
    pip install -r requirements.txt
    ```

## Project Structure
The project consists of the following key files and directories:
- `data/`: Contains the bank marketing dataset.
- `notebooks/`: Jupyter notebooks for data analysis, preprocessing, feature engineering, and model training.
- `src/`: Source code files including feature engineering, preprocessing, and model training.
- `requirements.txt`: Contains necessary Python libraries and their versions.

## Methodology
The project leverages various data preprocessing and transformation techniques to prepare the dataset for machine learning. It applies categorical and target encoding, one-hot encoding, and categorization of numeric features. The main models used include Random Forest and Logistic Regression, validated through Grid Search and evaluated using classification metrics like ROC-AUC.

## Dependencies
Here is a list of required libraries:
```
pandas
numpy
matplotlib
seaborn
scikit-learn
category-encoders
tqdm

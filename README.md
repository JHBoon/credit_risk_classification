Credit Risk Prediction Model

## Overview
This project is part of the Data Analyst Bootcamp by the University of Irvine, focusing on supervised machine learning techniques. 

## Objective
Build a reliable machine learning tool for lenders to assess the risk of loans.

## Goal
Build a logistic regression model to predict the risk associated with loans, categorizing them into two classes: 
- **Class 0**: Healthy loans 
- **Class 1**: High-risk loans

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Tools Used](#tools-used)
- [Contributing](#contributing)

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/JHBoon/credit_risk_prediction.git
   cd Credit_Risk
   open credit_risk_classification.ipynb
Install the required packages:
pip install -r requirements.txt
Usage
To run the model, open the Jupyter Notebook file:

credit_risk_classification.ipynb
Data
The dataset used for this project is named lending_data. 
It includes various features related to loan applications, which are used to train the logistic regression model.

Model Evaluation
The model's performance is evaluated using the following metrics:

Recall for Class 0 (Healthy Loans): ~99.9%
F1 Score for Class 0: 1 (indicating perfect precision and recall)
Recall for Class 1 (High-Risk Loans): 91%
Misclassification Rate for Class 1: 15%
These metrics indicate that while the model performs exceptionally well in identifying healthy loans, there is room for improvement in the classification of high-risk loans.

Results
The model demonstrates strong predictive capabilities, particularly for healthy loans. Further tuning and validation may enhance its performance on high-risk loans.

Tools Used
This project utilized the following tools:
Python
Visual Studio Code (VSCode)
GitHub
Terminal
Xpert Learning Assistant Chat+
Chat GPT

Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss potential improvements.

Author: 
Jay Boon
https://www.linkedin.com/in/justboon/

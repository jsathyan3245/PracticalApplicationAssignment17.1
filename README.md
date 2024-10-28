# PracticalApplicationAssignment17.1

# Bank Marketing Prediction

## Overview
This project focuses on predicting whether clients will subscribe to a term deposit based on various demographic and behavioral factors from a bank marketing dataset. Multiple machine learning models were utilized to achieve the best predictive performance.

## Summary of Findings
In this analysis, four models were compared based on their training time, training accuracy, and test accuracy. The results are summarized in the table below:

| Model               | Train Time (seconds) | Train Accuracy | Test Accuracy |
|---------------------|----------------------|----------------|---------------|
| Logistic Regression  | 0.419235             | 0.911927       | 0.911265      |
| KNN                  | 0.023599             | 0.927709       | 0.900704      |
| Decision Tree        | 0.174611             | 1.000000       | 0.886380      |
| SVM                  | 9.606932             | 0.922671       | 0.911750      |

### Key Observations:
- The **Decision Tree** model achieved perfect training accuracy (1.000), but it showed a relatively lower test accuracy compared to Logistic Regression and SVM, indicating potential overfitting.
- **Logistic Regression** performed comparably well in terms of test accuracy while being efficient in training time.
- **KNN** exhibited the fastest training time but had a slightly lower test accuracy than Logistic Regression.
- The **SVM** model, while having good accuracy, took significantly longer to train compared to other models.

## Jupyter Notebook
The complete analysis can be found in the Jupyter notebook located in the `notebook` directory.

- [Analysis Notebook](notebook/analysis.ipynb)

## Data
The dataset used for this analysis is located in the `data` directory.

- **Dataset:** `bank-additional-full.csv`

## Results
Model performance metrics and additional visualizations are stored in the `results` directory.

## Installation
To replicate the analysis, ensure you have the necessary packages installed. You can do this by running:
```bash
pip install -r requirements.txt

# ConfusionFunction

## Description

The `ConfusionFunction` class calculates performance metrics for binary classifiers using the confusion matrix. Additionally, it generates error, ROC, and AUC curve plots for different classification thresholds.

## Features

- Calculation of metrics such as accuracy, precision, recall, F1 score, specificity, negative predictive value, false positive rate, false discovery rate, false negative rate, Cohen's kappa, and Jaccard index.
- Generation of error, ROC, and AUC curve plots.
- Printing of confusion matrix and associated metrics for different thresholds.

## Metrics Explained

### Accuracy
- **Formula**: \((TP + TN) / (TP + FP + TN + FN)\)
- **Description**: Measures the proportion of true results (both true positives and true negatives) among the total number of cases examined.

### Precision
- **Formula**: \(TP / (TP + FP)\)
- **Description**: Measures the proportion of positive results that are true positives (i.e., the accuracy of the positive predictions).

### Recall (Sensitivity)
- **Formula**: \(TP / (TP + FN)\)
- **Description**: Measures the proportion of true positives that are correctly identified by the model.

### F1 Score
- **Formula**: \(2 \cdot (Precision \cdot Recall) / (Precision + Recall)\)
- **Description**: The harmonic mean of precision and recall, providing a balance between the two.

### Specificity (True Negative Rate)
- **Formula**: \(TN / (TN + FP)\)
- **Description**: Measures the proportion of true negatives that are correctly identified.

### Negative Predictive Value (NPV)
- **Formula**: \(TN / (TN + FN)\)
- **Description**: Measures the proportion of negative results that are true negatives.

### False Positive Rate (FPR)
- **Formula**: \(FP / (FP + TN)\)
- **Description**: Measures the proportion of false positives among all negatives.

### False Discovery Rate (FDR)
- **Formula**: \(FP / (FP + TP)\)
- **Description**: Measures the proportion of false positives among all positive results.

### False Negative Rate (FNR)
- **Formula**: \(FN / (FN + TP)\)
- **Description**: Measures the proportion of false negatives among all positives.

### Cohen's Kappa
- **Formula**: \(\kappa = (po - pe) / (1 - pe)\)
  - \(po\) = observed agreement
  - \(pe\) = expected agreement by chance
- **Description**: A measure of inter-rater agreement that considers the agreement occurring by chance.

### Jaccard Index
- **Formula**: \(TP / (TP + FP + FN)\)
- **Description**: Measures the similarity between the predicted and actual classes.

## Installation

Clone this repository:

```bash
git clone https://github.com/mardenlelis/ConfusionFunction.git
cd ConfusionFunction

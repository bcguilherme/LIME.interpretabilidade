# LIME.interpretabilidade

# Breast Cancer Classification with Logistic Regression and LIME

This repository contains a Python script for classifying breast cancer data using Logistic Regression and explaining model predictions using LIME (Local Interpretable Model-Agnostic Explanations).

## Getting Started

To get started, you need to have Python installed and install the required packages. You can use the following command to install the necessary packages:

```bash
pip install scikit-learn lime matplotlib

Data Description
The breast cancer dataset is loaded from the scikit-learn library. A brief description of the dataset is printed, including the feature names and class names.

Data Splitting
The dataset is split into training and testing sets using the train_test_split function. The split is stratified to maintain class balance.

Logistic Regression Classifier
A Logistic Regression classifier is trained on the training data. The accuracy of the model is evaluated on both the training and testing datasets. Confusion matrices and classification reports are printed for model evaluation.

Model Explanation with LIME
LIME is used to explain the predictions made by the Logistic Regression model. A random instance from the testing data is selected, and LIME is used to provide an explanation for the model's prediction on this instance. The explanation is displayed in a Jupyter Notebook.

Exploring Incorrect Predictions
A random incorrect prediction is selected from the testing data, and LIME is used to explain the model's prediction on this instance. The explanation is displayed in a Jupyter Notebook.

Feature Importance Visualization
The feature importance (coefficients) of the Logistic Regression model is visualized using a bar plot. The importance of each feature in making predictions is shown.

Conclusion
This repository provides an example of using Logistic Regression for breast cancer classification and LIME for model interpretability. You can adapt this code for your own datasets and classification tasks.

License
This project is licensed under the MIT License - see the LICENSE file for details.

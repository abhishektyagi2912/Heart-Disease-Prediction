# Heart Disease Prediction using Logistic Regression

This is a machine learning project for predicting heart disease using logistic regression. The goal of this project is to create a model that can accurately predict whether a patient has heart disease or not based on their medical attributes.

## Dataset

The dataset used for this project is the Cleveland Heart Disease Database from the UCI Machine Learning Repository. It contains 303 instances with 13 medical attributes and 1 binary classification target variable (0 or 1 indicating whether the patient has heart disease or not).

## Dependencies
* Python 3.7+
* NumPy
* Pandas
* Scikit-learn
* Gradio

## Installation

You can install the required packages using pip:

```
pip install numpy pandas scikit-learn gradio
```

## Usage
To run the model, simply run the model.py script:
```
To run the model, simply run the heart_disease_prediction.py script:

```

This will train the logistic regression model on the dataset and launch a Gradio interface where you can input the medical attributes of a patient and get a prediction of whether they have heart disease or not.

The model is trained on 70% of the dataset and tested on the remaining 30%. The accuracy of the model is printed to the console.

## Gradio Interface
The Gradio interface allows you to easily input medical attributes for a patient and get a prediction of whether they have heart disease or not. You can adjust the input values using the sliders provided and the prediction will update in real-time.

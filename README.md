# Breast Cancer Outcome Prediction Using Machine Learning

This project explores the use of machine learning techniques to analyse breast cancer patient data and predict clinical outcomes. The work includes data cleaning, exploratory data analysis, classification modelling for mortality status, model evaluation, hyperparameter tuning, ensemble learning, and regression modelling for survival months.

The project was completed as part of a university machine learning coursework.

## Project Overview

The aim of this project was to apply machine learning methods to a breast cancer dataset and investigate whether patient and clinical features could be used to support outcome prediction.

The project focuses on two main tasks:

1. **Mortality status classification**  
   Predicting whether a patient belongs to the `Alive` or `Dead` mortality status class.

2. **Survival months regression**  
   Predicting survival months using a filtered dataset and regression modelling.

This project is for educational and portfolio purposes only. It is not intended for medical diagnosis or real-world clinical decision-making.

## Notebooks

The project is split across three notebooks:

### `Mourad_Ali_Notebook1.ipynb`

Focuses on data preparation and exploratory analysis.

Main tasks include:

- Loading the breast cancer dataset
- Inspecting numerical and categorical variables
- Removing unnecessary columns
- Checking missing values
- Detecting and removing selected outliers
- Filling missing values using mean imputation
- Encoding categorical variables
- Mapping mortality status into numerical labels
- Saving cleaned and filtered datasets for modelling

### `Mourad_Ali_Notebook2.ipynb`

Focuses on classification modelling for mortality status prediction.

Models used include:

- Logistic Regression
- K-Nearest Neighbours
- Naive Bayes

Evaluation methods include:

- Train-test split
- Accuracy score
- Confusion matrix
- Classification report
- ROC curve
- GridSearchCV for hyperparameter tuning

### `MouradMLCW_notebook3_.ipynb`

Focuses on more advanced modelling.

Main tasks include:

- Building a Voting Ensemble Classifier
- Combining Logistic Regression and K-Nearest Neighbours
- Evaluating ensemble performance
- Creating confusion matrices and classification reports
- Building a Decision Tree Regressor for survival months prediction
- Evaluating regression performance using MAE, MSE, and R²
- Visualising the decision tree model

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Scikit-learn
- Jupyter Notebook / Google Colab

## Machine Learning Methods

The project applies both classification and regression approaches.

### Classification

Classification models were used to predict mortality status. The models were evaluated using accuracy, confusion matrices, classification reports, and ROC curves.

Models included:

- Logistic Regression
- K-Nearest Neighbours
- Naive Bayes
- Voting Ensemble Classifier

### Regression

A Decision Tree Regressor was used to predict survival months from patient data. Regression performance was evaluated using:

- Mean Absolute Error
- Mean Squared Error
- R² Score

## Key Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis
- Handling missing values
- Outlier detection
- Categorical encoding
- Classification modelling
- Regression modelling
- Hyperparameter tuning with GridSearchCV
- Model evaluation using classification and regression metrics
- Visualising model performance
- Working with Jupyter notebooks

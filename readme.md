# Titanic Passenger Survival Prediction

A machine learning project that predicts whether a passenger survived the Titanic disaster using demographic and travel information. The project demonstrates an end-to-end ML workflow, including data preprocessing, feature engineering, model training, evaluation, explainability, and prediction generation.

## Features

* Data preprocessing and cleaning
* Missing value handling
* Feature engineering
* Multiple machine learning models
* Hyperparameter tuning
* Model evaluation using cross-validation
* SHAP-based model explainability
* Prediction generation for the test dataset

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* SHAP
* Matplotlib
* SciPy
* Joblib

## Dataset

The project uses the Kaggle Titanic dataset, which contains passenger details such as:

* Passenger Class
* Age
* Gender
* Fare
* Family Size
* Embarked Port

The objective is to predict whether a passenger survived.

## Project Structure

```
Titanic Passenger Survival/
│── train.csv
│── test.csv
│── gender_submission.csv
│── submission.csv
│── ML_project_odd_sem.py
│── requirements.txt
│── README.md
```

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/vedantbhor23/titanic-survival-.git
cd titanic-survival-
pip install -r requirements.txt
```

## Running the Project

Execute the Python script:

```bash
python ML_project_odd_sem.py
```

## Machine Learning Workflow

* Load and explore the dataset
* Clean and preprocess data
* Engineer useful features
* Train multiple classification models
* Evaluate model performance
* Interpret predictions using SHAP
* Generate predictions for unseen data

## Future Improvements

* Model deployment using Flask or Streamlit
* Automated hyperparameter optimization
* Interactive dashboard for predictions
* Deep learning-based survival prediction

## Author

**Vedant Bhor**

Computer Engineering Student | Machine Learning | AI | Data Science

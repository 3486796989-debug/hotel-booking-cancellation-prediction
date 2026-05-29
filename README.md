# Hotel Booking Cancellation Prediction

This project predicts hotel booking cancellation outcomes using structured hotel booking data and machine-learning classification models.

## Project Overview

The workflow includes data preprocessing, exploratory data analysis, feature engineering, model training, and model evaluation.

Main steps include:

- loading hotel booking data from `data.csv`
- checking duplicate values and missing values
- removing invalid or high-missing-rate columns
- imputing missing values
- cleaning invalid guest-count records
- exploring numerical and categorical features
- encoding categorical variables with one-hot encoding
- standardizing numerical features
- training classification models
- evaluating models with accuracy, AUC, confusion matrix, and ROC curves

## Models Used

- Logistic Regression
- Gaussian Naive Bayes
- Random Forest
- Decision Tree

Randomized search is used for hyperparameter tuning on Random Forest and Decision Tree models.

## Repository Files

- `hotel_booking_cancellation_prediction.ipynb`  
  Main Jupyter Notebook containing the full analysis workflow.

- `requirements.txt`  
  Python dependencies required to run the project.

## Data

The project expects a `data.csv` file in the project root. The raw data file is not included if it contains private or large-scale data.

## How To Run

Install the required packages:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook hotel_booking_cancellation_prediction.ipynb
```

Run the notebook cells sequentially after placing `data.csv` in the project directory.

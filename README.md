# medical-insurance-cost-prediction-using-machine-learning-
This project predicts medical insurance costs based on various user attributes using a **Linear Regression** model. The dataset includes features such as age, BMI, smoking status, and region. The goal is to build a model that can help understand the impact of these factors on insurance charges.

## Overview

* Built a **Linear Regression** model to estimate insurance charges.
* Preprocessed the dataset by:

  * Handling missing values
  * Encoding categorical variables
  * Scaling numerical features
* Evaluated model performance on a test dataset.
* Achieved an **accuracy of 74.4%** on test data.

##  Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib & Seaborn (for visualization)

## Dataset

The dataset includes the following features:

* `age`: Age of the primary beneficiary
* `sex`: Gender of the person
* `bmi`: Body Mass Index
* `children`: Number of children covered by insurance
* `smoker`: Smoking status (`yes`/`no`)
* `region`: Residential area in the US
* `charges`: Insurance cost (target variable)

You can find the dataset [here](https://www.kaggle.com/datasets/mirichoi0218/insurance).

1. Data Preprocessing

   * Handled missing values (if any)
   * One-hot encoded categorical variables (`sex`, `smoker`, `region`)
   * Scaled numerical features for better model performance

2. Model Training

   * Split the data into training and testing sets
   * Trained a **Linear Regression** model using Scikit-learn

3. Evaluation

   * Calculated metrics like R² score and Mean Squared Error
   * Achieved an accuracy of **74.4%** on the test set

## Results

* The model effectively identifies trends based on smoking, BMI, and age.
* Smoking status had the most significant impact on insurance costs.

## Future Improvements

* Try advanced models like Random Forest or XGBoost
* Perform hyperparameter tuning
* Use cross-validation for more robust evaluation

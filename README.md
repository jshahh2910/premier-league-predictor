# premier-league-predictor
Machine learning project for predicting Premier League match outcomes using historical match data and team form.

## Project Overview

This project uses historical Premier League match data to build a machine learning model that predicts the outcome of a football match:

- **Home Win**

- **Draw**

- **Away Win**

The project starts with historical match data and gradually prepares it for machine learning by cleaning the data, creating useful features, and training a classification model.

## Dataset

The dataset contains Premier League match results from **1993 to 2025**.

The main dataset is stored in:

`Data/premier_league_matches_1993_2025.csv`

The data includes information such as:

- Match date

- Home team

- Away team

- Home goals

- Away goals

- Full-time result

## Machine Learning

The current model uses **Logistic Regression** for multiclass classification.

The workflow includes:

1. Loading and inspecting the dataset

2. Cleaning and preparing the data

3. Creating match-related features

4. Splitting the data chronologically

5. Preprocessing numerical and categorical features

6. Training the Logistic Regression model

7. Evaluating the model

8. Comparing the model against a naive baseline

## Evaluation

The model is evaluated using:

- Accuracy

- Balanced Accuracy

- Macro F1-score

- Weighted F1-score

- Confusion Matrix

- Classification Report

A naive baseline that predicts the most frequent class is also used for comparison.

## Project Structure

```text

premier-league-predictor/
│
├── Data/
│   └── premier_league_matches_1993_2025.csv
│
├── premier league.ipynb
│
├── README.md
│
└── requirements.txt
```

Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

Future Improvements

* Add more team-form features
* Improve prediction of draws
* Experiment with additional machine learning models
* Tune model hyperparameters
* Add more recent match data
* Build a simple interface for match predictions



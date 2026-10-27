# Exploratory Data Analysis (EDA) on the Titanic Dataset 🚢

## About the Project

This is one of my first hands-on projects in Exploratory Data Analysis (EDA). I wanted to understand how to explore a dataset, identify missing values, clean the data, and use visualizations to find patterns rather than just looking at rows and columns.

For this project, I followed along with Krish Naik's EDA tutorial and practised the concepts using the Titanic dataset. It helped me connect the Python and Pandas basics I was learning with a practical data analysis problem.

## What is EDA?

Exploratory Data Analysis is the process of understanding a dataset before drawing conclusions or building a machine learning model.

It helps us answer questions such as:
- What does the dataset contain?
- Are there any missing or unusual values?
- Which patterns or relationships can we find?
- Which features might be useful for further analysis?

## Dataset

The project uses the Titanic training dataset, which contains information about passengers aboard the Titanic.

Some of the important columns are:

- **PassengerId:** Unique ID assigned to each passenger.
- **Survived:** Whether the passenger survived (0 = No, 1 = Yes).
- **Pclass:** Passenger class (1st, 2nd, or 3rd).
- **Name:** Passenger's name.
- **Sex:** Passenger's sex.
- **Age:** Passenger's age.
- **SibSp:** Number of siblings or spouses aboard.
- **Parch:** Number of parents or children aboard.
- **Fare:** Ticket fare.
- **Cabin:** Cabin information.
- **Embarked:** Port where the passenger boarded.

## Tools and Libraries

- Python
- Pandas — for loading, exploring, and cleaning data.
- NumPy — for numerical operations.
- Matplotlib — for creating plots.
- Seaborn — for statistical visualizations.
- Jupyter Notebook / Google Colab — for writing and running code.

## What I Explored

### 1. Understanding the Data

I used functions such as `head()`, `info()`, `describe()`, and `shape` to understand the dataset, its dimensions, column types, and basic statistics.

### 2. Handling Missing Values

I checked for missing values using `isnull().sum()` and visualized them using a heatmap.

The `Age`, `Cabin`, and `Embarked` columns contained missing values. I explored an age-imputation approach, removed the `Cabin` column during preprocessing, and handled missing embarkation data.

### 3. Data Visualization

I used Seaborn and Matplotlib to explore the data visually and understand how passenger characteristics relate to survival.

### 4. Feature Preparation

I explored converting categorical variables into numerical representations so they could be used by a machine learning model.

### 5. Logistic Regression

I followed the tutorial's approach to train a Logistic Regression model and evaluate its predictions using accuracy.

## Key Learnings

- How to load and inspect a dataset using Pandas.
- Why data cleaning is an important part of analysis.
- How to identify missing values with a heatmap.
- How to handle missing data and categorical features.
- How visualizations can help reveal patterns in data.
- How to train a basic Logistic Regression model and evaluate its performance.

## Project Structure

```text
Exploratory-Data-Analysis/
├── EDA.ipynb
├── titanic_train.csv
└── README.md
```

The CSV file should be included only if redistribution is permitted. Otherwise, download instructions can be provided instead.

## How to Run the Notebook

1. Open `EDA.ipynb` in Google Colab or Jupyter Notebook.
2. Make sure the Titanic CSV dataset is available in the notebook's working directory.
3. Install any required libraries if they are not already available.
4. Run the notebook cells in order to reproduce the analysis.

## Learning Reference

This project was practised alongside **Krish Naik's Exploratory Data Analysis tutorial**.

This repository documents my learning and practice. I plan to keep improving my understanding of data analysis by exploring more datasets and asking better questions of the data.

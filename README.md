# adult-census-income-prediction
A Machine Learning project using the Adult Census Income dataset to predict whether an individual's annual income exceeds $50K. Includes data preprocessing, exploratory data analysis, visualization, and classification models using Python and Scikit-learn.
# Adult Census Income Prediction Using Machine Learning

##  Project Overview

This project focuses on predicting an individual's annual income using the Adult Census Income dataset.

The objective is to classify individuals into two income categories based on demographic and employment-related information.

Machine Learning classification algorithms are used to analyze the dataset and predict income levels.

##  Objectives

- Understand and explore the Adult Census Income dataset.
- Perform data cleaning and preprocessing.
- Handle missing values and duplicate records.
- Perform Exploratory Data Analysis (EDA).
- Visualize relationships between different features.
- Train Machine Learning classification models.
- Evaluate and compare model performance.

##  Dataset Description

The Adult Census Income dataset contains demographic and employment-related information.

**Important Features:**

- Age
- Workclass
- Final Weight (fnlwgt)
- Education
- Education Number
- Marital Status
- Occupation
- Relationship
- Race
- Sex
- Capital Gain
- Capital Loss
- Hours Per Week
- Native Country

**Target Variable:** `income`

The target variable contains two classes:

- `<=50K` – Annual income is $50,000 or less.
- `>50K` – Annual income is greater than $50,000.

##  Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

##  Project Workflow

1. **Data Loading:** Import the dataset using Pandas.
2. **Data Understanding:** Examine dataset shape, columns, data types, and statistical summaries.
3. **Data Cleaning:** Handle missing values, duplicates, and inconsistent data.
4. **Exploratory Data Analysis:** Analyze income distribution and feature relationships.
5. **Data Visualization:** Create charts such as histograms, count plots, box plots, and heatmaps.
6. **Data Preprocessing:** Encode categorical variables and prepare numerical features.
7. **Data Splitting:** Divide the dataset into training and testing sets.
8. **Model Building:** Train different classification algorithms.
9. **Model Evaluation:** Compare models using classification performance metrics.

##  Machine Learning Algorithms

The following classification algorithms are explored:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

##  Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

These metrics help understand and compare the performance of the classification models.

##  Installation

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

##  How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/your-username/adult-census-income-prediction.git
```

2. Navigate to the project folder.

3. Install the required libraries.

4. Make sure the dataset file is available in the project directory.

5. Launch Jupyter Notebook:

```bash
jupyter notebook
```

6. Open the notebook and run all cells.

##  Project Structure

```text
adult-census-income-prediction/
│
├── adult income prediction.ipynb
├── adult.csv
└── README.md
```

*Update the filenames above to match the files you actually upload.*

##  Future Improvements

- Experiment with additional classification algorithms.
- Perform hyperparameter tuning.
- Improve model performance through feature engineering.
- Evaluate models using confusion matrices and ROC-AUC.
- Develop a simple web application for income prediction.

##  Author

**Vishwani G**

B.Sc. Computer Science with Artificial Intelligence Student

Interested in Artificial Intelligence, Machine Learning, and Data Science.

---

⭐ Thank you for visiting this project!

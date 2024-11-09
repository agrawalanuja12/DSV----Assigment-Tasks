# MCA Assignment: Data Exploration and Model Building

This repository contains solutions for three tasks as part of an MCA assignment, focusing on data exploration and regression model building. Each task is implemented in a Jupyter Notebook and demonstrates fundamental techniques in data science using Python.

## Tasks Overview

### Task 1: Dataset Exploration - Iris Dataset
**Objective:** Load and explore the Iris dataset.

**Steps:**
- Load the Iris dataset from `sklearn.datasets`.
- Display the first five rows and the dataset's shape.
- Calculate summary statistics (mean, standard deviation, minimum, and maximum) for each feature.

**Output:** Basic summary statistics and a preview of the dataset.

---

### Task 2: Data Splitting - Iris Dataset
**Objective:** Split the Iris dataset into training and testing sets.

**Steps:**
- Load the Iris dataset.
- Split the dataset into an 80-20 training-testing ratio.
- Print the number of samples in each set.

**Output:** Training and testing set sizes for further model use.

---

### Task 3: Linear Regression - Salary Prediction
**Objective:** Train a linear regression model to predict salary based on years of experience.

**Steps:**
- Load a dataset with `YearsExperience` and `Salary` columns.
- Train a linear regression model using `YearsExperience` as the predictor.
- Evaluate the model's performance with Mean Squared Error (MSE).

**Output:** MSE score on the test set.

---

## Project Structure

```plaintext
├── task1_exploration.ipynb       # Notebook for Task 1
├── task2_split.ipynb             # Notebook for Task 2
├── task3_regression.ipynb        # Notebook for Task 3
├── requirements.txt              # List of required packages
└── README.md                     # Project documentation

# Iris Flower Classification

## OIBSIP Data Science Internship — Task 1

### Project Overview

This project focuses on building a machine learning classification model to predict the species of an iris flower based on its physical measurements.

The Iris dataset contains measurements of sepal length, sepal width, petal length, and petal width for three different iris species:

* Setosa
* Versicolor
* Virginica

### Objective

The main objectives of this project are:

* Explore and understand the Iris dataset.
* Perform exploratory data analysis.
* Visualize relationships between features and species.
* Split the dataset into training and testing sets.
* Train multiple classification models.
* Evaluate model performance using accuracy, confusion matrices, and classification reports.
* Select the best-performing model based on test-set performance.

### Dataset

The Iris dataset is obtained from the built-in `scikit-learn` dataset collection using `load_iris()`.

The dataset contains:

* 150 observations
* 4 numerical features
* 3 target classes
* No missing values

### Features

| Feature      | Description                        |
| ------------ | ---------------------------------- |
| Sepal Length | Length of the sepal in centimeters |
| Sepal Width  | Width of the sepal in centimeters  |
| Petal Length | Length of the petal in centimeters |
| Petal Width  | Width of the petal in centimeters  |

### Machine Learning Models

Two classification algorithms were implemented:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)

### Model Results

| Model               | Test Accuracy |
| ------------------- | ------------: |
| Logistic Regression |        96.67% |
| K-Nearest Neighbors |          100% |

Based on the selected test split, K-Nearest Neighbors achieved the highest test accuracy among the two evaluated models.

### Exploratory Data Analysis

The project includes:

* Dataset shape and data types
* Missing-value analysis
* Descriptive statistics
* Species distribution
* Pairplot visualization
* Box plot analysis
* Feature selection discussion

The analysis showed that petal length and petal width provide strong discriminatory information for distinguishing the iris species.

### Model Evaluation

The models were evaluated using:

* Accuracy
* Classification Report
* Confusion Matrix

### Example Prediction

The trained KNN model was also used to predict the species of new iris flowers using their sepal and petal measurements.

### Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* VS Code

### Project Structure

```text
Task1_Iris_Classification/
│
├── YuvasreeM_Task1.ipynb
└── README.md
```

### Conclusion

The project demonstrates the complete machine learning workflow for a classification problem, including data exploration, visualization, model training, evaluation, comparison, and prediction.

K-Nearest Neighbors achieved 100% accuracy on the selected test set and was therefore selected as the best-performing model for this project.

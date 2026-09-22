# OIBSIP Task 3 – Car Price Prediction

## Project Overview

This project focuses on predicting the selling price of used cars using Machine Learning regression techniques.

The dataset contains information about used cars such as manufacturing year, kilometers driven, fuel type, seller type, transmission, owner type, mileage, engine, maximum power, and number of seats.

## Objective

The main objective of this project is to build a machine learning model that can predict the selling price of a used car based on its characteristics.

## Dataset

The project uses the CarDekho car price dataset.

### Features

* Year
* Kilometers Driven
* Fuel Type
* Seller Type
* Transmission
* Owner
* Mileage
* Engine
* Max Power
* Seats

### Target

* Selling Price

## Data Preprocessing

The following preprocessing steps were performed:

* Removed duplicate records
* Handled missing numerical values using median values
* Converted `max_power` into numerical format
* Filled missing `max_power` values
* Removed the `name` column
* Converted categorical variables using one-hot encoding
* Split the dataset into training and testing sets

## Machine Learning Models

Three regression models were trained and evaluated:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

## Model Results

| Model             |       MAE |      RMSE |     R² |
| ----------------- | --------: | --------: | -----: |
| Linear Regression | 172654.81 | 306982.06 | 0.5703 |
| Decision Tree     |  92742.75 | 169335.31 | 0.8693 |
| Random Forest     |  75058.16 | 132065.28 | 0.9205 |

## Feature Importance

The Random Forest model was also used to analyze feature importance.

The most influential features in the model included:

* Max Power
* Year
* Mileage
* Kilometers Driven
* Engine

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Structure

```text
Task3_Car_Price_Prediction/
│
├── YuvasreeM_Task3.ipynb
└── README.md
```

## Conclusion

This project demonstrates the use of machine learning regression techniques for used car price prediction. Multiple models were compared using MAE, RMSE, and R² metrics, and the Random Forest model achieved an R² score of approximately 0.92 on the test dataset.

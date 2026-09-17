# Car Price Prediction

A machine learning web application that predicts the price of a used car based on details such as car company, car model, year, kilometers driven, and fuel type.

## Project Overview

This project uses Machine Learning to estimate the price of a used car. A Linear Regression model is trained using a cleaned used-car dataset and integrated into a Flask web application.

The user enters the required car details through the web interface, and the application predicts the estimated price.

## Technologies Used

- Python
- Flask
- Pandas
- NumPy
- Scikit-learn
- HTML
- CSS
- Bootstrap
- Jupyter Notebook
- Git & GitHub

## Machine Learning Model

The project uses:

- Linear Regression
- Train-test split
- Data cleaning and preprocessing

The trained model is saved as:

`LinearRegressionModel.pkl`

## Project Structure

```text
Car-Price-Prediction/
│
├── application.py
├── Cleaned Car.csv
├── LinearRegressionModel.pkl
├── requirements.txt
├── .gitignore
├── README.md
│
├── templates/
│   └── index.html
│
└── static/
    └── css/
        └── style.css

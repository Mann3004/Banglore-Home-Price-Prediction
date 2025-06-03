# Bangalore Home Price Prediction 🏡

This project is a Machine Learning-based web application that predicts the price of homes in Bangalore based on various parameters like location, square footage, number of bedrooms, and bathrooms.

## 📊 Dataset

The dataset used is `bengaluru_house_prices.csv`, which contains real estate listings from Bangalore. It includes features such as:
- Location
- Square footage
- Number of bedrooms (BHK)
- Number of bathrooms
- Price (target)

## 🔍 Model Overview

The data was preprocessed through:
- Handling missing values
- Removing outliers
- Dimensionality reduction (location clustering)

A regression model (Linear Regression) was trained on the cleaned dataset to predict house prices.

## 🌐 Web Interface

A simple web interface built using HTML, CSS, and JavaScript allows users to:
- Select a location
- Enter square footage
- Choose BHK and bathrooms
- Get the estimated price instantly

## ⚙️ How to Run Locally

1. Clone this repository:
    ```bash
    git clone https://github.com/Mann3004/Banglore-Home-Price-Prediction
    ```

2. Install required Python libraries:
    ```bash
    pip install pandas numpy matplotlib scikit-learn flask
    ```

3. Run the Flask server:
    ```bash
    python server.py
    ```

4. Open `client/app.html` in a browser to use the application.

## 📌 Features

- Data Cleaning and Preprocessing
- Linear Regression Model
- Interactive Web Interface
- Location-wise Prediction

# 📈 Stock Price Prediction using Linear Regression

## 📝 Project Overview
This project aims to predict **stock prices** using **Linear Regression**. We use **historical stock data** to train the model and forecast future prices. The objective is to provide a simple, interpretable model to understand the relationship between time and stock price.

## 📊 Features
- Predict future stock prices using **Linear Regression**
- Data preprocessing and feature engineering
- Evaluate model performance using metrics like **Mean Squared Error (MSE)** and **R-squared (R²)**
- Visualize stock trends and predictions using **Matplotlib**


## 📊 Dataset
- **Source**: Publicly available stock market dataset (e.g., Yahoo Finance, Kaggle)
- **Columns**:
  - `Date`: The date of the stock price
  - `Open`: Opening price
  - `High`: Highest price
  - `Low`: Lowest price
  - `Close`: Closing price (target variable)

## 🛠️ Requirements
Ensure you have the following packages installed:

**requirements.txt**
```
numpy
pandas
matplotlib
scikit-learn
```

## 📈 Model Workflow
1. **Data Collection**: Load stock market data from CSV.
2. **Data Preprocessing**:
   - Handle missing values.
   - Convert `Date` column to datetime format.
   - Extract features like **Year**, **Month**, **Day**.
3. **Train-Test Split**: Divide the dataset into **training** and **testing** sets.
4. **Model Training**: Fit **Linear Regression** on the training data.
5. **Model Evaluation**: Evaluate performance using:
   - Mean Squared Error (MSE)
   - R-squared (R²)
6. **Prediction & Visualization**: Predict future stock prices and visualize results.


## 📊 Model Performance
Example output:
```
Mean Squared Error: 230.38
R-squared: 0.99
```

## 📌 Future Improvements
- Use **polynomial regression** for better modeling of non-linear patterns.
- Implement **time-series models** like **ARIMA** or **LSTM**.
- Explore other features like **moving averages** and **trading volume**.


## 🧑‍💻 Author
Your Name - [Your GitHub Profile](https://github.com/shivam200412)

## 📜 License
This project is licensed under the MIT License.


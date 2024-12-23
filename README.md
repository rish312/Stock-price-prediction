<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Comfortaa&size=30&duration=4000&pause=1000&color=F7F7F7&background=FFFFFF00&width=435&lines=%F0%9F%93%88+Stock+Price+Prediction" alt="Typing SVG" /></a>

![Stock Prediction Model](https://github.com/Karthik3904/Stock-Price-Prediction/blob/update-readme/images/Screenshot%202024-10-25%20194943.png)

</div>

<img src="https://raw.githubusercontent.com/alo7lika/Stock-Price-Prediction/refs/heads/main/Images/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">


<br>

<img src="https://raw.githubusercontent.com/alo7lika/Stock-Price-Prediction/refs/heads/main/Images/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="900">

## ✨ Project Structure

Check the project structure here [Project Structure](PROJECT_STRUCTURE.md)

## 📚 Table of Contents

- [✨ Project Structure](#-project-structure)
- [📚 Table of Contents](#-table-of-contents)
- [🌞 Overview](#-overview)
- [🛠️ Features](#️-features)
- [🔍 Algorithms Used](#-algorithms-used)
- [📊 Dataset](#-dataset)
- [📁 Project Structure](#-project-structure-1)
- [🚀 How to Run `main.py`](#-how-to-run-mainpy)
- [📈 Results](#-results)
- [📊 Performance Metrics](#-performance-metrics)
- [🔧 Optimization Techniques](#-optimization-techniques)
- [🔮 Future Work](#-future-work)
- [🏆 Conclusion](#-conclusion)


---
## 🌞 Overview
This project aims to predict the stock prices of **The State Bank of India (SBI)** using various machine learning regression algorithms. By leveraging historical stock data sourced from Yahoo Finance, this project provides insights into the performance of different regression models in stock price prediction for SBI. 

The primary objective is to compare model accuracy and performance metrics, such as RMSE, MAE, and MAPE, across multiple algorithms, ultimately identifying the most suitable regression approach for stock price forecasting.


## 🛠️ Features

- Utilizes various regression algorithms for stock price prediction.
- Dataset collected from Yahoo Finance for **The State Bank Of India**.

## 🔍 Algorithms Used

We implemented the following regression algorithms for stock price prediction:

| 🤖 Algorithm                              | 📜 Description                                      |
|-------------------------------------------|----------------------------------------------------|
| Linear Regression                        | A basic regression algorithm.                       |
| Support Vector Regression (SVR)         | Effective for non-linear relationships.             |
| Random Forest                            | Ensemble learning method using decision trees.      |
| Decision Tree                            | Simple yet effective model based on tree structure. |
| KNeighborsRegressor (KNN)               | Predicts based on nearest neighbors' average.      |
| Artificial Neural Networks (ANN)        | Mimics human brain for complex data patterns.       |
| Long Short Term Memory (LSTM)           | Suitable for time-series prediction.                |

## 📊 Dataset

The dataset used in this project is sourced from Yahoo Finance and includes historical stock data for **The State Bank Of India**. It comprises relevant features such as:

- 📈 Open prices
- 📉 High prices
- 📉 Low prices
- 💵 Close prices
- 📦 Volume

## 📁 Project Structure

📂 data/ # Contains the dataset files.
📓 notebooks/ # Jupyter notebooks with the code for data exploration, preprocessing, and model training.
🐍 src/ # Python source code for the project.
📋 requirements.txt # List of dependencies needed to run the project.


## 🚀 How to Run `main.py`
**Steps**:
1.**If Flask is not installed, install it**:
  ```bash
  pip install flask
  ```
2.**Install dependencies using**:
  ```bash
  pip install -r requirements.txt
  ```
3.**Run the Flask app**:
  ```bash
  python main.py
  ```


## 📈 Results

The sequence of all the algorithms used is as follows:

1. Linear Regression
2. SVR
3. Random Forest
4. Gradient Boosting Models (GBM)
5. Extreme Gradient Boosting (XGBoost)
6. AdaBoostRegressor
7. Decision Tree
8. KNeighborsRegressor (KNN)
9. Artificial Neural Networks (ANN)
10. Long Short Term Memory (LSTM)

## 📊 Performance Metrics

The **Root Mean Square Error (RMSE)** of all the following 10 Regression Algorithms is provided below: 
<img src="images/f23e9194-72de-438d-bd69-744667680d3e.jpeg" alt="Performance-Metrices" width="400" height="300">


The **Mean Absolute Error (MAE)** of all the following 10 Regression Algorithms is provided below: 

<img src="images/085ee2d1-3544-4bed-a558-5b0b801e806b.jpeg" alt="Performance-Metrices" width="400" height="300">


The **Mean Absolute Percentage Error (MAPE)** of all the following 10 Regression Algorithms is provided below: 

<img src="images/6c9ebb5b-a8ed-44de-8842-bf8f5c25990f.jpeg" alt="Performance-Metrices" width="400" height="300">

## 🔧 Optimization Techniques

We have applied several Intel-specific optimization techniques to enhance the performance of our models. For detailed information, please refer to the [Optimization Techniques](./Intel_Optimized/Intel_Optimization.md) document.

## 🔮 Future Work

- Combine this data with stock sentiment data to enhance prediction accuracy.
- Utilize clustering algorithms to develop a buy/sell recommendation system.

## 🏆 Conclusion

Among the models assessed, **AdaBoostRegressor** and **LSTM** emerged as the top performers, showcasing low RMSE, MAE, and MAPE values. These metrics suggest that these algorithms effectively capture the underlying trends and patterns in the stock price data, making them reliable for prediction tasks.

While some models demonstrated solid predictive capabilities, others, such as **Support Vector Regression (SVR)** and **KNeighborsRegressor**, recorded higher RMSE and MAE values. This indicates that these algorithms may yield acceptable predictions on average but are susceptible to significant errors in certain scenarios, emphasizing the need for careful model selection for stock price predictions.



This is my personal ML and Stock market analysis project

# Stock Market Analysis and Prediction using Supervised Machine Learning

## 📌 Project Overview

This project focuses on analyzing and predicting stock market trends of the **NIFTY 50 index** using supervised machine learning and deep learning models. Historical stock data is collected and processed to build predictive models that estimate future price movements.

The project compares multiple models including **Linear Regression, Random Forest, Support Vector Machine (SVM), and LSTM neural networks** to evaluate their prediction performance.

---

## 🎯 Objectives

* Collect historical NIFTY 50 stock market data
* Perform data preprocessing and feature engineering
* Train multiple machine learning models
* Optimize models using hyperparameter tuning
* Evaluate model performance using standard metrics
* Compare prediction accuracy of different models

---

## 🛠 Tools and Technologies

* **Programming Language:** Python
* **Environment:** Jupyter Notebook / VS Code
* **Libraries Used:**

  * yfinance (data collection)
  * pandas, numpy (data processing)
  * matplotlib (visualization)
  * scikit-learn (ML models)
  * tensorflow / keras (LSTM model)

---

## 📊 Dataset

Historical NIFTY 50 stock market data is downloaded using the Yahoo Finance API via the **yfinance** library. The dataset includes:

* Open price
* Close price
* High price
* Low price
* Volume

Time range: **2015 – 2025**

---

## ⚙️ Methodology

1. Data collection using yfinance
2. Data preprocessing and cleaning
3. Feature engineering (moving averages, returns, volatility)
4. Data normalization and time-series window creation
5. Training ML models:

   * Linear Regression
   * Random Forest (with hyperparameter tuning)
   * Support Vector Machine (SVM)
   * LSTM neural network
6. Model evaluation using:

   * Mean Squared Error (MSE)
   * Root Mean Square Error (RMSE)
   * R-squared (R²)
   * Symmetric Mean Absolute Percentage Error (SMAPE)
7. Performance comparison and analysis

---

## 📈 Results

The project evaluates and compares the performance of all models using multiple metrics. The best-performing model is selected based on prediction accuracy and error minimization.

---

## 🚀 How to Run the Project

1. Install required libraries:

   ```bash
   pip install yfinance pandas numpy matplotlib scikit-learn tensorflow
   ```
2. Run the Jupyter notebook step-by-step
3. The dataset will be downloaded automatically
4. Models will train and display performance results

---

## 📂 Project Structure

```
├── nifty50_data.csv
├── stock_prediction.ipynb
├── README.md
```

---

## 🔮 Future Scope

* Integration of real-time stock data
* Use of advanced deep learning models
* Deployment as a web-based prediction system
* Addition of more financial indicators

---

## 👨‍💻 Author

**Tejas Nikas**

---

## 📜 License

This project is for educational and academic purposes.


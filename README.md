# 📈 TCS Stock Price Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on analyzing and predicting Tata Consultancy Services (TCS) stock prices using Machine Learning techniques in Python. Historical stock market data from the past four years is used to analyze price movements, visualize trends, train machine learning models, and evaluate their prediction performance.

The main objective of this project is to understand how machine learning algorithms can be applied to historical stock market data and compare their performance in predicting stock prices.

## 🎯 Objectives

- Collect and analyze four years of historical TCS stock data.
- Perform data cleaning and preprocessing.
- Analyze Open, High, Low, Close, Adjusted Close, and Volume data.
- Visualize stock price trends using graphs.
- Build and train multiple machine learning models.
- Compare model performance using evaluation metrics.
- Identify the model that performs best on the selected test dataset.

## 📊 Dataset Information

- **Company:** Tata Consultancy Services (TCS)
- **Stock Ticker:** `TCS.NS`
- **Data Period:** Approximately October 2022 to October 2026
- **Data Frequency:** Daily stock market data
- **Number of Records:** Approximately 993 observations
- **Data Source:** Yahoo Finance historical stock market data

### Dataset Features

| Feature | Description |
|---|---|
| Date | Trading date |
| Open | Opening stock price |
| High | Highest price during the trading session |
| Low | Lowest price during the trading session |
| Close | Closing stock price |
| Adj Close | Adjusted closing price |
| Volume | Number of shares traded |

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Scikit-learn** – Machine learning models and evaluation
- **Google Colab / Jupyter Notebook** – Development environment
- **Yahoo Finance** – Historical stock data source

## 🤖 Machine Learning Models

The following regression models were used and compared in the project:

1. Linear Regression
2. Random Forest Regressor
3. Gradient Boosting Regressor
4. Support Vector Regression (SVR)

The models are evaluated on the selected test dataset to compare their prediction errors and performance.

## ⚙️ Project Workflow

1. **Data Collection:** Download historical TCS stock data.
2. **Data Cleaning:** Handle column names, date formatting, and data types.
3. **Exploratory Data Analysis:** Understand stock price trends and patterns.
4. **Data Visualization:** Plot Open and Close prices and other relevant trends.
5. **Feature Selection:** Select appropriate input features and the target variable.
6. **Data Splitting:** Divide the dataset into training and testing sets while preserving chronological order.
7. **Model Training:** Train the selected machine learning algorithms.
8. **Prediction:** Generate stock price predictions using trained models.
9. **Model Evaluation:** Compare predictions using suitable regression metrics.
10. **Result Visualization:** Present model comparisons and prediction results.

## 📉 Model Evaluation

The models are compared using Mean Absolute Percentage Error (MAPE) and approximate prediction accuracy.

The results obtained in the project are:

| Model | MAPE (%) | Approx. Prediction Accuracy (%) |
|---|---:|---:|
| Linear Regression | 1.54 | 98.46 |
| Random Forest | 24.55 | 75.45 |

*Note: These are the results recorded during the project. Add the final Gradient Boosting and SVR results after verifying your completed notebook.*

The approximate prediction accuracy shown here is calculated as `100 − MAPE`. It is a project-specific comparison metric, not a guarantee of actual stock prediction accuracy.

## 📁 Project Structure

```text
TCS-Stock-Price-Prediction/
│
├── TCS_Stock_Price_Prediction.ipynb
├── TCS_4_Years_Data.csv
└── README.md
```

*Update the notebook filename if your actual file uses a different name.*

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/TCS-Stock-Price-Prediction.git
```

### Step 2: Open the Project Folder

```bash
cd TCS-Stock-Price-Prediction
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Step 4: Open the Notebook

Open the `.ipynb` notebook in Google Colab or Jupyter Notebook.

### Step 5: Run the Cells

Run the notebook cells in order to load the dataset, explore the data, train the models, generate predictions, and evaluate the results.

## 🔍 Key Learnings

- Working with real-world historical stock market data.
- Data cleaning and preprocessing using Pandas.
- Visualizing financial data with Matplotlib and Seaborn.
- Applying regression algorithms using Scikit-learn.
- Evaluating and comparing machine learning models.
- Understanding the importance of chronological train-test splitting in time-series-related problems.

## ⚠️ Limitations

- Stock prices are affected by economic conditions, company performance, market sentiment, and unexpected events.
- Historical patterns do not guarantee future performance.
- Model results depend on the selected features, data quality, and evaluation methodology.
- Low prediction error on historical test data does not guarantee reliable future predictions.

**Disclaimer:** This project is for educational purposes only and should not be considered financial or investment advice.

## 👨‍💻 Author

**Sharukh**

B.Tech Graduate | Aspiring Data Analyst | Machine Learning Enthusiast

GitHub: [Add Your GitHub Profile Link](https://github.com/)

## ⭐ Support

If you find this project useful, consider giving the repository a star ⭐ on GitHub.

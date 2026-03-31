# 📊 E-Commerce Transaction Analysis using Statistical Distributions

## 🔷 Project Overview

This project focuses on analyzing customer transaction data from an e-commerce platform to understand purchasing behavior using statistical distribution techniques. The goal is to identify patterns in transaction success, frequency, and amount, and determine which probability distributions best model the data.

---

## 🎯 Objective

* Understand and apply probability distributions
* Analyze spread and behavior of transaction data
* Handle skewed data using transformations
* Derive meaningful business insights

---

## 📁 Dataset Description

| Column Name        | Description                                |
| ------------------ | ------------------------------------------ |
| transaction_id     | Unique transaction identifier              |
| customer_id        | Unique customer identifier                 |
| transaction_amount | Amount spent in ₹                          |
| transaction_date   | Date of transaction                        |
| transaction_count  | Number of transactions in a week           |
| region             | Customer region (North, South, East, West) |
| transaction_status | Success or Fail                            |

---

## 🛠️ Tools & Libraries Used

* Python
* NumPy
* Pandas
* SciPy
* Statsmodels
* Matplotlib
* Seaborn

---

## 🔷 Project Workflow

1. Data Loading & Cleaning
2. Exploratory Data Analysis (EDA)
3. Distribution Fitting
4. Visualization
5. Statistical Testing
6. Business Insights

---

## 📊 Part A — Theoretical Concepts Covered

* Statistical Distributions
* Q-Q Plot
* Discrete vs Continuous Distributions
* Bernoulli Distribution
* Binomial Distribution
* Poisson Distribution
* Log-Normal Distribution
* Power Law Distribution
* Box-Cox Transformation
* Z-Score Probability
* PDF vs CDF

---

## 📈 Part B — Analysis Performed

### 🔹 1. Bernoulli Distribution

* Modeled transaction success (Success = 1, Fail = 0)
* Calculated probability of success

### 🔹 2. Binomial Distribution

* Estimated probability of successful transactions over a week

### 🔹 3. Poisson Distribution

* Modeled number of transactions per day
* Checked mean vs variance for validation

### 🔹 4. Log-Normal Distribution

* Analyzed transaction amount distribution
* Identified right-skewed behavior

### 🔹 5. Power Law Distribution

* Checked presence of heavy-tailed spending behavior

### 🔹 6. Q-Q Plot

* Tested normality of transaction amounts

### 🔹 7. Box-Cox Transformation

* Reduced skewness and stabilized variance

### 🔹 8. Z-Score Analysis

* Calculated probability of transactions exceeding ₹5000

### 🔹 9. PDF & CDF

* Visualized probability distribution and cumulative probability

---

## 🔍 Key Findings

* Transaction success follows Bernoulli distribution
* Weekly success patterns align with Binomial distribution
* Daily transaction counts can be approximated using Poisson distribution (validated using mean ≈ variance)
* Transaction amounts are right-skewed, indicating Log-Normal behavior
* Q-Q plot confirms non-normality
* Box-Cox transformation improves data normality
* High-value transactions (> ₹5000) are relatively rare
* Evidence of heavy-tailed behavior suggests few high-spending customers dominate revenue

---

## 💡 Business Insights

* Identify high-value customers for targeted marketing
* Improve system reliability by analyzing failure rates
* Forecast transaction load using Poisson distribution
* Optimize pricing strategies based on spending patterns
* Detect anomalies and potential fraud

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:

   ```
   pip install pandas numpy scipy matplotlib seaborn statsmodels
   ```
3. Run the analysis script or Jupyter notebook:

   ```
   python analysis.py
   ```

---

## 📌 Conclusion

This project demonstrates how statistical distributions can be applied to real-world transaction data to extract meaningful insights. By combining theoretical concepts with practical implementation, it provides a strong foundation in data analysis and probability modeling.

---

## 👤 Author

Yakshraj Gohil

---

## ⭐ If you found this project useful, consider giving it a star!

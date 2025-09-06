# Bank Marketing Data Analysis – Mini Project

## 📌 Overview
This project analyzes the **Bank Marketing Dataset** to understand customer behavior and the factors influencing whether a client subscribes to a term deposit.  
Through **exploratory data analysis (EDA)** and visualization, the project highlights demographic and financial variables that affect subscription trends.

---

## 📂 Dataset
- **Source**: Bank Marketing Dataset (`bank.csv`)
- **Features**: Includes attributes such as age, job, marital status, education, balance, contact method, and outcome of previous marketing campaigns.
- **Target**: `subscription` (whether the customer subscribed to a term deposit).

---

## 🔎 Methodology
1. **Data Import & Cleaning**
   - Loaded dataset using pandas
   - Converted categorical features into appropriate datatypes
   - Checked missing values and inconsistencies

2. **Exploratory Data Analysis**
   - Distribution of age, balance, and job type
   - Relationship between demographic variables and subscription status
   - Comparison of subscription vs. non-subscription groups

3. **Visualizations**
   - **Boxplots & Violin plots**: To study distribution, spread, and outliers
   - **Pie charts**: To examine proportions of defaulters vs. non-defaulters
   - **Histograms**: For feature distributions

4. **Insights**
   - Younger customers are more frequent but less likely to subscribe
   - Higher balances generally correlate with higher subscription likelihood
   - Contact method and past campaign outcomes strongly influence results

---

## 📊 Results
- Customers with **higher balances** are more likely to subscribe.
- **Age** plays a significant role: older customers show higher subscription rates despite lower representation.
- **Previous campaign outcomes** and **contact methods** are strong predictors.

---

## 📦 Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/shilpagotur/bank-marketing-analysis.git

---

## 📌 Future Work
- Extend analysis with machine learning models for prediction
- Perform feature importance ranking
- Build a classification pipeline (Logistic Regression, Random Forest, etc.)

---

## 🙏 Acknowledgments
- UCI Bank Marketing Dataset
- Libraries: pandas, matplotlib, seaborn, numpy

---


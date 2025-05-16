# 📊 Electronics Customer Behavior Analysis

## 📁 Overview

This data science project analyzes customer behavior in the **electronics retail sector** using historical sales data. The objective is to uncover actionable insights to improve **customer retention**, enhance **marketing strategies**, and **boost sales** through a combination of data analysis and machine learning techniques.

The project covers:
- Data acquisition and cleaning
- Feature engineering
- Exploratory data analysis (EDA)
- Predictive modeling using regression and decision trees
- Customer segmentation with clustering

---

## 📌 Key Features

- Predict average spending per purchase
- Classify potential repeat customers
- Segment customers based on purchasing patterns
- Provide data-driven recommendations for business improvement

---

## 🛠️ Technologies Used

- **Python** 3.7+
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Machine learning models
- **Statsmodels** – Time series decomposition

---

## ⚙️ Installation

To run this project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/electronics-customer-behavior-analysis.git
   cd electronics-customer-behavior-analysis
2.**Create and activate a virtual environment**
  
  python -m venv venv
  source venv/bin/activate      # Windows: venv\Scripts\activate
  
3**Install dependencies**
pip install -r requirements.txt
jupyter notebook notebooks/AnalysisofCustomerBehaviour.ipynb

## 🔍 Analysis Summary

### 📈 Linear Regression
- **Goal**: Predict average spending per purchase  
- **Input Features**: Age, Income, Brand Affinity, etc.  
- **Metrics**: MAE, MSE, R²

---

### 🌳 Decision Tree Classifier
- **Goal**: Predict if a customer will purchase next month  
- **Features**: Purchase frequency, spend history  
- **Metrics**: Accuracy, Precision, Recall, F1 Score

---

### 🎯 K-Means Clustering
- **Clusters Found**: 3 major customer segments
  - High-spending loyal customers  
  - Occasional deal seekers  
  - Low-engagement or at-risk customers  
- **Strategy**: Tailor marketing campaigns for each group

---

## 📊 Key Recommendations

- **Targeted Campaigns**: Use cluster profiles to personalize promotions  
- **Seasonal Offers**: Address sales dips with timely discounts  
- **Loyalty Programs**: Retain valuable customers through incentives

---

## 🧪 Sample Features Engineered

- `Average_Spending_Per_Purchase`  
- `Purchase_Frequency_Per_Month`  
- `Brand_Affinity_Score`  
- `Recency_Days`  
- `Total_Spend_Per_Year`  
- `Purchase_Behavior` (high/low frequency)

---

## 📈 Visual Outputs

- Histograms and boxplots  
- Heatmaps for feature correlation  
- Elbow plot for K-means cluster selection  
- Decision tree visualization

---

## 📬 Contact

**Project Maintainer**:  
Senior Data Scientist  
📧 i232582@isb.nu.edu.pk




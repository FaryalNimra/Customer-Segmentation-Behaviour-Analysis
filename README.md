# 🛒 Customer Segmentation & Spending Behavior Analysis

This project involves **data preprocessing, visualization, and clustering analysis** on a retail dataset from an online shopping store. The goal is to understand customer behavior based on their online and offline spending habits, and segment them using machine learning.

---

## 🎯 Project Objective

The primary objectives of this project are to:

- Clean and preprocess transaction data from an online shopping store.  
- Perform exploratory data analysis (EDA) through statistical summaries and visualizations.  
- Understand spending patterns across demographics (like gender).  
- Use clustering techniques such as **KMeans** to segment customers based on their behavior and value.  
- Enable targeted marketing and data-driven decision-making through customer segmentation.

---

## 📁 Dataset Overview

- **File used**: `Online Shopping Store Transaction Data.csv`  
- **Columns include**:
  - `Gender`  
  - `Tenure_Months`  
  - `Quantity`  
  - `Avg_Price`  
  - `Offline_Spend`  
  - `Online_Spend`

---

## 📌 Key Tasks Performed

### ✅ 1. Data Cleaning
- Checked for missing values  
- Removed rows with null entries  

### 📊 2. Exploratory Data Analysis (EDA)
- Scatter plot: Online Spend vs Offline Spend (by gender)  
- Distribution plot of `Avg_Price`  
- Bar plot of average `Online_Spend` by gender  
- Box plot of `Offline_Spend` by gender  
- Correlation heatmap  
- Pair plots of selected features  

### 🤖 3. Customer Clustering (KMeans)
- Standardized numerical features: `Tenure_Months`, `Quantity`, `Avg_Price`, `Offline_Spend`, `Online_Spend`  
- Applied **KMeans Clustering**  
- Used **Elbow Method** to determine optimal number of clusters  
- Final number of clusters: **5**  
- Visualized clusters:
  - Online vs Offline Spending  
  - Quantity vs Avg Price  

---

## 📊 Visual Outputs

The notebook generates multiple helpful visualizations including:
- Correlation heatmap  
- Gender-based spending patterns  
- Elbow curve for optimal clusters  
- Cluster visualizations via scatter plots  

These insights help in understanding different customer groups and their unique spending behaviors.

---

## 🔧 Installation & Setup

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 👩‍💻 Author

**Faryal Nimra**  
📧 [faryalnimra190@gmail.com](mailto:faryalnimra190@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/faryal-nimra-4a49a32b6)  
🌐 [Portfolio](https://portfolio-five-beige-ixn8l41et7.vercel.app/)


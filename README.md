# RFM Customer Segmentation Analysis

## 📌 Project Overview

This project focuses on customer segmentation using the RFM (Recency, Frequency, Monetary) analysis technique.  
The purpose of the analysis is to identify customer purchasing behavior, classify customers into business-oriented segments, and generate actionable insights for customer retention and marketing strategies.

The analysis was performed using Python in Jupyter Notebook with data cleaning, preprocessing, exploratory data analysis, customer segmentation, and visualization techniques.

---

## 🛠 Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Datetime
- mpl_toolkits.mplot3d

---

# 🔍 Project Workflow

## Data Familiarizing

The following preprocessing steps were performed:

- Checked dataset structure
- Inspected missing values
- Removed duplicate records
- Converted date columns into datetime format
- Created additional analytical columns

---

## RFM Analysis

RFM metrics were created to evaluate customer behavior:

### 🔹 Recency (R)

Measures how recently a customer made a purchase.

### 🔹 Frequency (F)

Measures how often a customer purchases.

### 🔹 Monetary (M)

Measures how much money the customer spends.

---

## Customer Segmentation

Customers were segmented into the following groups:

| Segment         | Description                                   |
| --------------- | --------------------------------------------- |
| Champions       | Most valuable and active customers            |
| Loyal           | Regular customers with stable activity        |
| At Risk         | Previously active customers becoming inactive |
| Needs Attention | Customers with decreasing engagement          |
| Lost            | Inactive customers with low engagement        |

---

# 📊 RFM Segmentation Results

| Segment Name    | Segment Size | Avg Monetary | Avg Frequency | Avg Recency |
| --------------- | ------------ | ------------ | ------------- | ----------- |
| Lost            | 20           | 65403.58     | 1.95          | 356 Days    |
| Needs Attention | 17           | 83778.59     | 2.53          | 238 Days    |
| At Risk         | 18           | 100967.90    | 3.16          | 166 Days    |
| Loyal           | 18           | 103926.83    | 3.50          | 113 Days    |
| Champions       | 19           | 190116.63    | 5.53          | 31 Days     |

---

# 📁 Project Structure

```bash
├── Full RFM Segmentation and Customer Profiling1.ipynb
├── RFM_Segmentation.csv
├── README.md
├── note.md
├── sales_data_samle.csv

```

---

# 🚀 Business Value

This analysis helps businesses:

- Improve customer retention
- Detect churn risks
- Identify high-value customers
- Build personalized marketing campaigns
- Increase customer lifetime value
- Improve strategic decision-making

---

### Author: _Huseyn Ahmadov_

#### _Business Analyst & Data Analyst_

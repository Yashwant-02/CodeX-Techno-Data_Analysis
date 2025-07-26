# 🧠 Customer Segmentation Analysis

This project performs customer segmentation for a retail business using visual analytics and logical rules — It uses only `pandas`, `matplotlib`, and `seaborn`.

---

## 📌 Project Objective

To group customers into meaningful behavioral segments based on:
- **Spending Score**
- **Annual Income**
- **Age**
- **Gender**

These segments help:
- Design targeted marketing campaigns
- Improve customer experience
- Identify high-value and low-engagement customers

---

## 📂 Dataset Used

- **Dataset Name:** `mall_customers.csv`
- **Features:**
  - `CustomerID`
  - `Genre` (Male/Female)
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

---

## 🧰 Tools and Libraries

- `pandas` – for data manipulation  
- `matplotlib.pyplot` – for charts  
- `seaborn` – for visual exploration  

> ⚠️ No machine learning libraries (like scikit-learn) were used in this project.

---

## 🔍 Project Workflow

### ✅ 1. Data Loading
Loaded the CSV file and performed initial inspection:
- Data types
- Null values
- Summary statistics

### ✅ 2. Data Cleaning & Exploration
- Converted `Genre` to numeric (`Male`=1, `Female`=0)
- Dropped `CustomerID`
- Analyzed age, income, and spending score distributions

### ✅ 3. Manual Segmentation Logic
Defined customer segments **manually** using business logic:

| Segment         | Criteria                                      |
|----------------|-----------------------------------------------|
| VIP             | High Income & High Spending                   |
| Cautious Rich   | High Income & Low Spending                    |
| Young Spenders  | Low Income & High Spending                    |
| Low Budget      | Low Income & Low Spending                     |
| Average         | Everyone else                                 |

### ✅ 4. Visualization
Created the following plots:
- Gender Distribution
- Age Histogram
- Income and Spending Distributions
- Correlation Heatmap
- Scatter Plots for Segment Analysis
- Segment Count Bar Plot

---

## 📊 Key Insights

- High-spending customers aren't always high earners
- Young customers often show impulsive spending behavior
- Visual inspection allows us to **manually create logical clusters**
- These segments are useful for **business strategies**

---

## 🔚 Conclusion

This project shows that you can perform powerful segmentation by using domain knowledge, visualizations, and data analysis logic. Great for business teams without access to advanced tools.

---

## 📎 Author

**Yashwant Saini**  
📌 Data Analyst | Python • MySQL • Power BI • Excel  
🔗 GitHub Portfolio: [Yashwant-02](https://github.com/Yashwant-02)

---

## 📁 Folder Structure

```bash
📦 Customer-Segmentation/
├── mall_customers.csv
├── customer_segmentation.ipynb
├── README.md
└── outputs/
    └── plots/

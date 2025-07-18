# 📊 Android App Market EDA

This project analyzes the Google Play Store data to uncover insights about the Android app market. It involves data cleaning, category exploration, metrics analysis, sentiment review, and interactive visualizations using Python and Plotly.

---

## 🎯 Objective

To explore, clean, and visualize app data from the Google Play Store in order to understand market trends, user ratings, app types, pricing strategies, and user sentiments.

---

## ✅ Key Features

### 1. Data Preparation
- Removed missing values from important columns
- Cleaned and converted `Installs`, `Price`, and `Reviews` columns to proper numeric format
- Removed duplicate entries
- Exported cleaned data as `cleaned_apps.csv` and `cleaned_reviews.csv`

### 2. Category Exploration
- Identified and printed the Top 10 app categories by volume

### 3. Metrics Analysis
- Calculated average rating, max installs, most reviewed app, and average price of paid apps

### 4. Sentiment Analysis
- Analyzed user sentiments (Positive, Neutral, Negative) from reviews
- Displayed counts and percentage distribution

### 5. Interactive Visualizations (Plotly)
- 📊 Bar Plot: Top 10 App Categories
- 📉 Histogram: Rating Distribution
- 🥧 Pie Chart: Free vs Paid Apps
- 💰 Scatter Plot: Price vs Rating (Paid Apps)
- 💬 Bar Chart: Sentiment Distribution

---

## 📁 Files Included

- `Android_App_Market_EDA.ipynb` – Jupyter Notebook with complete analysis
- `apps.csv` – Raw app dataset
- `user_reviews.csv` – Raw user reviews dataset
- `cleaned_apps.csv` – Cleaned app dataset
- `cleaned_reviews.csv` – Cleaned user reviews

---

## ⚙️ How to Run

1. **Install Dependencies**
   ```bash
   pip install -r requirements.txt

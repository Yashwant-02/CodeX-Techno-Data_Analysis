**Android App Market EDA**
This project presents a comprehensive Exploratory Data Analysis (EDA) of the Google Play Store dataset. The objective is to derive actionable insights about app performance, user behavior, pricing strategies, and market dynamics using structured data analysis and interactive visualizations.

**Project Objective**
To clean, explore, and analyze app and user review data from the Google Play Store to understand:

Key trends in app categories, ratings, and installs

Pricing distribution between free and paid apps

User sentiment patterns across app reviews

Influencing factors for app success on the platform

**Datasets Used**
File	Description
apps.csv	Raw dataset containing app-level information
user_reviews.csv	Raw dataset of user reviews with sentiment labels
cleaned_apps.csv	Cleaned and processed app dataset
cleaned_reviews.csv	Cleaned and processed review dataset

**Data Cleaning & Preparation**
Performed rigorous data preprocessing to ensure accuracy and consistency:

Removed null and duplicate records

Converted data types (Installs, Price, Reviews) to numeric formats

Filtered irrelevant or corrupted entries

Saved clean datasets for downstream analysis

 **Key Analyses & Insights**
📂 Category Exploration
Identified top 10 most populated app categories

Assessed distribution of app types (free vs paid)

**📈 Metrics Analysis**
Calculated average ratings, installs, and pricing

Identified the most reviewed and most downloaded apps

**💬 Sentiment Analysis**
Classified user reviews into Positive, Neutral, and Negative

Analyzed sentiment distribution across app types and categories

**📊 Visualizations (Interactive - Plotly)**
Bar Chart – Top 10 App Categories

Histogram – Rating Distribution

Pie Chart – Free vs Paid Apps

Scatter Plot – Price vs Rating (Paid Apps)

Bar Chart – Sentiment Distribution in Reviews

**🛠️ Tools & Technologies**
Python – Data manipulation and analysis

Pandas, NumPy – Data handling and transformation

Plotly – Interactive data visualizations

Jupyter Notebook – Exploratory and visual workflows


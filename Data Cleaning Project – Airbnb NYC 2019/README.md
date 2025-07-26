# 🧹 Data Cleaning Project – Airbnb NYC 2019

## 📄 Description

This project involves cleaning and preprocessing the Airbnb New York City 2019 dataset. The goal is to prepare the data for reliable analysis by addressing inconsistencies, missing values, duplicates, and outliers.

## 📁 Dataset

- **Source**: Inside Airbnb  
- **File**: `AB_NYC_2019.csv`  
- **Records**: 48,895 rows × 16 columns  
- **Attributes** include: listing name, host ID, price, location, reviews, etc.

## 🧼 Cleaning Objectives

1. **Data Integrity** – Ensure reliable, accurate, and valid data.
2. **Missing Data Handling** – Imputed or removed missing values appropriately.
3. **Duplicate Removal** – Eliminated all exact duplicate records.
4. **Standardization** – Consistent formatting for strings, types, and units.
5. **Outlier Detection** – Identified and removed skewed records.

## 🔧 Cleaning Steps

- Dropped null values in critical columns (`name`, `host_name`)
- Filled `reviews_per_month` missing values with `0`
- Converted `last_review` to datetime format
- Removed duplicates
- Standardized string casing and spacing
- Removed outliers from `price` and `minimum_nights`
- Validated `latitude` and `longitude` ranges for NYC

## 💾 Output

- ✅ Cleaned file: `AB_NYC_2019_Cleaned.csv`

## 📌 Tools Used

- Python (Pandas)
- Jupyter Notebook

## 📊 Outcome

This clean dataset is now suitable for further analysis or dashboard creation in Power BI or Tableau.

---

## 📎 Author

**Yashwant Saini**  
*Data Analyst*  
📧 yashwantsaini523@gmail.com  
🌐 [GitHub Profile](https://github.com/Yashwant-02)


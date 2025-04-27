# 🏠 Exploratory Data Analysis on House Rent Prediction using Real Estate Data

## 📁 Project Overview
This project presents a detailed exploratory data analysis (EDA) on a **House Rent Prediction** dataset sourced from Kaggle.  
The dataset includes features such as **BHK configuration**, **area size**, **city**, **furnishing status**, and **tenant preference**.  
The goal of this analysis is to uncover rental market patterns, relationships between housing attributes and rent prices, and tenant trends, using powerful visualization and statistical methods.

---

## 📚 Project Objectives
- **Rent Distribution Across Cities**: Explore how rent varies geographically.
- **Relationship Between BHK and Rent**: Analyze rent trends across different house configurations.
- **Rental Price Analysis**: Deep dive into rent distribution based on multiple factors.
- **Count of Furnishing Types by City**: Compare how furnishing status varies across cities.
- **Monthly Average Rent Trend by Furnishing Status**: Analyze rent trends over time.
- **Furnishing and Tenant Preference Insights**: Understand the intersection between furnishing types and tenant types.
- **Scatter Plot on House Rents vs House Sizes**: Examine relationship between property size and rent.
- **Distribution of Different Number of BHKs**: Analyze which house configurations are most common.

---

## 🗂 Dataset
- **Source**: Kaggle – House Rent Prediction Dataset
- **Records**: 2,000+ synthetic real estate listings
- **Features**:
  - `BHK`: Number of Bedrooms, Hall, Kitchen.
  - `Rent`: Rent amount of the property.
  - `Size`: Property size (in Square Feet).
  - `Floor`: Floor level and total floors (e.g., 2 out of 5).
  - `Area Type`: Super Area, Carpet Area, or Build Area.
  - `Area Locality`: Specific locality name.
  - `City`: City name.
  - `Furnishing Status`: Furnished / Semi-Furnished / Unfurnished.
  - `Tenant Preferred`: Type of tenant (Family, Bachelors, Company).
  - `Bathroom`: Number of bathrooms.
  - `Point of Contact`: Contact information.

---

## 🧹 Data Preprocessing Steps
- Checked for missing values and duplicate records (none found, fortunately).
- Converted categorical variables where needed.
- Handled floor information parsing.
- Prepared dataset for further visual analysis and modeling tasks.

---

## 📊 Techniques & Tools Used
- **Programming Language**: Python (Jupyter Notebook)
- **Libraries**:
  - `pandas`, `numpy` – Data wrangling and analysis
  - `matplotlib`, `seaborn` – Visualization

---

## 📈 Key Visualizations
- **Heatmaps** – Correlation between numeric features
- **Bar Graphs** – BHK vs Rent, City-wise distribution
- **Violin Plots** – Rent distribution across furnishing statuses
- **Count Plots** – Tenant preference and furnishing types
- **Scatter Plots** – House Size vs Rent
- **Box Plots** – Rent across different cities
- **Line Plots** – Rent trends over time by furnishing status

---

## 📌 Notable Findings
- **Mumbai** and **Delhi** emerge as premium rental markets.
- Rent generally **increases** with the **number of BHKs and bathrooms**.
- **Semi-furnished** homes are the most popular choice among tenants.
- **Furnished** homes demand the **highest rents**.
- **Families** are the most preferred tenants.
- **Rental prices are steadily increasing** over time.
- **2BHK homes** are the most demanded property configuration.

---

---

## 📈 Future Scope
- **Statistical Hypothesis Testing**: Investigate statistical significance in rent trends.
- **Feature Engineering and Clustering**: Create new variables and group similar properties.
- **Real Estate Applications**: Insights can support rental portals and property investors.
- **Broader Academic and Industry Impact**: Dataset can enhance research in housing economics and urban planning.

---

## 👤 Author
**Name**: Abhishek Kashyap  
**Registration No**: 12311363  
**University**: Lovely Professional University, CSE (INT375)

---

## 📌 License
This project is developed for educational purposes under **INT375 – Data Science Toolbox** and follows all academic integrity norms.

---

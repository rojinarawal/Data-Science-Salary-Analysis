# 📊 Data Science Salary Analysis

This project explores and analyzes a comprehensive dataset of Data Science-related job titles, salaries, employment types, and geographic locations over the years. The analysis is conducted using Python libraries such as `pandas`, `numpy`, `matplotlib`, and `scipy`.

## 📁 Dataset Overview

- 📅 Work years: 2020–2023
- 💼 Job titles: 100+ unique roles
- 🌍 Global: Includes data from multiple countries and continents
- 🧠 Experience levels: Entry to Executive
- 🏢 Company sizes: Small, Medium, Large
- 💰 Salaries converted to USD

## 🛠️ Steps Performed

### 🔹 Data Preparation
- Loaded CSV data into a pandas DataFrame
- Removed unnecessary columns: `salary`, `salary_currency`
- Checked and removed missing (`NaN`) values (none found)
- Checked and listed duplicate records
- Standardized job titles (e.g., "Machine Learning Engineer" → "ML Engineer")
- Mapped experience level codes (e.g., "SE" → "Senior Level/Expert")

### 🔹 Data Analysis
- Calculated:
  - Total salary in USD
  - Mean and standard deviation
  - Skewness and kurtosis
  - Correlation matrix for numeric variables

### 🔹 Data Exploration
- Visualized:
  - Top 15 most common job titles (`bar chart`)
  - Highest average salary job (`bar chart with annotation`)
  - Salaries by experience level (`bar chart`)
  - Histogram and box plot for salary distribution

## 📈 Key Insights

- The most frequent roles include **Data Scientist**, **ML Engineer**, and **Data Analyst**.
- Salary distribution is **slightly right-skewed**, with high outliers.
- **Executive-level positions** earn the highest average salary.
- Remote work (remote_ratio) varies but 100% remote is most common in the dataset.

## 📦 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `scipy.stats`

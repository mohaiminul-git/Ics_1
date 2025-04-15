# 📊 Descriptive Analysis of Life Expectancy and Child Mortality

This project is an academic report submitted as part of the "Case Studies I" course at TU Dortmund University (Winter Term 2023/24). It investigates the disparities in life expectancy and under-5 child mortality rates across gender, regions, and timeframes using descriptive statistics and data visualization techniques.

## 📌 Project Objectives

- Explore gender-based and regional disparities in life expectancy and child mortality.
- Compare health indicators between two timeframes: 2004 and 2024.
- Examine statistical relationships between variables using correlation and scatter plot matrices.

## 🗃️ Dataset

The dataset is an extract from the U.S. Census Bureau’s International Data Base (IDB) containing demographic data for internationally recognized states/regions with populations exceeding 5,000 from 1950 to 2100. After data cleaning, 446 observations were analyzed.

**Key variables:**
- Life Expectancy at Birth (Male, Female, Both)
- Under Age 5 Mortality Rate (Male, Female, Both)
- Region, Subregion, Year

## 📈 Methods Used

- **Descriptive statistics:** Mean, Median, Standard Deviation, IQR
- **Visualization:** Histograms, Box Plots, Scatter Plot Matrix
- **Correlation analysis** to identify linear dependencies between variables

## 🔍 Key Insights

- Males have lower average life expectancy and higher child mortality than females.
- Europe shows the highest life expectancy, while Africa has the highest child mortality.
- A strong negative correlation (-0.866) exists between life expectancy and child mortality rates.
- Notable heterogeneity was found across subregions in Asia.

## 🛠️ Tools & Technologies

- Python 3.12.6
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
- IDE: VS Code

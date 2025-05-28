# Impact of Climate Change on Agricultural Production

## Project Overview

This project aims to analyze the impact of key climate variables, particularly temperature and precipitation, on agricultural production across six countries: Australia, Brazil, Germany, India, Nigeria, and the United States of America. By integrating long-term climate and crop production data, the study seeks to quantify how changing environmental conditions affect food security and economic stability in diverse regions.

---

## Motivation

Climate change poses significant risks to global agriculture, influencing crop yields and production variability. Understanding the relationship between climatic factors and agricultural output is essential for developing resilient farming practices and policies. This project addresses the urgent need for data-driven insights into how temperature and precipitation trends correlate with agricultural productivity in diverse geopolitical contexts.

---

## Data Sources

- **Climate Data:** Historical temperature and precipitation data sourced from global meteorological databases such as NOAA and FAO.  
- **Agricultural Data:** Crop production, yield, and harvested area data obtained from FAOSTAT, covering multiple decades.  
- **Countries Selected:** Australia, Brazil, Germany, India, Nigeria, and United States of America, chosen for their climatic diversity and agricultural significance.

---

## Methodology and Analytical Plan

- **Data Preprocessing:** Cleaning and transforming raw datasets into consistent, long-form formats; aligning years and country identifiers; handling missing values.  
- **Exploratory Data Analysis (EDA):** Visualization of temporal trends and distributions; calculation of correlation matrices between climate variables and agricultural metrics.  
- **Statistical Hypothesis Testing:** Pearson correlation tests to evaluate significance of relationships between temperature, precipitation, and production.  
- **Regression Modeling:** Multiple linear regression models incorporating temperature and precipitation as predictors of agricultural production.  
- **Model Evaluation:** Performance assessment using metrics such as R² score, and visualization of predicted versus actual values.  

---

## Tools and Libraries Used

- **Programming Language:** Python 3.x  
- **Data Manipulation:** pandas, numpy  
- **Statistical Analysis:** scipy.stats (pearsonr)  
- **Machine Learning:** scikit-learn (LinearRegression)  
- **Visualization:** matplotlib, seaborn  
- **Environment:** Jupyter Notebook for iterative analysis and reporting  

---

## Project Structure
```
/project-root
│
├── README.md # Project overview and instructions
├── requirements.txt # Python dependencies
├── notebooks/ # Jupyter notebooks with step-by-step analysis
│ ├── data_preprocessing.ipynb
│ ├── exploratory_analysis.ipynb
│ ├── regression_modeling.ipynb
│ └── hypothesis_testing.ipynb
├── data/ # Raw and processed datasets (subject to data sharing policy)
├── scripts/ # Python scripts for reusable functions and data pipelines
├── reports/ # Final report and presentations
│ └── final_report.pdf
```

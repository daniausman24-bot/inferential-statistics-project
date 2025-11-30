# Inferential Statistics Project — PakWheels Automobile Dataset

## Project Overview
This repository contains a comprehensive Exploratory Data Analysis (EDA) and Inferential Statistics project using the **PakWheels Used Car Dataset**.  
The project focuses on statistical reasoning, hypothesis testing, correlation analysis, and bootstrapping to derive meaningful insights from real-world data.

## Objectives
- Perform data cleaning and preprocessing to handle missing values and inconsistencies.  
- Explore and visualize dataset patterns using EDA techniques.  
- Apply inferential statistics to test hypotheses and compare groups.  
- Analyze correlations between variables and identify spurious correlations.  
- Validate results using bootstrapping for more robust inference.  
- Present clear conclusions and interpretations suitable for both technical and non-technical audiences.

## Methodology

### 1. Data Cleaning & Preparation
- Handled missing values and inconsistent entries.  
- Created bins for `model_year` (≤2010, 2011–2015, ≥2016).  
- Extracted brand names from car titles for group comparisons.

### 2. Exploratory Data Analysis (EDA)
- Descriptive statistics (mean, median, SD).  
- Visualizations: histograms, boxplots, bar charts.  
- Identification of skewness, outliers, and data patterns.

### 3. Inferential Statistics
- **One-sample tests:** t-test / z-test with 95% confidence interval.  
- **Two-sample tests:** independent t-test / z-test between selected groups.  
- **Multiple-group comparisons:** ANOVA or Kruskal–Wallis test for price differences across brands/year groups.  
- Interpretation of p-values and critical values for decision making.

### 4. Correlation Analysis
- Scatterplots and heatmap visualizations for numeric variables.  
- Computation of correlation coefficients, p-values, and confidence intervals.  
- Exploration of **spurious correlations** and their implications.

### 5. Bootstrapping
- Resampling with replacement (1000 iterations) to validate hypothesis test results and correlations.  
- Comparison of bootstrap confidence intervals with classical test results.

## Key Insights
- Significant differences in car prices across brands and model-year groups.  
- Strong correlations exist between engine size, mileage, and price.  
- Bootstrapping results were consistent with classical statistical tests, confirming the robustness of conclusions.  
- Spurious correlations were identified and explained, highlighting the importance of careful data interpretation.

## Tools & Libraries
- **Python**  
- **Jupyter Notebook**  
- **Pandas, NumPy, SciPy**  
- **Matplotlib, Seaborn**

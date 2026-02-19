# LIFE_EXPECTANCY_PROJECT

Analyzing Gapminder data to link GDP and population to life expectancy using EDA, SQL, interactive visualizations, and predictive modeling.

## Table of Contents
- Project Overview
- Objectives
- Data Source
- Tools
- Data Cleaning & Preparation
- Exploratory Data Analysis
- Data Analysis & Predictive Modeling
- Results / Findings
- Recommendations
- Dashboard Preview
- Limitations
- References

## Project Overview
The project “Analyzing Life Expectancy Across Countries” examines Gapminder datasets to uncover the relationship between economic factors and life expectancy. By combining exploratory data analysis (EDA), SQL queries, and predictive modeling, this project identifies key trends and predicts life expectancy for countries worldwide.

## Objectives
- Explore how GDP per capita and population influence life expectancy  
- Analyze trends across continents and income groups  
- Implement predictive modeling to forecast life expectancy  
- Provide actionable insights for public health and economic planning  

## Data Source
Country-level dataset containing:
- Life Expectancy  
- GDP per Capita  
- Population  
- Continent  
- Year  

Used for trend analysis, feature engineering, and machine learning.

## Tools
| Tool | Purpose |
|----|----|
| Python | Data cleaning, analysis, ML modeling |
| Pandas / NumPy | Data manipulation |
| Matplotlib / Seaborn | Visualization |
| SQL | Aggregation and analysis |
| scikit-learn | Machine Learning (Linear Regression) |
| Power BI | Interactive dashboards |
| Excel | Initial exploration |

## Data Cleaning & Preparation
- Checked missing and inconsistent values  
- Standardized data types and categorical fields  
- Removed duplicates  
- Engineered features:
  - Log GDP per Capita  
  - Life Expectancy Categories (Low / Medium / High)

## Exploratory Data Analysis
- Life expectancy distribution by continent  
- Correlation analysis between GDP, population, and life expectancy  
- Identification of outliers and anomalies  
- Scatter plots, bar charts, and heatmaps  

## Data Analysis & Predictive Modeling
### Machine Learning Component
- Linear Regression model implemented  
- Features: GDP per capita, Population  
- Train/Test split: 80% / 20%  
- Metrics: R² score, Mean Absolute Error (MAE)  

## Results / Findings
### Descriptive Insights
- Higher GDP correlates with higher life expectancy  
- Population has moderate influence  
- Europe & Oceania show highest averages; Africa lowest  

### Predictive Insights
- Model achieved R² ≈ 0.72  
- Identified underperforming countries relative to GDP  

## Recommendations
- Use predictions to guide health interventions  
- Investigate outliers for policy action  
- Combine ML results with dashboard insights  

## Dashboard Preview
Power BI dashboards showing:
- Life expectancy vs GDP  
- Predicted vs actual values  
- Interactive filters by country and year  

## Limitations
- Limited features beyond GDP and population  
- Historical data only  
- Outlier handling may affect averages  

## References
- Gapminder Dataset  
- Python Libraries: Pandas, NumPy, Matplotlib, Seaborn, scikit-learn  
- Power BI

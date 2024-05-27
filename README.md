# AQI Trends Over The Years
Analyzed air quality data for 26 Indian cities (2015-2020) using Python, leveraging Pandas for data manipulation, Seaborn and Matplotlib for visualization, and Scikit-learn for developing a Linear Regression model. Techniques included data cleaning, exploratory data analysis (EDA), time series analysis, and predictive modeling to uncover key pollution trends and patterns.

## Project Goals
- Explore the distribution of pollutants (PM2.5, PM10, AQI).
- Identify relationships between variables (e.g., PM2.5 vs. AQI).
- Analyze trends in pollution levels over time.
- Perform metro city-wise analysis.
- Explore possibilities for AQI prediction.

## Project Structure
- Data: Contains the air quality dataset in CSV format.
- Notebooks: Jupyter notebooks with detailed steps for data analysis, visualization, and modeling.
- Scripts: Python scripts for data preprocessing, EDA, and model training.
- Visualizations: Generated plots and charts.


## Data Description
The code expects the data to be in a CSV format with the following columns:

- date: Date of the measurement
- city: City name
- PM2.5: Concentration of fine particulate matter
- PM10: Concentration of coarse particulate matter
- AQI: Air Quality Index

## Dataset
- Source: The dataset contains daily air quality data for 26 cities in India.
- Time Period: January 2015 to July 2020.
- Key Features: PM2.5, PM10, NO2, NH3, SO2, CO, O3, AQI, AQI_Bucket, and date.

## Techniques and Tools Used
** Data Cleaning and Preprocessing:
*** Filled missing values using mean imputation.
*** Converted date column to datetime format.
*** Sorted data chronologically for time series analysis.

** Exploratory Data Analysis (EDA):
*** Computed descriptive statistics.
*** Visualized data using bar plots, scatter plots, histograms, and time series plots.
*** Analyzed trends and seasonal patterns.

** Visualization:
*** Employed Seaborn and Matplotlib for comprehensive data visualization.
*** Used various styles and color palettes for enhanced visual appeal.

** Predictive Modeling:
*** Developed a Linear Regression model using Scikit-learn.
*** Evaluated model performance with Mean Squared Error (MSE) and R-squared (R²) metrics.

## Findings
- Identified the top 10 cities with the highest average AQI.
- Discovered seasonal pollution trends, with specific months showing significantly higher AQI.
- Developed a predictive model for AQI based on PM2.5 and PM10 levels.

## Conclusion
This project provides valuable insights into air quality trends across major Indian cities. The analysis and predictive modeling can inform policymakers and stakeholders in devising strategies to improve air quality.

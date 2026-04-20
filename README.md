# Experiment-19-and-20
# COVID-19 Data Analysis

Experiment No.: 19 & 20

Name: Aanjneya Pankharaj
PRN: 25070123002
Batch: ENTC A1

# Overview

This experiment focuses on analysing a global COVID-19 dataset using Python and data analysis libraries. The objective is to clean, process, and extract meaningful insights such as country-wise statistics, active cases, and global distribution of confirmed cases.

# Dataset Description

The dataset used (covid_19_data.csv) contains worldwide COVID-19 records with the following attributes:

ObservationDate – Date of record
Province/State – State or province name
Country/Region – Country name
Confirmed – Total confirmed cases
Deaths – Total deaths
Recovered – Total recovered cases
Tools & Technologies Used
Python
Pandas (Data Analysis)
Plotly (Data Visualization)
Google Colab / Jupyter Notebook
🔧 Steps Performed
1. Data Loading
Imported dataset using Pandas
Displayed initial rows for inspection
2. Data Cleaning
Removed unnecessary columns (SNo, Last Update)
Checked missing values and data types
3. Data Type Conversion
Converted:
ObservationDate → DateTime
Confirmed, Deaths, Recovered → Integer
4. Feature Engineering
Created a new column:
Active Cases = Confirmed - Deaths - Recovered
5. Data Exploration
Identified latest available date in dataset
Extracted latest records
Counted:
Total countries (195)
Country-wise entries
6. Country-wise Analysis
Grouped data by country
Calculated total:
Confirmed cases
Deaths
Recovered cases
Active cases
Example:
India and Russia case analysis
7. Data Visualization
Created a world map (choropleth) showing confirmed cases using Plotly
8. Top Countries Analysis
Identified Top 20 countries based on:
Confirmed cases
Recovered cases
# Key Insights
The dataset contains records from January 2020 to May 2021
Total countries analysed: 195
Countries like US, India, and Brazil recorded the highest confirmed cases
Active cases provide better insight into current disease spread
Visualisation helps understand global impact effectively
# Conclusion

This experiment demonstrates how raw pandemic data can be transformed into meaningful insights through data cleaning, processing, and visualisation. It highlights the importance of data analysis in understanding global health crises and supports decision-making through statistical evidence.

# Future Scope
Time-series analysis of case trends
Predictive modelling using Machine Learning
Region-wise comparative analysis
Vaccination data integration

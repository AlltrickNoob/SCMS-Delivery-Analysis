Data Analysis and Cleaning of SCMS Delivery History Dataset
Project Overview
This project focuses on cleaning and analyzing the SCMS Delivery History Dataset, a comprehensive logistics dataset. The primary goal is to handle data quality issues, such as missing values, duplicates, and inconsistent data formats, to enable effective data-driven decision-making.
Key Objectives:
•	Identify and resolve missing data.
•	Remove duplicate records.
•	Enforce uniform data types.
•	Explore data to derive actionable insights.
________________________________________
Table of Contents
1.	Dataset Description
2.	Project Workflow
3.	Tools and Libraries
4.	File Structure
5.	Setup Instructions
6.	Key Results
7.	Future Recommendations
8.	References
________________________________________
Dataset Description
•	Dataset: SCMS Delivery History
•	Total Records: 10,324
•	Columns: 33 (including shipment modes, product details, and financial metrics)
•	Data Quality Issues:
o	Missing values in columns like Shipment Mode, Dosage, and Line Item Insurance.
o	Duplicated rows.
o	Mixed data types in several columns.
________________________________________
Project Workflow
1. Dataset Exploration:
•	Load data using pandas.
•	Display summary statistics.
•	Identify missing and inconsistent data.
•	Visualize numerical distributions and correlations using histograms and heatmaps.
2. Data Cleaning:
•	Handle Missing Values:
o	Drop columns with over 50% missing data.
o	Fill missing numerical values with the median.
o	Fill missing categorical values with the mode.
•	Remove Duplicates:Ensure unique records.
•	Data Type Enforcement:
o	Convert columns to appropriate data types.
•	Reset Index:
o	Re-index cleaned data for clarity.
3. Results and Insights:
•	Analyze trends in shipment modes, product delivery metrics, and financial distributions.
•	Generate a cleaned dataset for further use.
________________________________________
Tools and Libraries
•	Python: Programming language.
•	Libraries:
o	pandas: Data manipulation and cleaning.
o	matplotlib: Data visualization.
o	seaborn: Advanced visualizations.
________________________________________
File Structure
bash
Copy code
Project/
│
├── PROJECT REPORT.pdf           # Detailed project report
├── SCMS_Delivery_History_Dataset.csv  # Raw dataset
├── PROJECT DATA EXPLORATION AND DATA CLEANING.ipynb  # Jupyter notebook
├── README.md                    # This file
________________________________________
Setup Instructions
Prerequisites
•	Python 3.7 or higher.
•	Install required libraries:
bash
Copy code
pip install pandas matplotlib seaborn
Steps to Run
1.	Clone or download this repository.
2.	Open the PROJECT DATA EXPLORATION AND DATA CLEANING.ipynb notebook in Jupyter Notebook or any compatible IDE.
3.	Run the cells in order to:
o	Load and explore the dataset.
o	Perform data cleaning.
o	Save the cleaned dataset.
Outputs
•	Cleaned Dataset: SCMS_Cleaned_Dataset.csv
________________________________________
Key Results
•	Data Quality Improvements:
o	Resolved 360 missing entries in Shipment Mode.
o	Standardized data types across 33 columns.
o	Removed duplicate rows.
•	Insights:
o	Right-skewed distributions observed in Pack Price and Unit Price.
o	Strong correlation identified between Line Item Value and Line Item Quantity.
________________________________________
Future Recommendations
1.	Automation:
o	Develop scripts to handle real-time data updates.
2.	Advanced Analysis:
o	Implement predictive modeling for delivery schedule optimization.
3.	Visualization Dashboards:
o	Create interactive dashboards to present logistics insights.
________________________________________
References
1.	McKinney, W. Python for Data Analysis. O'Reilly Media, 2017.
2.	Seaborn Documentation
3.	Pandas Documentation


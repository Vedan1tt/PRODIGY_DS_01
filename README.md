Population Distribution Visualization
Overview

This project demonstrates data visualization using Python. It includes:

Population Distribution by Country (2023) using World Bank population data.
Age Distribution Visualization using a histogram.
Gender Distribution Visualization using a bar chart.

The project uses Pandas for data handling and Matplotlib for creating visualizations.

Project Structure
task1/
│
├── task1.py
├── age_gender_distribution.py
├── API_SP.POP.TOTL_DS2_en_csv_v2_282912.csv
├── Metadata_Country_API_SP.POP.TOTL_DS2_en_csv_v2_282912.csv
├── Metadata_Indicator_API_SP.POP.TOTL_DS2_en_csv_v2_282912.csv
├── chart_age_distribution.png
└── chart_gender_distribution.png
Features
1. Population Analysis
Reads World Bank population dataset.
Extracts population data for:
India
China
United States
Brazil
Nigeria
Displays a bar chart comparing their populations in 2023.
2. Age Distribution
Uses sample age data.
Creates a histogram showing age distribution.
3. Gender Distribution
Uses sample gender count data.
Creates a bar chart showing gender distribution.
Technologies Used
Python 3.x
Pandas
Matplotlib
Installation

Install required libraries:

pip install pandas matplotlib
Running the Project
Population Visualization
python task1.py
Age and Gender Distribution Visualization
python age_gender_distribution.py
Output
Population Distribution

Displays a bar chart comparing the population of selected countries in 2023.

Age Distribution

Generates:

chart_age_distribution.png
Gender Distribution

Generates:

chart_gender_distribution.png
Data Source

Population data obtained from the World Bank Open Data dataset:

Population, Total (SP.POP.TOTL)

Source: World Bank Open Data

Learning Outcomes
Data loading using Pandas
Data filtering and preprocessing
Creating histograms and bar charts
Saving visualizations as image files
Basic exploratory data analysis (EDA)


Author
Vedant Mule
Bachelor of Computer Application Student
Data Science Enthusiast

# A-B-Testing-Analysis
A/B Testing Analysis using Python, Statistics (Z-Test), Power BI, and Data Visualization.
# A/B Testing Analysis for Website Conversion Optimization

## Project Overview

This project analyzes the impact of a new website version on user conversion rates using A/B Testing. The objective is to determine whether the treatment group significantly improves conversions compared to the control group through statistical hypothesis testing and interactive business dashboards.

## Business Problem

Organizations frequently test multiple versions of a website or application to improve user engagement and conversion rates. This project evaluates whether the new website design performs better than the existing version using a Two-Proportion Z-Test and visual analytics.

## Objectives

- Analyze user conversion behavior.
- Compare Control and Treatment groups.
- Perform Exploratory Data Analysis (EDA).
- Conduct statistical hypothesis testing using a Two-Proportion Z-Test.
- Build an interactive Power BI dashboard for business insights.

## Dataset Information

The dataset contains 1,000 user records with the following attributes:

- User ID
- Group (Control / Treatment)
- Device
- Country
- Timestamp
- Converted (0 = No, 1 = Yes)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Jupyter Notebook
- Power BI

## Project Workflow

1. Data Collection
2. Data Loading
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Conversion Rate Analysis
6. Two-Proportion Z-Test
7. Business Insights
8. Power BI Dashboard

## Statistical Testing

**Null Hypothesis (H₀):**
There is no significant difference in conversion rates between the Control and Treatment groups.

**Alternative Hypothesis (H₁):**
The Treatment group has a significantly different conversion rate compared to the Control group.

A Two-Proportion Z-Test was used to validate the experimental results.

## Power BI Dashboard

The dashboard includes:

- Total Users
- Total Conversions
- Overall Conversion Rate
- Control Conversion Rate
- Treatment Conversion Rate
- Conversion Rate by Group
- Conversion Rate by Country
- Conversion Rate by Device
- Interactive Filters (Group, Device, Country)

## Key Insights

- Compared conversion rates between Control and Treatment groups.
- Measured overall website conversion performance.
- Analyzed conversion trends across countries and devices.
- Applied statistical testing to support business decision-making.
- Presented findings through an interactive Power BI dashboard.

## Project Structure

```
A_B_Testing_Analysis/
│
├── A_B_Testing_Analysis.ipynb
├── ab_testing_project.xlsx
├── A_B_Testing_Analysis_Dashboard.pbix
├── dashboard.png
└── README.md
```

## How to Run

1. Clone the repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run all notebook cells.
5. Open the Power BI dashboard (.pbix) to explore the interactive report.

## Author

**Ruchika Sinha**

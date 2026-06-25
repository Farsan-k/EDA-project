# Job Market Exploratory Data Analysis

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-success)

</p>

---

## Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of a real-world job market dataset to uncover trends in salaries, experience requirements, industries, locations, and hiring patterns.

The objective is to transform raw recruitment data into meaningful business insights through systematic data cleaning, preprocessing, statistical analysis, and visualization. The project follows an industry-standard data analysis workflow and demonstrates practical skills required for data analyst and data scientist roles.

---

## Problem Statement

Organizations generate massive amounts of recruitment data containing valuable insights about salaries, job demand, industries, and experience requirements. However, raw datasets often contain missing values, inconsistent formats, duplicates, and noisy information that limit effective decision-making.

This project aims to clean and analyze job market data to identify meaningful trends that can support job seekers, recruiters, HR teams, and business analysts.

---

## Solution

The project applies a structured exploratory data analysis pipeline that includes:

- Data cleaning
- Missing value treatment
- Feature engineering
- Statistical analysis
- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Business insight generation

The final output provides actionable insights into salary distribution, experience levels, industry demand, and hiring patterns.

---

## Features

- Complete data cleaning workflow
- Missing value handling
- Duplicate removal
- Feature engineering
- Statistical analysis
- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Salary trend analysis
- Industry-wise insights
- Location-based analysis
- Professional data visualizations
- Business insight generation

---

## Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Development Environment | Jupyter Notebook |
| Statistical Analysis | Descriptive Statistics |

---

## Project Structure

```text
EDA-project
│
├── data
│   ├── raw
│   │   └── job.zip
│   │
│   ├── interim
│   │   └── cleaned_day4.zip
│   │
│   └── processed
│       ├── cleaned_day1.zip
│       ├── cleaned_day2.zip
│       ├── cleaned_day3.zip
│       └── cleaned_day4.zip
│
├── notebooks
│   ├── 01_data_overview.ipynb
│   ├── 02_cleaning_preprocessing.ipynb
│   ├── 03_univariate_bivariate_eda.ipynb
│   └── 04_stats_time_features_final_insights.ipynb
│
├── reports
│   └── figures
│       ├── Distribution of Average Pay.png
│       ├── Boxplot of Average Pay.png
│       ├── Average Pay Distribution by Industry.png
│       ├── Average Pay Distribution by Role.png
│       ├── Correlation Between Experience and Pay.png
│       └── Number of Job Postings.png
│
└── README.md
```

---

## Dataset

The project uses a real-world job market dataset containing recruitment information from various companies and industries.

### Dataset Features

- Job Title
- Company
- Industry
- Job Location
- Experience
- Salary
- Employment Type
- Skills
- Posting Date
- Additional Job Information

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/EDA-project.git

cd EDA-project
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate the environment

**Windows**

```bash
.venv\Scripts\activate
```

**Linux/macOS**

```bash
source .venv/bin/activate
```

Install required libraries

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Exploratory Data Analysis Workflow

```text
Raw Dataset
      │
      ▼
Data Loading
      │
      ▼
Data Inspection
      │
      ▼
Data Cleaning
      │
      ▼
Missing Value Treatment
      │
      ▼
Duplicate Removal
      │
      ▼
Feature Engineering
      │
      ▼
Univariate Analysis
      │
      ▼
Bivariate Analysis
      │
      ▼
Correlation Analysis
      │
      ▼
Statistical Analysis
      │
      ▼
Business Insights
```

---

## Data Cleaning

The preprocessing pipeline includes:

- Missing value treatment
- Duplicate removal
- Data type conversion
- Standardizing categorical values
- Salary data cleaning
- Experience column transformation
- Industry normalization
- Outlier detection
- Data validation

---

## Exploratory Data Analysis

The project analyzes several aspects of the dataset, including:

- Salary distribution
- Industry distribution
- Job location trends
- Experience requirements
- Hiring demand
- Company-wise openings
- Correlation between experience and salary
- Top-paying industries
- Most demanded job roles

---

## Visualizations

The project includes professional visualizations such as:

- Salary Distribution
- Boxplots
- Histogram Analysis
- Correlation Heatmaps
- Industry-wise Salary Comparison
- Experience vs Salary Scatter Plot
- Job Posting Distribution
- Location-wise Hiring Analysis

---

## Statistical Analysis

Statistical techniques applied include:

- Mean
- Median
- Mode
- Standard Deviation
- Variance
- Quartiles
- Percentiles
- Correlation Analysis
- Outlier Detection using IQR

---

## Key Insights

Some of the insights generated include:

- High-paying industries
- Salary variation across locations
- Relationship between experience and salary
- Most active hiring locations
- Frequently advertised job roles
- Distribution of experience requirements
- Industry-wise recruitment patterns

---

## Business Applications

The findings from this analysis can support:

- HR Analytics
- Recruitment Planning
- Salary Benchmarking
- Workforce Planning
- Job Market Research
- Talent Acquisition
- Business Intelligence
- Career Guidance Platforms

---

## Skills Demonstrated

- Python Programming
- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis
- Feature Engineering
- Statistical Analysis
- Data Visualization
- Business Analytics
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Future Improvements

Future enhancements may include:

- Interactive Power BI dashboard
- Tableau visualization
- Streamlit dashboard
- Automated EDA report generation
- SQL database integration
- Predictive salary modeling
- Machine Learning integration
- Real-time recruitment analytics

---

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch.
5. Submit a Pull Request.

---

## License

This project is licensed under the MIT License.

---

## Author

**Farsan K**

Aspiring Data Scientist | Machine Learning Engineer

**GitHub:** https://github.com/Farsan-k

**LinkedIn:** https://www.linkedin.com/in/farsank/

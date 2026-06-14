# Demographic Data Analyzer

A Python data analysis project that uses Pandas to analyze demographic information from the 1994 Census dataset. This project is part of the freeCodeCamp Data Analysis with Python certification and demonstrates practical data manipulation, aggregation, filtering, and summary-statistics skills.

## Project Objective

The objective of this project is to extract meaningful demographic insights from census data using Python and Pandas. The analysis focuses on race distribution, education level, income, working hours, country-level income patterns, and occupation trends.

## Dataset

- Dataset: 1994 Census / Adult Income dataset
- File: `adult.data.csv`
- Main target column: income category (`<=50K` or `>50K`)
- Key feature categories:
  - Age
  - Race
  - Education
  - Occupation
  - Native country
  - Working hours per week
  - Salary group

## Questions Answered

The analysis answers the following questions:

- How many people of each race are represented in the dataset?
- What is the average age of men?
- What percentage of people have a Bachelor's degree?
- What percentage of people with advanced education earn more than 50K?
- What percentage of people without advanced education earn more than 50K?
- What is the minimum number of hours worked per week?
- What percentage of people who work minimum hours earn more than 50K?
- Which country has the highest percentage of people earning more than 50K?
- What is the most popular occupation for people earning more than 50K in India?

## Tech Stack

- Python
- Pandas
- Unit testing

## Project Structure

```text
demographic-data-analyzer/
│
├── adult.data.csv                  # Dataset
├── demographic_data_analyzer.py    # Main analysis logic
├── main.py                         # Script for running the analysis
├── test_module.py                  # Unit tests
└── README.md                       # Project documentation
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Sudinupadhaya/demographic-data-analyzer.git
cd demographic-data-analyzer
```

### 2. Install dependencies

```bash
pip install pandas
```

### 3. Run the project

```bash
python main.py
```

### 4. Run tests

```bash
python -m unittest test_module.py
```

## Output

The analysis returns a dictionary containing:

- `race_count`
- `average_age_men`
- `percentage_bachelors`
- `higher_education_rich`
- `lower_education_rich`
- `min_work_hours`
- `rich_percentage`
- `highest_earning_country`
- `highest_earning_country_percentage`
- `top_IN_occupation`

## Skills Demonstrated

This project demonstrates:

- Data loading with Pandas
- Data filtering
- Grouping and aggregation
- Percentage calculation
- Conditional analysis
- Working with categorical data
- Writing clean analysis functions
- Validating results using tests

## Why This Project Matters

This project shows the ability to work with real tabular data and answer business-style analytical questions using Python. These are core skills for data analyst, business analyst, and junior data science roles.

## Author

**Sudin Upadhaya**

- GitHub: Sudinupadhaya
- Focus areas: Data Analysis, Python, Machine Learning, and Software Engineering

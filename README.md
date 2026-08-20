# Thinking in Terms of Data

Before writing a single line of code, you must learn to **think like a data person**. This repository covers the entire lifecycle of working with data -- from collecting it to presenting your findings.

## Contents

| Notebook | Description |
|----------|-------------|
| [`index.ipynb`](index.ipynb) | Comprehensive guide covering data collection, cleaning, analysis, and visualization with theory, code examples, and practical assignments |
| [`thinking data.ipynb`](thinking data.ipynb) | Hands-on assignments for data cleaning, insight extraction, and building a rule-based recommendation system |
| [`sample/data.json`](sample/data.json) | Sample messy dataset used in the assignments |

## Topics Covered

### 1. Data Collection
- Types of data (quantitative, qualitative, structured, unstructured)
- Common data sources (files, databases, APIs, web scraping, surveys)
- Primary vs secondary data collection
- Data quality dimensions (accuracy, completeness, consistency, timeliness)
- Best practices and common mistakes

### 2. Data Cleaning (Pre-Processing)
- Data profiling and the cleaning workflow
- Handling missing values (mean, median, mode, forward fill)
- Removing duplicates
- Fixing inconsistent formats (casing, whitespace, synonyms)
- Detecting and handling outliers (IQR method)
- Data transformation (encoding, scaling, feature engineering)

### 3. Data Analysis
- Types of analysis (descriptive, diagnostic, predictive, prescriptive)
- Exploratory Data Analysis (EDA)
- Measures of central tendency (mean, median, mode)
- Measures of spread (range, variance, standard deviation, IQR)
- Correlation and its interpretation
- Statistical significance and hypothesis testing

### 4. Data Visualization
- Choosing the right chart for your question
- Principles of good visualization (clarity, honesty, accessibility)
- Common visualization mistakes to avoid
- Dashboard design best practices
- Telling a story with data

## Practical Assignments

Each section in `index.ipynb` includes a real-world scenario with hands-on assignments:

| Assignment | Scenario | Skills Practiced |
|------------|----------|------------------|
| **FreshCart** | Organize scattered customer/order data from Google Sheets, WhatsApp, and Excel | Data collection, source analysis, unification |
| **HealthFirst Clinic** | Clean messy patient appointment data | Duplicates, formatting, missing values, outliers |
| **BrightStar Electronics** | Analyze 15 days of e-commerce sales data | Central tendency, spread, correlation, outliers |
| **CityBike Rentals** | Create text-based visualizations of rental data | Line charts, bar charts, histograms, storytelling |

## Assignments in `thinking data.ipynb`

| Assignment | Task |
|------------|------|
| **Assignment 1** | Clean and structure messy user feedback data (mixed types, missing values, duplicates) |
| **Assignment 2** | Extract insights: average rating, percentage of poor ratings |
| **Assignment 3** | Build a rule-based product recommendation feature |

## Requirements

- Python 3.14+
- Jupyter Notebook / JupyterLab
- No external libraries required -- all code uses plain Python

## Getting Started

1. Clone this repository
2. Open `index.ipynb` for the full educational guide
3. Open `thinking data.ipynb` for the hands-on assignments
4. Run all cells in order to see the output

## Data Thinking Framework

```
Question --> Collect --> Clean --> Analyze --> Visualize --> Decide
    ^                                                       |
    +-------------------------------------------------------+
                  (Iterate as needed)
```

---
title: 'Data Science'
---

Portfolio projects and technical work in data analysis, statistics, SQL, and machine learning.

## Selected projects

### [Stack Overflow Data Analysis in BigQuery](https://console.cloud.google.com/bigquery)

An analysis of Stack Overflow data using BigQuery to investigate questions such as which programming languages are trending. The project combines SQL exploration with pandas-style transformations and visual analysis of query results. The code can be viewed at [Google Colab](https://colab.research.google.com/drive/1_SOlTZU_An0-FgK6kw2KDdsT8KCNCMHv?usp=sharing).

**Objectives:** Identify trends in programming language popularity and explore patterns in the Stack Overflow dataset.

**Skills:** Query data using SQL cells; clean and transform data using the BigQuery DataFrames (pandas) API; visualize query results using Visualization cells.

![Stack Overflow analysis in BigQuery](/images/bigquery_stackoverflow.png)

### [NYC Payroll Analysis](https://github.com/santimda/NYC-payroll-data-analysis)

An end-to-end analysis of approximately two million NYC payroll records. The project combines PostgreSQL data preparation with Python exploratory analysis and a Random Forest regression model for total income. It examines salary distributions, job titles, boroughs, hours worked, overtime, and tenure, with an emphasis on a clear and reproducible workflow.

**Skills:** PostgreSQL, SQL data cleaning, feature engineering, Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, regression, model evaluation, Looker Studio.

![NYC payroll model performance](/images/model_performance.png)

### [Mock Salaries](https://github.com/santimda/mock_salaries)

A controlled machine-learning experiment using a synthetic salary dataset with a known ground-truth generating process. Ridge Regression, Random Forest, and Gradient Boosting models are compared not only by predictive performance, but also by how well they recover the true salary drivers and expose proxy variables and bias.

**Skills:** Python, synthetic data generation, feature engineering, preprocessing, Ridge Regression, Random Forest, Gradient Boosting, model comparison, feature importance, interpretability, regression diagnostics.

![Comparison of feature importance across salary models](/images/feature_importance_comparison.png)

### [Data Science Job Market Analysis](https://github.com/santimda/data_science_job_market_analysis)

An analysis of approximately 786,000 Data Science job postings from the US and Europe. It compares requested skills, job-posting characteristics, and reported salaries, while carefully treating salary results as associations within a small reported-salary subset rather than causal effects.

**Skills:** Python, pandas, NumPy, Matplotlib, Seaborn, Hugging Face Datasets, exploratory data analysis, data visualisation, salary analysis, uncertainty-aware interpretation.

![Skills and salary associations in the European data science job market](/images/06_skills_salary_europe.png)

---
title: 'Data Science'
---

Portfolio projects and technical work in data analysis, statistics, SQL, and machine learning.

## Selected projects

### [Stack Overflow Data Analysis in BigQuery](https://console.cloud.google.com/bigquery)

An analysis of Stack Overflow data using BigQuery to investigate questions such as which programming languages are trending. The project combines SQL exploration with pandas-style transformations and visual analysis of query results. The code can be viewed at [Google Colab](https://colab.research.google.com/drive/1_SOlTZU_An0-FgK6kw2KDdsT8KCNCMHv?usp=sharing).

**Objective:** Identify trends in programming language popularity and explore patterns in the Stack Overflow dataset.

**Approach and result:** Query the public dataset in SQL, transform the results with the BigQuery DataFrames (pandas) API, and visualise the resulting trends. **Tools:** BigQuery, SQL, pandas-style transformations. **Code:** [Google Colab](https://colab.research.google.com/drive/1_SOlTZU_An0-FgK6kw2KDdsT8KCNCMHv?usp=sharing).

![Stack Overflow analysis in BigQuery](/images/bigquery_stackoverflow.png)

### [NYC Payroll Analysis](https://github.com/santimda/NYC-payroll-data-analysis)

**Objective:** Analyse approximately two million NYC payroll records and understand which factors relate to total income. **Approach:** Prepare data in PostgreSQL, explore it in Python, and compare a Random Forest regression workflow. **Result:** The analysis examines salary distributions, job titles, boroughs, hours worked, overtime, and tenure in a reproducible workflow. **Tools:** PostgreSQL, SQL, Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Looker Studio. **Code:** [GitHub](https://github.com/santimda/NYC-payroll-data-analysis).

![NYC payroll model performance](/images/model_performance.png)

### [Mock Salaries](https://github.com/santimda/mock_salaries)

**Objective:** Test whether models can recover known salary drivers without hiding proxy variables or bias. **Approach:** Generate a synthetic dataset with a known ground truth and compare Ridge Regression, Random Forest, and Gradient Boosting by both predictive performance and interpretability. **Result:** The controlled experiment makes model behaviour and feature-importance differences explicit. **Tools:** Python, feature engineering, preprocessing, scikit-learn, regression diagnostics. **Code:** [GitHub](https://github.com/santimda/mock_salaries).

![Comparison of feature importance across salary models](/images/feature_importance_comparison.png)

### [Data Science Job Market Analysis](https://github.com/santimda/data_science_job_market_analysis)

**Objective:** Compare requested skills, posting characteristics, and reported salaries across approximately 786,000 Data Science job postings from the US and Europe. **Approach:** Clean and explore the postings, then analyse salary associations while treating the reported-salary subset as limited evidence rather than causal data. **Result:** The project identifies patterns in skill demand and reported compensation with explicit uncertainty-aware interpretation. **Tools:** Python, pandas, NumPy, Matplotlib, Seaborn, Hugging Face Datasets. **Code:** [GitHub](https://github.com/santimda/data_science_job_market_analysis).

![Skills and salary associations in the European data science job market](/images/06_skills_salary_europe.png)

---
title: 'Data Science'
---

Portfolio projects and technical work in data analysis, statistics, SQL, and machine learning.

<div class="data-science-page">

## [Stack Overflow Data Analysis in BigQuery](https://console.cloud.google.com/bigquery)

An analysis of Stack Overflow data using BigQuery to investigate questions such as which programming languages are trending. The project combines SQL exploration with pandas-style transformations and visual analysis of query results. The code can be viewed at [Google Colab](https://colab.research.google.com/drive/1_SOlTZU_An0-FgK6kw2KDdsT8KCNCMHv?usp=sharing).

**Tools:** BigQuery, SQL, pandas-style transformations, visualization cells (screenshot below).

![Stack Overflow analysis in BigQuery](/images/bigquery_stackoverflow.png)


## [NYC Payroll Analysis](https://github.com/santimda/NYC-payroll-data-analysis)

Analysis of approximately two million NYC payroll records and understand which factors relate to total income. Public repository to the project in [GitHub](https://github.com/santimda/NYC-payroll-data-analysis).

**Approach:** Prepare data in PostgreSQL, explore it in Python, and compare a Random Forest regression workflow. Prepare a dashboard to visualize main findings.

**Result:** The analysis examines salary distributions, job titles, boroughs, hours worked, overtime, and tenure in a reproducible workflow.

**Tools:** PostgreSQL, SQL, Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Looker Studio.

![NYC payroll model performance](/images/model_performance.png)


## [Mock Salaries](https://github.com/santimda/mock_salaries)

Experiment to test whether models can recover known salary drivers without hiding proxy variables or bias. Public repository to the project in [GitHub](https://github.com/santimda/mock_salaries).

**Approach:** Generate a synthetic dataset with a known ground truth and compare Ridge Regression, Random Forest, and Gradient Boosting by both predictive performance and interpretability.

**Result:** The controlled experiment makes model behaviour and feature-importance differences explicit.

**Tools:** Python, feature engineering, preprocessing, scikit-learn, regression diagnostics.


![Comparison of feature importance across salary models](/images/feature_importance_comparison.png)


## [Data Science Job Market Analysis](https://github.com/santimda/data_science_job_market_analysis)

Compare requested skills, posting characteristics, and reported salaries across approximately 786,000 Data Science job postings from the US and Europe. Public repository to the project in [GitHub](https://github.com/santimda/data_science_job_market_analysis).

**Approach:** Clean and explore the postings, then analyse salary associations while treating the reported-salary subset as limited evidence rather than causal data.

**Result:** The project identifies patterns in skill demand and reported compensation with explicit uncertainty-aware interpretation.

**Tools:** Python, pandas, NumPy, Matplotlib, Seaborn, Hugging Face Datasets.

![Skills and salary associations in the European data science job market](/images/06_skills_salary_europe.png)

</div>

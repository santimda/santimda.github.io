# PROJECT_CONTEXT.md

## Project: Personal Professional Website

### Owner

Santiago del Palacio — astrophysicist transitioning into data science and machine learning.

### Purpose

Build a professional personal website that presents Santiago's background coherently across two related areas:

1. **Astronomy / Astrophysics** — established research career and scientific work.
2. **Data Science / Machine Learning** — current professional transition, portfolio projects, and practical technical work.

The website should function as a canonical, coherent portfolio for data-science/ML job applications while preserving the credibility and depth of the existing astronomy career. 

The site should tell a coherent story rather than looking like an astronomy CV with a disconnected collection of beginner ML exercises.

---

## Background

- PhD in Astronomy, defended in November 2018.
- 7 years of postdoctoral research experience.
- Former postdoctoral researcher at Chalmers University of Technology, Sweden (2022–2026).
- Previous postdoctoral research at the Instituto Argentino de Radioastronomía (2019–2022).
- Research experience includes:
  - radio astronomy
  - high-energy astrophysics
  - AGN
  - tidal disruption events
  - pulsar timing
  - cosmic rays
  - spectral energy distribution modelling
  - observational astronomy
- Extensive experience working with complex scientific datasets from instruments/telescopes including IAR, VLA, ALMA, Swift, XMM-Newton, NuSTAR and Chandra.
- 60+ peer-reviewed publications, including 8 first-author papers.
- PI on 17 observing proposals and participant in 40+ proposals.
- Strong quantitative and scientific programming background.

The astronomy background should be presented as relevant evidence of quantitative reasoning, data analysis, modelling, statistics, scientific programming, and problem solving—not hidden or minimized.

---

## Data Science Transition

Santiago is transitioning from academic astronomy into industry-oriented data science / machine learning.

Current learning and portfolio focus:

- Python
- SQL
- pandas
- data analysis and visualization
- statistics
- scikit-learn
- machine learning fundamentals
- data engineering concepts where useful
- Git/GitHub
- eventually potentially deployment/cloud/end-to-end ML workflows

Current SQL experience includes PostgreSQL, DuckDB and BigQuery.

Current ML work includes:
- regression
- classification
- preprocessing and feature transformations
- cross-validation
- ensemble methods
- PCA
- anomaly detection
- model evaluation
- statistical interpretation of results

The portfolio should demonstrate practical competence and sound reasoning, not merely library usage.

---

## Website Concept

The website should have a clear personal identity rather than feeling like two unrelated websites.

Suggested homepage concept:

    SANTIAGO DEL PALACIO
    Scientist · Data Science · Machine Learning

    [ Data Science ]    [ Astronomy ]

Data Science should probably be presented first while Santiago is actively transitioning careers.

Astronomy remains an important part of the site because it establishes the depth of his scientific and quantitative experience.

Possible navigation:

- Home
- Data Science
  - Projects
  - Skills / approach (optional)
- Astronomy
  - Research
  - Publications
  - Selected projects
- About / CV
- Contact

Keep navigation simple. Avoid unnecessary sections.

---

## Data Science Portfolio Philosophy

The portfolio should prioritize **a small number of strong, well-explained projects** over many superficial projects.

Each project should ideally explain:

1. **Problem** — What question is being addressed?
2. **Data** — Where the data came from, its structure and relevant limitations.
3. **Approach** — SQL, cleaning, EDA, statistics, modelling, etc.
4. **Results** — Important plots, tables and conclusions.
5. **Reasoning / lessons learned** — Explain important modelling or analytical decisions.
6. **Code** — Link to the relevant GitHub repository.

The portfolio should show how Santiago thinks about data, not just that he can execute Python/sklearn commands.

Projects currently available or under development include:

### 1. NYC Payroll / Salary Data Analysis

A SQL/data-analysis project involving a large NYC payroll dataset.

Relevant skills:
- SQL
- PostgreSQL
- data cleaning
- aggregation
- exploratory analysis
- pandas
- visualization

### 2. Data Scientist Job/Salaries Analysis

Analysis of Data Scientist job postings and their associated skills/salaries.

Example analysis:
- frequency of skills in job postings
- median salary associated with skills
- salary distributions and uncertainty
- relationship between skill frequency and salary

Technologies:
- Python
- pandas
- SQL
- visualization

### 3. Machine Learning Salary Prediction

Synthetic salary dataset used to explore:
- preprocessing
- numerical scaling
- categorical encoding
- transformations such as QuantileTransformer
- Ridge regression
- Random Forest
- Gradient Boosting
- model comparison and evaluation

### 4. Classification / Ensemble Experiments

Experiments using scikit-learn datasets such as digits, including:
- Logistic Regression
- Random Forest
- SVC
- Gradient Boosting
- voting ensembles
- stacking

These may be useful as learning projects but should only appear prominently on the website if they can be presented with a meaningful question and interpretation.


---

## Professional Narrative

The website should communicate a straightforward transition:

Santiago has spent years extracting information from complex observational datasets, developing quantitative models, performing statistical analysis and interpreting uncertain measurements in astrophysics. He is now applying that analytical background to data science and machine learning.

Possible conceptual wording:

> My research career has involved extracting physical information from complex observational datasets, developing quantitative models, and working extensively with Python and statistical methods. I am now applying this analytical background to problems in data science and machine learning.

Do not overuse this wording or make the transition sound artificial.

Avoid generic LinkedIn-style buzzwords such as:
- passionate about leveraging cutting-edge AI
- data-driven solutions
- transforming businesses through innovation
- results-oriented professional
- passionate data scientist

The writing should be concrete, technical and credible.

---

## Design / Tone

The website should feel:

- professional
- clean
- modern
- technically credible
- understated
- easy to navigate
- appropriate for both technical recruiters and scientists

Avoid:
- excessive animations
- flashy startup aesthetics
- generic AI imagery
- excessive gradients
- buzzword-heavy copy
- unnecessary visual complexity

The astronomy section can retain some scientific/technical character, while the data-science section should look like a professional technical portfolio.

Prioritize readability and information hierarchy.

---

## Technical Direction

The site is currently being developed locally.

The development environment may use OpenCode as the coding assistant.

Important principle:

**Keep project-specific decisions and context in this repository rather than relying on conversational memory.**

This file is the initial shared context for AI coding assistants.

As the project develops, update this file with:
- chosen framework
- directory structure
- design decisions
- typography
- color palette
- deployment target
- content structure
- completed projects
- outstanding tasks

Do not make large architectural changes without first considering the existing project structure.

---

## GitHub / Project Presentation

Data Science projects should generally link to GitHub repositories.

Where appropriate, project pages can include:
- concise code excerpts
- plots
- methodology
- results
- links to notebooks/repositories

The website itself should remain focused on communicating the work. It should not simply reproduce a Jupyter notebook.


---

## Existing Website

The previous personal website was hosted on Google Sites:

https://sites.google.com/view/santiagodelpalacio-astro

It can be used as a reference for existing astronomy content, but the new site does not need to preserve its design.

---

## Working Principles for AI Coding Assistants

When modifying this project:

1. Read this file first.
2. Inspect the existing code before proposing changes.
3. Prefer simple, maintainable solutions.
4. Do not introduce unnecessary dependencies.
5. Preserve existing functionality unless explicitly asked to change it.
6. Explain significant architectural decisions briefly.
7. Avoid generating large amounts of placeholder content.
8. Do not invent professional experience, projects, publications, skills or achievements.
9. Keep technical claims accurate.
10. When uncertain about content, ask rather than fabricate.
11. Optimize for a professional portfolio suitable for Data Scientist / ML / quantitative roles while retaining the astronomy identity.

---

## Current Status

This is the initial planning/context document.

The next stage is to choose the website technology and establish the local project structure, then begin implementing the homepage and the Astronomy/Data Science separation. The preferred option is using Hugo Hero.

---

## Hosting / Deployment

The website should be hosted for free using GitHub Pages.

The source code should live in a public GitHub repository, with the deployed website served through GitHub Pages using the URL `santimda.github.io`.

Do not introduce paid hosting, subscriptions, or infrastructure.

The deployment workflow should be as simple as possible, preferably:
- Git repository on GitHub
- automatic build/deployment through GitHub Actions or the framework's supported GitHub Pages workflow
- HTTPS enabled through GitHub Pages

A custom domain may be considered later, but is not required initially.
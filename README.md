# Caduceus — Mental Health App Survey Analysis

A work-in-progress research project investigating **mental health app adoption, attitudes, trust, and usage among Vietnamese young adults**.

The project analyzes survey data to better understand how young people perceive and engage with digital mental health tools, with the broader goal of informing the design and development of accessible mental health technology.

> **Status:** Work in progress

## Research Focus

The analysis investigates several aspects of mental health app adoption, including:

- Attitudes toward seeking professional psychological help
- Trust in mental health applications
- Interest in using digital mental health tools
- Current mental health app usage
- Desired application features
- Demographic and socioeconomic factors associated with adoption

## Data

The project uses survey responses collected as part of Caduceus's research on digital mental health among Vietnamese young adults.

The analysis pipeline includes:

- Data cleaning and filtering
- Demographic recoding
- Likert-scale transformation
- Descriptive statistics
- Scale construction
- Correlation and statistical analysis
- Structural equation modeling (SEM)

The current analysis includes **406 participants aged 18 and older** after data cleaning and eligibility filtering.

## Analysis

The primary analysis is implemented in Python using Jupyter Notebook.

The workflow includes:

```text
Survey Responses
       │
       ▼
Data Cleaning
       │
       ▼
Demographic & Scale Recoding
       │
       ▼
Descriptive Analysis
       │
       ▼
Statistical Analysis
       │
       ▼
Structural Equation Modeling
       │
       ▼
Research Findings
```
## Tools

- Python
- Jupyter Notebook
- pandas
- NumPy
- SciPy
- matplotlib
- seaborn
- semopy
- Graphviz

## Repository Structure

```text
├── data/
│   └── Source survey data
│
├── caduceus_survey.ipynb
│   └── Data cleaning and statistical analysis
│
├── caduceus_data_cleaned.csv
│   └── Processed analysis dataset
│
├── cleaned_mental_health_survey.csv
│   └── Cleaned survey dataset
│
└── sem_model_plot
    └── SEM visualization
```
## Project Status

This repository represents an ongoing research project. Analysis, modeling, and documentation are subject to change as the research develops.

## Context

Developed as part of research work with **Caduceus**, a digital health startup focused on mental health technology.

This repository contains work in progress and should not be interpreted as a finalized research publication.

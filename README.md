# Africa Financial Aid Allocation Using Machine Learning and Optimization

This project applies machine learning and mathematical optimization to explore how international aid resources could be allocated across African countries to improve quality of life, measured using the Human Development Index (HDI).

The work was completed as part of a Machine Learning and Analytics course project in Fall 2022.

---

## Project Overview

International aid organizations operate under strict budget constraints and must decide how to distribute limited funding across competing development programs such as healthcare, sanitation, and clean water access.

This project addresses two core questions:

- Can HDI be predicted using country-level features that are directly influenced by financial aid?
- How should a fixed aid budget be optimally allocated across different interventions to maximize predicted HDI improvement?

The analysis focuses on African countries and combines data engineering, predictive modeling, and constrained optimization.

---

## Methods Used

### Exploratory Data Analysis
- Data integration from multiple sources  
- Country name standardization  
- Missing value handling  
- Feature engineering and scaling  
- Distribution analysis  

### Machine Learning
- Linear regression models  
- Cross-validation  
- Feature importance analysis  

### Optimization
- Linear programming formulation  
- Budget constraints  
- Allocation caps and diversification rules  
- Sensitivity analysis  

---

## Repository Contents

- `Africa_Financial_Aid_Optimization_Report.pdf`  
  Final written report describing methodology, modeling decisions, and findings.

- `hdi_prediction_and_optimization.ipynb`  
  Jupyter notebook containing data cleaning, regression modeling, and optimization.

- `data/`  
  CSV datasets used in the analysis:
  - `hdi_by_country.csv`
  - `life_expectancy.csv`
  - `water_sanitation_access.csv`
  - `country_continent_mapping.csv`

---

## Tools and Technologies

- Python  
- pandas  
- numpy  
- scikit-learn  
- cvxpy  
- matplotlib  
- Jupyter Notebook  

---

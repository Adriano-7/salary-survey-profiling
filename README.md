# Data Profiling of a Salary Survey  

## Description  
This project performs **data profiling** on a salary survey dataset sourced from [Ask A Manager](https://www.askamanager.org/2021/04/how-much-money-do-you-make-4.html). It analyzes over **28,000 records** spanning multiple industries, countries, job titles, and demographic variables. The focus is on identifying and resolving data quality issues to ensure accurate insights and fair analysis of salary trends.

Key issues tackled:  
- **Standardization challenges** in categorical variables (e.g., inconsistent country names).  
- **Salary data formatting inconsistencies**, which complicate numerical analysis.  
- **Demographic imbalances**, with underrepresentation of some groups, impacting analysis fairness.

## Features  
- **Data Cleaning & Preprocessing:** Standardizing text fields and numerical formats.  
- **Exploratory Data Analysis (EDA):** Visualizing key demographic distributions.  
- **Association Analysis:** Using **Cramér’s V** to measure correlations between categorical variables.  
- **Recommendations:** Suggestions to improve data quality and representation for future analyses.

## Setup and Usage  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/Adriano-7/salary-survey-profiling
   cd salary-survey-profiling
   ```
3. **Run the Jupyter Notebook:**  
   ```bash
   jupyter notebook T01_Assignment_Notebook.ipynb
   ```

## Dependencies  
- **Jupyter Notebook**  
- **pandas**  
- **numpy**  
- **matplotlib**  
- **seaborn**  

## Contact  
Developed by **Adriano Machado**  
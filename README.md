# IIMA_Data_Intern_Project
This project involves estimating a modified Keynesian consumption function using household-level data. 
The analysis is conducted in Python and aims to assess the relationship between income and consumption, controlling for gender. 
The project is part of a technical assessment for a research internship opportunity at the Indian Institute of Management Ahmedabad (IIMA).

**Objective**:
To estimate the Marginal Propensity to Consume (MPC) based on the economic model:

Consumption = α + β₁ * Income + β₂ * Gender + ε
Where:
1. `Income`: Annual household income
2. 'Gender`: Dummy variable (1 = Male, 0 = Not Male)
3. `Consumption`: Annual household consumption
4. `ε`: Error term


# Key Tasks

1. **Data Cleaning and Summary Statistics**
   - Handled missing/infinite values
   - Computed descriptive statistics for all variables

2. **Distribution Analysis**
   - Created a normalized histogram of income
   - Fitted both **Lognormal** and **Gamma** distributions using Maximum Likelihood Estimation
   - Compared fits based on log-likelihood values

3. **Regression Analysis**
   - Performed OLS regression to estimate MPC
   - Controlled for gender as a dummy variable
   - Interpreted results in context of economic literature

4. **Report Generation**
   - Developed a polished, publication-ready report with visualizations and formatted regression outputs
   - Report provided in both `.docx` and `.tex` formats
   - Python code included in the appendix


 ## Author

**Sheehan Mathur**  
BITS Pilani Dubai Campus  
📧 sheehan.mathur@gmail.com

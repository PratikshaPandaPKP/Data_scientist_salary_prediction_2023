# Data_scientist_salary_prediction_2023
Created this project on May 2023.


Data Science Job Salaries Dataset contains 11 columns, each are:-
work_year: The year the salary was paid.
experience_level: The experience level in the job during the year
employment_type: The type of employment for the role
job_title: The role worked in during the year.
salary: The total gross salary amount paid.
salary_currency: The currency of the salary paid as an ISO 4217 currency code.
salaryinusd: The salary in USD
employee_residence: Employee's primary country of residence in during the work year as an ISO 3166 country code.
remote_ratio: The overall amount of work done remotely
company_location: The country of the employer's main office or contracting branch
company_size: The median number of people that worked for the company during the year


Sure, here's a concise summary of the analysis and modeling process:

1. **Data Preparation and Visualization**:
   - Visualized key variables like `remote_ratio`, `company_location`, and `company_size`.
   - Transformed categorical variables into dummy variables.
   - Simplified job titles and handled high cardinality categorical variables.

2. **Descriptive Statistics**:
   - Described the dataset's central tendency, dispersion, and distribution shape.
   - Encoded binary variables for features like `employee_residence`, `company_location`, and `salary_currency`.

3. **Model Development**:
   - Built an initial Linear Regression model using all features, resulting in moderate fit.
   - Conducted feature selection using RandomForestClassifier to identify important features.
   - Trained a new Linear Regression model with selected features.
   - Conducted multicollinearity check using Variance Inflation Factor (VIF).

4. **Model Evaluation**:
   - The initial and new Linear Regression models yielded relatively low accuracy scores.
   - The new model, trained with selected features, showed a decrease in performance compared to the initial model.

5. **Conclusions and Recommendations**:
   - Model performance suggests that linear regression may not effectively capture the relationship between predictors and the target variable.
   - Next steps include exploring non-linear models like decision trees or neural networks, addressing heteroscedasticity, feature engineering, and utilizing cross-validation techniques.

Overall, while the analysis provided insights into the dataset and initial modeling attempts were made, further exploration and refinement of modeling techniques are needed to improve predictive performance.

Created this project on May 2023.

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

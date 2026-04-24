### End-to-End Predictive Modeling: Hotel Reservation Cancellation Analysis

**Tools: Python, Pandas, NumPy, SciPy, Statsmodels, Scikit-learn, Matplotlib, Seaborn**  

**Techniques: Data Cleaning, Exploratory Data Analysis (EDA), Feature Engineering, Logistic Regression, Feature Selection (VIF, Correlation Matrix, Backward Elimination), Multicollinearity Analysis, Model Evaluation, Data Visualization**  

- Conducted an end-to-end data analysis and predictive modeling project to identify factors influencing hotel reservation cancellations and estimate cancellation likelihood
- Sourced and analyzed a Kaggle dataset containing 36,275 observations and 19 variables, including both categorical and numerical features
- Performed data cleaning and preprocessing, including duplicate/null checks, variable transformation, and creation of new engineered features to improve model usability
- Conducted exploratory data analysis (EDA) with statistical summaries, bivariate visualizations, and distribution analysis to identify potential predictors  
- Addressed multicollinearity using correlation heatmaps and Variance Inflation Factor (VIF), applying a threshold of 5 for feature reduction 
- Built a logistic regression model and applied backward stepwise elimination to retain only statistically significant variables at a 95% confidence level  
- Derived and interpreted the final log-odds equation to quantify how key variables influence the probability of reservation cancellation 
- Identified significant predictors, including:
  - Negative impact: repeated guests, parking requirement, special requests  
  - Positive impact: online reservations, longer lead time, higher room price 
- Generated predictive scenarios, showing cancellation likelihood ranging from ~6% (low-risk) to ~84% (high-risk) depending on customer characteristics 
- Delivered actionable business insights to support revenue optimization, occupancy planning, and risk mitigation strategies in the hotel industry 

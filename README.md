# Assignment #2 Repository

The csv file for `cohort` in the `raw-data` folder includes 5,000 observations with variables `smoke`, `female`, `age`, `cardiac`, and `cost`.
Based on our analysis of the cohort data in the "Assignment 2" R markdown file in the 'analysis' folder, we run a linear regression of cost on age, smoke, female, and cardiac. We find statistical significannce for all coefficients of the covariates. The main results are below: 

Controlling for other covariates, age has a significant incremental effect on cost at ~$16 per year. Fixing all other variables (non-smokers, no cardiac event, average age), females have lower costs than males by $253 per visit. Adjusting for age, smoking status, and gender (baseline is non-smoking men), those having a cardiac event costs $408 on average more than those note having a cardiac event (as the graph in our analysis / pdf shows). Finally, smoking has the largest individual effect on cost of visit ($542 on average more than non-smokers), controlling for all other variables.

Further checks would be required to ensure homoskedasticity, no multicollinearity, linearity in parameters, and no correlation between residuals (errors) and parameters. This would ensure that our OLS / linear model is the best linear unbiased estimator(s) of our beta coefficients on our covariates.

I did not use generative AI technology (e.g., ChatGPT) to complete any portion of the analysis for this assignment.

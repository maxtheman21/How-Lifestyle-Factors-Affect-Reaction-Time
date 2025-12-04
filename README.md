# Reaction Time Prediction Using Machine Learning  
## Final Project Overview

### Project Summary
This project investigates whether reaction time can be accurately predicted using cognitive performance data. The dataset contained more than 80,000 samples, providing a robust foundation for model training and evaluation. Both linear and non-linear machine learning models were tested to determine if the dataset’s features were correlated strongly enough with reaction time to enable prediction.

### Objective
- Use machine learning to predict reaction time from cognitive performance features  
- Evaluate and compare linear vs. non-linear model performance  
- Assess whether the dataset contains meaningful predictive signals  

### Dataset
- Approximately 80,000 rows of cognitive performance measurements  
- Additional features were engineered during preprocessing  
- Correlation analysis revealed weak relationships between predictors and reaction time  

### Models Tested
| Model Type | Example Models | Best RMSE | Notes |
|------------|----------------|-----------|------|
| Linear     | Linear Regression, Polynomial Regression | ~115 | High intercepts, near-zero coefficients, poor predictive power |
| Non-Linear | Decision Tree Regression | 47–111 | Some improvement, but inconsistent generalization |

**Conclusion:** Model performance remained weak overall. The dataset’s features do not reliably predict reaction time.

### Key Findings
- A large dataset does not guarantee predictive success  
- Low-correlation features lead to poor model learning and high error  
- Non-linear methods improved results slightly but still lacked stability  
- Identifying unproductive feature-target relationships is an important outcome in applied machine learning

### Future Work
To improve prediction accuracy, future studies should incorporate features more directly associated with reaction time, such as:
- Sleep duration and quality  
- Physical performance metrics  
- Cognitive load indicators  
- Additional physiological measurements  

### Skills and Concepts Demonstrated
- Data cleaning and feature engineering  
- Correlation analysis and model diagnostic techniques  
- Use of RMSE and coefficient interpretation for performance evaluation  
- Understanding model limitations and appropriate rejection of weak predictors  

# Predictive Analysis of Depression in Students  
**Machine Learning Project with Feature Selection Techniques**

## Overview
This project identifies key predictors of depression among students using a dataset of 27,901 records. Through rigorous feature selection methods, we uncovered the most influential factors affecting student mental health, with findings validated by multiple statistical approaches.

## Key Findings
Analysis revealed these primary predictors of depression:
1. **Academic Pressure** (χ² = 3821.83, p < 0.001)
2. **Financial Stress** (Mutual Information: 0.124)
3. **Suicidal Thoughts** (Decision Tree Importance: 0.298)
4. **Work/Study Hours** (RFE-selected feature)
5. **Sleep Duration** (Chi-square: p < 0.001)

## Technical Implementation
### Feature Selection Methodology

The project employed multiple techniques to identify the most influential predictors of student depression:
-Mutual Information: Identified Suicidal Thoughts and Academic Pressure as top features, with mutual information (MI) scores exceeding 0.15.
-Recursive Feature Elimination (RFE): Selected Academic Pressure and Financial Stress among the top 5 predictive features using logistic regression.
-Decision Tree: Highlighted Suicidal Thoughts and Academic Pressure with feature importance scores greater than 0.13.
-Chi-Square Test: Also ranked Academic Pressure and Financial Stress highest, with χ² scores exceeding 3557.

### Analytical Approach
- Multi-method feature selection consensus
- Statistical validation of predictors
- Correlation analysis between features
- Importance ranking visualization

## Project Documentation
[**Comprehensive Project Report (PDF)**](_RashiRaj_AMLProject.pdf)  
*Includes complete documentation of:*
- Dataset preprocessing pipeline
- Feature selection implementation
- Statistical validation metrics
- Visualization of key results
- Technical conclusions and recommendations

## Conclusions
1. Academic pressure shows strongest correlation with depression rates
2. Psychological indicators serve as critical early warning signs
3. Lifestyle factors (sleep duration) significantly impact mental health
4. Multi-factorial intervention strategies are recommended
5. Machine learning effectively identifies at-risk student profiles

## Author  
**Rashi Raj**  
B.Tech Computer Science (AIML)  
University of Petroleum and Energy Studies  
[GitHub Profile](https://github.com/rasshhe)

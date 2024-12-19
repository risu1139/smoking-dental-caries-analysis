# The Impact of Smoking on the Development of Dental Caries
Overview
This project provides a comprehensive statistical analysis exploring the relationship between smoking and the development of dental caries. By leveraging a robust dataset of 38,984 individuals and conducting a meta-analysis of 12 independent studies, this research quantifies the association between smoking and oral health degradation. It aims to provide critical insights for public health interventions.

Objectives
Quantify the association between smoking and dental caries.
Assess the consistency of this relationship across diverse populations.
Provide statistically rigorous evidence for potential causal mechanisms.
Data
The dataset includes health metrics from the Playground Series - Season 3, Episode 24, such as:

Body Mass Index (BMI): Underweight to obese classification.
Waist Circumference: Stratified obesity risk by gender.
Age: Low (<45 years) and high (≥45 years) risk groups.
Blood Pressure: Normal (<120/80 mmHg) to severe hypertension (≥180/120 mmHg).
Oral Health Metrics: Dental caries classification.
Additional biomarkers: Cholesterol, triglycerides, hemoglobin, creatinine, γ-GTP, and AST-ALT values.
Methodology
The analysis was conducted in the following phases:

Descriptive Statistics: Summarized key health indicators and frequency distributions.
Chi-Square & Fisher’s Exact Tests: Assessed the relationship between smoking and dental caries.
Kaplan-Meier Survival Analysis: Explored the onset of dental caries in smokers vs. non-smokers.
Meta-Analysis: Pooled data from 12 independent studies to generalize findings.
Regression Analysis: Validated the findings using logistic regression.
XGBoost Classifier: Developed a model for predicting smoking status using health metrics.
Results
Chi-Square Test: Established a strong association between smoking and dental caries (p-value < 0.05).
Odds Ratio (OR): Smokers are 2.34 times more likely to develop dental caries.
Kaplan-Meier Survival Analysis: Smokers develop dental caries earlier in life than non-smokers.
Meta-Analysis: High heterogeneity but consistent evidence of smoking's impact.
XGBoost Classifier: Achieved an MSE of 0.2067 with hyperparameter tuning.
Conclusion
This analysis demonstrates a significant and consistent association between smoking and an increased likelihood of developing dental caries. The findings underscore the importance of public health campaigns targeting smoking cessation to mitigate risks to oral health.

How to Use
Clone this repository.
You can access the dataset and scripts used for the statistical analysis.
Run individual scripts for specific tests or model training.

References
The project includes a comprehensive list of studies and literature used for meta-analysis.

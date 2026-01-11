# Student Performance Analytics & Prediction

## Overview
This project analyzes student academic and behavioral data to identify key factors affecting performance and to predict final grades. In addition to regression-based grade prediction, the project includes a classification model to identify academically at-risk students.

## Dataset
- Source: UCI Student Performance Dataset (Math)
- Records: 395 students
- Target Variables:
  - Regression: Final Grade (G3)
  - Classification: At-Risk Status (G3 < 10)

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Methodology
1. Data loading and preprocessing
2. Exploratory data analysis and correlation study
3. Feature engineering (average previous grades)
4. Regression modeling (Linear Regression, Random Forest)
5. Model evaluation using RMSE, MAE, R², and cross-validation
6. Classification of at-risk students using balanced Logistic Regression
7. Performance evaluation using Accuracy, Precision, Recall, and F1-score

## Key Results
- Random Forest Regression achieved an RMSE of ~1.9 and R² > 0.8
- Balanced Logistic Regression achieved:
  - Accuracy ~90%
  - Recall ~96%
  - F1-score ~87%

## Insights
- Previous academic performance is the strongest predictor of final grades
- High absenteeism negatively impacts performance
- Balanced classification improves detection of at-risk students

## Conclusion
The project demonstrates an end-to-end data science workflow with a strong emphasis on interpretability, model evaluation, and real-world applicability in the education domain.

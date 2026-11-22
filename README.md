Heart Disease Prediction Using Data Science

Project Overview

This project focuses on analysing cardiovascular patient data and developing machine learning classification models to predict the presence of heart disease.

The project follows an end-to-end Data Science workflow, including data understanding, exploratory data analysis, data preprocessing, feature selection, model development, evaluation and interpretation.

Objectives

- Analyse patient medical data.
- Identify important patterns and relationships among medical features.
- Perform exploratory data analysis and statistical analysis.
- Develop and compare multiple machine learning classification models.
- Evaluate model performance using classification metrics.
- Provide data-driven recommendations for hospitals.

Dataset Description

The project uses two CSV datasets:

- Dataset 1: Patient identifiers and heart disease target variable.
- Dataset 2: Patient identifiers and medical features.

The datasets are combined using the common patient identifier.

Total records: 180

Target variable: `heart\_disease\_present`

- 0 – No heart disease
- 1 – Heart disease present

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib
- Jupyter Notebook

 Project Workflow

1. Data Collection and Understanding
2. Data Cleaning
3. Exploratory Data Analysis
4. Data Visualization
5. Data Preprocessing
6. Feature Selection
7. Statistical Analysis
8. Machine Learning Model Development
9. Model Comparison
10. Hyperparameter Tuning
11. Model Evaluation
12. Threshold Analysis
13. Feature Interpretation
14. Hospital Recommendations
15. Conclusion

Machine Learning Algorithms

The following algorithms were evaluated:

- Support Vector Machine (SVM)
- Random Forest
- XGBoost
- Logistic Regression
- Decision Tree

 Model Evaluation Results

The original SVM achieved the following test results:

| Metric | Score |
|---|---:|
| Accuracy | 91.7% |
| Precision | 84.2% |
| Recall | 100% |
| F1 Score | 91.4% |
| ROC-AUC | 0.966 |

The tuned SVM achieved an accuracy of 83.3% and ROC-AUC of 0.947 on the test dataset.

The original SVM showed better overall test performance in this experiment.

 Key Findings

- Patient groups showed differences in several medical feature distributions.
- Maximum heart rate showed a notable difference between the two groups.
- Serum cholesterol also showed a positive mean difference in the disease group.
- The original SVM achieved the strongest observed test performance among the reported comparison.

 Hospital Recommendations

- Encourage regular cardiovascular screening.
- Monitor blood pressure and cholesterol levels.
- Promote preventive healthcare awareness.
- Use validated clinical assessments for patient monitoring.
- Consider machine learning only as supplementary research support.

 Project Limitations

- The dataset contains only 180 patient records.
- External clinical validation has not been performed.
- Model performance may vary across patient populations.
- Larger and more representative datasets are required.

 Disclaimer

This project is developed for educational and research purposes only. It is not intended to replace professional medical diagnosis or treatment.

Author

Data Science Project – Heart Disease Prediction

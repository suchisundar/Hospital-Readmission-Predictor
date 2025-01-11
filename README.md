# Predicting Impact on Readmission Rates for Patients Hospitalized with Diabetes

### Problem Statement 

Hospital readmissions are classified as events when a discharged patient gets readmitted to a hospital within a certain number of days. These have been the subject of retrospective surveys and prospective trials with a view to their prevention. The need for hospital readmission for certain conditions indicates hospital quality. Identifying patients at high risk early in hospitalization will help to reduce the readmission rate, in that hospitals can focus on preparing readmission for patients at high risk to shorten the length of readmission. 

### Goal of Analysis

The goal of the analysis is to find the determining factors that lead to higher readmission and correspondingly being able to predict which patients will get readmitted. Therefore, we proposed two research questions: 

1) What methods can we use to best predict hospital readmission in this dataset? 

2) What are the strongest predictors of hospital readmission in diabetic patients? 

### Method & Result 

This project uses Logistic Regression, Decision Tree, Random Forest, and XGboost classifiers to predict the readmission rate. Each algorithm was evaluated using 10-fold stratified cross-validation. All of our algorithms are evaluated using the area-under-the-curve (AUC), which is equivalent to the c-statistic in the binary classification scenario. In comparing of four models, it showed the XGBoost worked the best for predicting the admission rate, which achieves the highest accuracy as 0.94, with 0.61 on AUC, and the second-best model is Random Forest, which achieves 0.92 accuracy and 0.94 on AUC. In this study, we also identified the most important factors as the time_in_hospital and number of inpatient stays, number of diagnoses, which appears to associate with the severity of the disease. 


 
### Credits

- Bhuvan, M.S., Kumar, A., Zafar, A. and Kishore, V., 2016. Identifying diabetic patients with high risk of readmission. *arXiv preprint arXiv:1602.04257*.
-  Mingle, D., Predicting Diabetic Readmission Rates: Moving Beyond HbA1c.
-  https://medium.com/berkeleyischool/how-to-use-machine-learning-to-predict-hospital-readmissions-part-1-bd137cbdba07

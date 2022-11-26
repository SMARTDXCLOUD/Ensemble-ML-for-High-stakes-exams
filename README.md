# Ensemble ML Models for Early Prediction of Students' Performance in High-Stakes Examinations 
# Keywords: Artificial Intelligence, High-Stakes Examination, Machine Learning, Medical Education, Educational Data Mining.
# This study presents a framework, based on reliable ML models to predict  students' performance in high-stake exams.
# 1) Prepration: To prepare input data for models’ development, four main preprocessing steps must be applied. First, input features and outcomes (score and status in CMBSE) were statistically analyzed (Chi-square test, t-test, and heatmap plots) and their correlations were discussed. In the second step, data scaling and normalization methods were implemented on features to manage the wide range of their values (a standard scaler (MaxMin) and one-hot encoding). Third, the impacts of features on predictions were estimated and the most important ones were selected (SHapely Additive exPlanations (SHAP)). Finally, to deal with the imbalanced datasets, data sampling approaches (SMOTE Tomek) were conducted. 
# 2) Modeling: Two main categories of ML approaches are compared, first, traditional models e.g., Logistic Regression  (LR), Support Vector Machine (SVM), and K-Nearest Neighbors (KNN), and second, ensemble models, such as Voting, Bagging, Random Forests (RF), Adaptive Boosting (ADA), Extreme Gradient Boosting (XGB), and Stacking. A hyper-parameter tuning technique, called GridSearchCV, was performed and models were optimized based on the best parameters.
# 3) Evaluations and visualization: on one hand, for classifiers, the performance of models were evaluated using the following measures, such as Precision (PPV), Sensitivity (Recall), Specificity (Spe), Accuracy (ACC), F-measure (F1),  Matthew’s Correlation Coefficient (MCC), Area Under Curve of Receiver Operator Characteristic (AUC-ROC), Area Under Curve of Precision-Recall (AUC-PRC), Calibration Plot, Brier Score (BS). On the other hand, for the evaluation of regressors, several metrics were utilized, such as Mean Squared Error (MSE), Root Mean Square Deviation (RMSD), and coefficient of determination (R2).

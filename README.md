Wine Quality Prediction using Machine Learning :- Project Overview :-

This project aims to predict the quality of wine based on its physicochemical properties using Machine Learning techniques. The model analyzes features such as acidity, sugar content, pH level, and alcohol percentage to classify wine quality.

The goal is to build a predictive model that can assist in automated quality assessment using data-driven approaches.

Dataset: Wine Quality Dataset :- Features include: Fixed Acidity Volatile Acidity Citric Acid Residual Sugar Chlorides Free Sulfur Dioxide Total Sulfur Dioxide Density pH Sulphates Alcohol Target Variable: Wine Quality (Score)

Technologies Used :- Python NumPy Pandas Matplotlib / Seaborn Scikit-learn

Project Workflow :- Data Loading and Exploration Data Cleaning and Preprocessing Exploratory Data Analysis (EDA) Feature Scaling and Correlation Analysis Model Building (Regression / Classification) Model Evaluation using Accuracy / RMSE / Confusion Matrix Hyperparameter Tuning

Machine Learning Models Used :- Logistic Regression Random Forest Support Vector Machine Decision Tree

Model Evaluation :- Three classification models — KNN, SVM, and Random Forest — were evaluated using Accuracy Score, Confusion Matrix, Precision, Recall, and F1-Score.

K-Nearest Neighbors (KNN) Best Accuracy: ~68% Performance sensitive to choice of k and distance metric. Lower overall performance compared to other models.

Support Vector Machine (SVM) Best Accuracy: 75.75% Tuned using RBF kernel with optimized C and gamma. Demonstrated good generalization but slightly higher misclassification rate.

Random Forest (Final Model) Accuracy: 80% Precision: 0.80 Recall: 0.83 F1-Score: 0.81 Random Forest achieved the highest and most balanced performance across all evaluation metrics and was selected as the final model.

Conclusion :- This project demonstrates the complete machine learning workflow — from data preprocessing and exploratory analysis to model comparison and performance optimization. Among the evaluated models (KNN, SVM, and Random Forest), Random Forest achieved the best performance with 80% accuracy and strong F1-score, indicating balanced classification across both classes. The results highlight the importance of: Feature scaling for distance-based models Hyperparameter tuning using cross-validation Comparative model evaluation before final selection This project reinforces practical understanding of classification techniques and model optimization strategies essential for real-world Data Science applications.

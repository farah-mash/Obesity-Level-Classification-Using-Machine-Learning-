# Obesity-Level-Classification-Using-Machine-Learning-
This project focuses on predicting obesity levels based on personal, behavioral, and lifestyle attributes using various machine learning algorithms. The dataset includes features such as gender, age, height, weight, eating habits, physical activity, and family history.
## 📊 Dataset Information
This dataset is used for estimating obesity levels in individuals based on their eating habits and physical condition. It includes data from people living in Mexico, Peru, and Colombia.

Number of Instances: 2,111

Number of Features: 16 input features + 1 target variable (NObeyesdad)

Target Classes:
Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, Obesity Type III.

### Note:
77% of the dataset was synthetically generated using the SMOTE algorithm via the Weka tool.
The remaining 23% was collected from real users via a web-based survey.

## 🤖 Machine Learning Model
To evaluate and compare the performance of different classification algorithms, multiple machine learning models were implemented. The models were trained on the dataset after applying preprocessing techniques, including label encoding and normalization.

✅ Models Used:
Random Forest Classifier
Decision Tree Classifier
Linear Support Vector Classifier (SVM)
Gaussian Naive Bayes 

📈 Model Performance Summary
Below is a summary of each model’s performance on the test set:

Model	Accuracy	Precision	Recall	F1-Score
Random Forest	0.959	0.961	0.959	0.959
Decision Tree	0.935	0.935	0.935	0.935
Linear SVM	0.751	0.740	0.751	0.740
Gaussian Naive Bayes	0.609	0.620	0.609	0.557

###🔍 Note:
The Random Forest Classifier achieved the best results in terms of accuracy and f1-score, making it the most effective model for this multi-class classification task.
The Decision Tree also showed strong performance and interpretability.
SVM and Naive Bayes performed relatively worse, possibly due to class imbalance and feature interactions.

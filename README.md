# Diabetes_Prediction
This project aims to build a Machine Learning model to predict whether a person is diabetic or not based on health-related attributes. This project uses a large dataset with 100,000 records from Kaggle for better accuracy and generalization.

📊 Dataset

Size: 100,000 rows
Source: Kaggle (Diabetes Prediction Dataset with 100k samples)
Features used:
Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age
Outcome (Target: 0 = Non-diabetic, 1 = Diabetic)

⚙️ Workflow
1. Data Preprocessing
Handled missing values
Removed duplicates
Handled outliers
Scaled numerical features using StandardScaler / MinMaxScaler
Split dataset into Train (80%) and Test (20%)

2. Exploratory Data Analysis (EDA)
Distribution plots of features (Age, Glucose, BMI, etc.)
Correlation heatmap using Seaborn
Boxplots for outlier detection
Class balance check (diabetic vs. non-diabetic)

3. Model Building
Tested multiple ML models:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)

4. Model Evaluation
Metrics Used:
Accuracy
Precision
Recall
F1-score
Confusion Matrix
ROC-AUC Curve

Best Performing Model:
Achieved highest accuracy with Random Forest Classifier which is 94%.

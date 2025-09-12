# Heart Disease Prediction with Random Forest and SHAP
This project uses a Random Forest classifier to predict the presence of heart disease based on a set of clinical features and uses interpretation using SHAP (SHapley Additive exPlanations). The dataset used is from the UCI Heart Disease Dataset.
 
The dataset contains 14 attributes that we later expand to 19 using one-hot encoding. They include age, sex, co, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal, and the target variable.

### Results
The mode has an F1-score of 0.83 for "No Disease" (class 0) and 0.84 for "Disease" (class 1). It has an overall accuracy of 84%. Using SHAP we found that `thal`, `ca`, and `oldpeak` were the top three contributors to predicting heart disease.
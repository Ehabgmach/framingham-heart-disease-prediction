# framingham-heart-disease-prediction
10-year CHD risk prediction using ML — Framingham Heart Study
 🫀 Framingham Heart Disease Prediction

10-year coronary heart disease (CHD) risk prediction using the 
Framingham Heart Study dataset and advanced ML techniques.

## 📊 Dataset
- **Source:** Framingham Heart Study
- **Patients:** 4,238
- **Features:** 15 clinical variables
- **Target:** 10-year CHD risk (binary)

## 🤖 Models Used
- Logistic Regression (baseline)
- K-Nearest Neighbors
- Random Forest
- Support Vector Machine
- Gradient Boosting
- XGBoost (tuned with GridSearchCV)
- ⭐ Stacking Ensemble (best result)

## 📈 Results
| Model | Accuracy | AUC |
|-------|----------|-----|
| Logistic Regression | ~74% | ~0.77 |
| XGBoost (Tuned) | ~88% | ~0.91 |
| Stacking Ensemble | ~90% | ~0.93 |

## ⚙️ Techniques
- SMOTE for class imbalance
- StandardScaler preprocessing
- GridSearchCV hyperparameter tuning
- SHAP explainability

## 🚀 Run on Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK_HERE)

## 🛠️ Libraries
pandas · numpy · matplotlib · seaborn · scipy · scikit-learn · xgboost · imbalanced-learn · shap

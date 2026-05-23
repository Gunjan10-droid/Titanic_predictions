# 🚢 Titanic Survival Prediction

## 📌 Overview
Predicting whether a passenger survived the Titanic disaster using Machine Learning.

## 📊 Dataset
- **Source:** Kaggle — Titanic: Machine Learning from Disaster
- **Train size:** 891 rows, 12 columns
- **Test size:** 418 rows
- **Target:** Survived (0 = No, 1 = Yes)

## 🔧 Steps Performed
1. Exploratory Data Analysis (EDA)
2. Data Preprocessing — Missing values, Drop irrelevant columns
3. Feature Engineering — family_size, is_alone, fare_per_person
4. Label Encoding & One-Hot Encoding
5. Model Training — Random Forest Classifier
6. Hyperparameter Tuning — GridSearchCV

## 🤖 Model Used
- Random Forest Classifier
- Best Params: max_depth=10, min_samples_split=2, n_estimators=300

## 📈 Results
| Metric | Score |
|--------|-------|
| Local Accuracy | 82.4% |
| Kaggle Public Score | 0.751 |

## 📦 Libraries Used
```python
pandas, numpy, matplotlib, seaborn
sklearn, xgboost
```

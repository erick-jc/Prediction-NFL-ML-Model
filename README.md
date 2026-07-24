# NFL Draft Prediction Pipeline

Repository containing the baseline solution and predictive model for the NFL Draft prediction competition, developed as part of the **Global Consumer Intelligence (GCI)** course.

## 📋 About the Project
The main objective of this project is to predict whether a player will be selected in the NFL Draft (**Drafted**) based on their physical attributes, athletic testing performance metrics (such as the Combine or Pro Days), and demographic/historical information.

## 🛠️ Technologies & Approach
* **Language:** Python
* **Environment:** Google Colab / VS Code
* **Machine Learning Libraries:** CatBoost, LightGBM, XGBoost, Scikit-Learn
* **Hyperparameter Optimization:** Optuna (using robust cross-validation strategies like `StratifiedGroupKFold`)
* **Evaluation Metric:** ROC-AUC

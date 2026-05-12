# TEAM 22 Explainable AI (XAI) Project

This repository contains the implementation of various Machine Learning models evaluated on our dataset, with a strong focus on Explainable AI (XAI) techniques (SHAP, LIME, PDP, ALE, Feature Importance) to demystify "black-box" models.

## Team Members & Implemented Models
- **Ahmed:** Random Forest, Decision Tree, CatBoost
- **Raneem:** Logistic Regression, Naive Bayes, XGBoost
- **Youssef Tarek:** AdaBoost
- **Riham:** (To be added)

## Project Structure
- `TEAM22_EDA_Upgraded (1).ipynb`: Contains the central data preprocessing, exploratory data analysis (EDA), and feature engineering techniques.
- `[Name]_[ModelName].ipynb`: Individual notebooks for each team member containing the specific model building, training, evaluation, and the implementation of at least 4 XAI techniques.
- `TEAM22_Master_Dataset.csv`: The primary dataset used across all models.

## Instructions to Run the Code

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ahmed-Abdelslam-75/TEAM22_XAI_Project.git
   ```

2. **Install Required Libraries:**
   Ensure you have the following installed in your Python environment:
   ```bash
   pip install pandas numpy scikit-learn catboost xgboost shap lime matplotlib seaborn alibi
   ```

3. **Execution Order:**
   - **Step 1:** Run `TEAM22_EDA_Upgraded (1).ipynb` first to understand the data processing steps and view the exploratory analysis.
   - **Step 2:** Run the individual model notebooks in any order (e.g., `Ahmed_CatBoost_with_Upgraded_EDA.ipynb`). Each model notebook is self-contained: it loads the dataset, trains the respective model, and outputs the detailed XAI visualizations.
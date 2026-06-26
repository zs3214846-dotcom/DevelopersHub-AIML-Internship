# DevelopersHub Corporation — AI/ML Engineering Internship

**Intern Name:** Zainab Sarwar 
**Due Date:** 27th June, 2026  

## Tasks Completed

### Task 1: Dataset Visualization
* **Objective:** Explore and visualize the Iris dataset to identify structural trends, feature distributions, and class separability.
* **Dataset:** Iris Dataset (Loaded dynamically via `seaborn`).
* **Tools & Libraries:** `pandas`, `numpy`, `seaborn`, `matplotlib`.
* **Key Findings:** * Successfully conducted initial data profiling and inspection using `.info()` and `.describe()`.
  * Scatter plots reveal that the **Setosa** species exhibits significantly smaller petals and is clearly, linearly separable from *Versicolor* and *Virginica*.
  * Histograms and box plots confirmed a clean feature distribution with no major distorting outliers.

### Task 2: Short-Term Stock Price Prediction
* **Objective:** Build and evaluate machine learning regression models to predict short-term stock price fluctuations.
* **Dataset:** Apple (`AAPL`) Stock Price Data (2 years of historical data fetched dynamically using the `yfinance` API).
* **Tools & Libraries:** `yfinance`, `pandas`, `scikit-learn` (`LinearRegression`, `RandomForestRegressor`, `train_test_split`), `matplotlib`.
* **Key Findings:**
  * **Linear Regression** performed exceptionally well, achieving a highly precise Mean Absolute Error (MAE) of **\$2.39** and an $R^2$ score of **0.9643** by effectively leveraging lag features to track continuous price trends.
  * **Random Forest Regressor** underperformed on this continuous forecasting task, yielding an MAE of **\$10.34** and an $R^2$ score of **0.4401** due to tree-based structural stagnation limits over time.

### Task 3: Heart Disease Prediction
* **Objective:** Develop a robust binary classification framework to assess and predict patient heart disease risks based on medical diagnostic features.
* **Dataset:** Heart Disease Dataset (Kaggle - 1,025 samples across 14 medical attributes).
* **Tools & Libraries:** `pandas`, `seaborn`, `scikit-learn` (`LogisticRegression`, `DecisionTreeClassifier`, `StandardScaler`), `matplotlib`.
* **Key Findings & Performance:**
  * **Data Quality:** Verified a pristine dataset with **zero missing values** across an ideally balanced target distribution (526 positive vs. 499 negative cases).
  * **Top Predictors:** The correlation heatmap indicates that **chest pain type (`cp`)** and **maximum heart rate achieved (`thalach`)** hold the strongest positive correlations with heart disease risk.
  * **Model Evaluation:** A **Logistic Regression** model trained on an 80/20 split achieved an overall classification accuracy of **79.51%**.
  * **Validation Metrics:** Confirmed excellent discriminative capabilities with an **ROC-AUC score of 0.879** and a confusion matrix that successfully isolated **90 True Positives**.# DevelopersHub-AIML-Internship

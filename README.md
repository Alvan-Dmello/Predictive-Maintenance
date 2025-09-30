# Predictive-Maintenance for Metro Compressors

## 💡 Project Overview

This project focuses on leveraging **Random Forest** machine learning model to predict failures in the **air production units (APU)** of metro compressors. The primary goal is to shift maintenance from reactive to predictive, thereby minimizing unplanned downtime, optimizing operational efficiency, and extending the lifespan of critical equipment.

The entire analysis, from data cleaning and feature engineering to model training and evaluation, is documented step-by-step in the accompanying Jupyter Notebook.

---

## ⚙️ Methodology and Model

The Predictive Maintenance process follows a standard ML workflow:

1.  **Data Preprocessing:** Handling sensor data, cleaning outliers, and managing missing values.
2.  **Feature Engineering:** Creating time-series features (e.g., rolling averages, exponential decay) to capture operational trends and identify anomaly indicators preceding failure.
3.  **Model:** **Random Forest Classifier** was selected for its robustness, interpretability, and effectiveness with tabular data, achieving high accuracy in classifying upcoming failures.
4.  **Hyperparameter Tuning:** Grid search was performed to optimize model parameters, maximizing precision and recall—critical metrics for minimizing false negatives (missed failures).

---

## 🧰 Tools & Resources

| Category | Tool / Resource | Purpose |
| :--- | :--- | :--- |
| **Development** | Python, **Jupyter Notebook** | Environment for iterative code development and analysis documentation. |
| **Key Libraries** | **Scikit-learn** | Model building, cross-validation, and evaluation metrics. |
| **Data Handling** | Pandas, NumPy | Efficient data manipulation and numerical operations. |
| **Dataset** | Kaggle Dataset Link | Link to the public compressor failure dataset used in this project. |
| **Documentation** | Project Report | Detailed summary of methodology, feature importance, and final results. |

---

## 🚀 How to Use & View the Project

The core of this project is the **Predictive_Maintenance.ipynb** notebook.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/Predictive-Maintenance.git](https://github.com/YourUsername/Predictive-Maintenance.git)
    cd Predictive-Maintenance
    ```
2.  **Launch the Notebook:** Open the file locally using Jupyter Lab or VS Code, or simply view the rendered file directly on GitHub.
    * **Notebook:** [`Predictive_Maintenance.ipynb`](./Predictive_Maintenance.ipynb)

3.  **Review the Report:** For a non-code summary of the project's setup, feature engineering choices, and a full analysis of performance metrics (Accuracy, Precision, Recall, F1-Score), refer to the **Project Report**.

---

## 📈 Published Results

The results, detailed in the **Project Report**, confirm that the tuned Random Forest model successfully predicts equipment failures with high confidence. The analysis includes a visualization of **Feature Importance** to identify which sensor readings (e.g., pressure trends, vibration peaks) are the strongest predictors of imminent APU failure, providing actionable insights for maintenance teams.

# AI-Based Customer Spending Prediction

A beginner-friendly machine learning project designed to predict customer spending categories (**Low**, **Medium**, or **High**) using demographic and financial attributes. This project follows a complete end-to-end data science workflow inside VS Code, covering data cleaning, exploratory data analysis (EDA), feature engineering, model training, evaluation, feature importance analysis, and business reporting.

---

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Key Features & Deliverables](#-key-features--deliverables)
- [Tech Stack & Tools](#-tech-stack--tools)
- [Project Structure](#-project-structure)
- [Installation & Setup](#-installation--setup)
- [Workflow Implementation](#-workflow-implementation)
- [Complete Python Code](#-complete-python-code)
- [Model Evaluation & Results](#-model-evaluation--results)
- [Business Insight Report](#-business-insight-report)

---

## 🎯 Project Overview
Understanding customer spending behavior is crucial for targeted marketing, inventory planning, and revenue optimization. This project uses machine learning techniques to categorize customers into distinct spending segments based on key characteristics such as **Age** and **Annual Income**.

---

## 📦 Key Features & Deliverables
1. **Cleaned & Prepared Dataset**: Processed customer dataset with categorized spending tiers.
2. **Exploratory Data Analysis (EDA)**: 5 distinct visualizations analyzing key distributions and relationship patterns.
3. **Feature Engineering**: Standardized inputs and features separated from targets to prevent data leakage.
4. **Machine Learning Models**: Benchmarking **Logistic Regression** vs. **Random Forest Classifier**.
5. **Model Evaluation**: Metrics including Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
6. **Feature Importance & Interpretation**: Analyzing top drivers of spending predictions.
7. **Inference Function**: Interactive utility to predict spending tiers for new/unseen customer data.
8. **Business Insight Report**: Summary of findings and strategic marketing recommendations.

---

## 🛠️ Tech Stack & Tools
- **Language**: Python 3.8+
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-Learn
- **IDE / Environment**: Visual Studio Code (Jupyter Extension / Terminal)

---

## 📁 Project Structure

```text
customer-spending-prediction/
│
├── README.md                          # Project documentation
├── requirements.txt                    # Python dependencies
├── main.py                            # Full Python script
└── notebooks/
    └── customer_spending_prediction.ipynb # Interactive Jupyter Notebook
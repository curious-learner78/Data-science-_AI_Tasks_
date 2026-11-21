# Data Analytics & Machine Learning Portfolio

An end-to-end collection of five data analytics, visualization, business trend analysis, machine learning classification, and interactive ML web application projects developed and executed in **Google Colab** using **Python**.

## Repository Structure

```text
├── README.md
├── project-01-titanic-eda/
│   └── titanic_eda.ipynb
├── project-02-data-visualization/
│   └── data_visualization.ipynb
├── project-03-sales-churn-analysis/
│   └── sales_churn_analysis.ipynb
├── project-04-ml-classifier/
│   └── ml_classifier.ipynb
└── project-05-gradio-ml-app/
    └── Task5.ipynb
```

## Tech Stack
1. Data Manipulation & Analysis: Pandas, NumPy
2. Data Visualization: Matplotlib, Seaborn
3. Machine Learning: Scikit-Learn (DecisionTreeClassifier, train_test_split, evaluation metrics)
4. Interactive Web App: Gradio

---

## Projects Overview

1. **Exploratory Data Analysis (EDA)** on Titanic (project-01-titanic-eda/)
Loaded the Titanic dataset and inspected data types, missing values, and descriptive statistics.
Performed non-destructive missing-value imputation (Age via median, Embarked via mode) and engineered family-size features.
Analyzed survival rates across passenger class (Pclass), sex, and age distributions to uncover key demographic and socio-economic patterns.
  
2. **Data Visualization with Matplotlib & Seaborn (project-02-data-visualization/)**
Created distributions using histograms with KDE overlays for Age and Fare.
Examined spread, medians, and outliers using box plots across passenger classes and survival outcomes.
Built a numeric feature correlation matrix heatmap and a survival-rate pivot heatmap across passenger class and sex.
3. **Customer Churn / Sales Trend Analysis (project-03-sales-churn-analysis/)**
Analyzed order-level e-commerce sales data to track total revenue, order counts, unique customers, and average order value (AOV).
Evaluated monthly revenue trends and month-over-month growth alongside customer segment revenue contributions.
Computed customer recency and order frequency to flag high-risk churn customers versus active customers, paired with trend and segment charts.
4. **First Machine Learning Classifier (project-04-ml-classifier/)**
Preprocessed Titanic passenger features, handled missing values, encoded categorical attributes, and created a stratified train-test split.
Trained and evaluated a DecisionTreeClassifier using train/test accuracy and a full classification report.
Visualized model performance and interpretability through a confusion matrix, feature importance bar chart, and decision tree structure diagram.
5. **Interactive ML Web App (project-05-gradio-ml-app/)**
Integrated a trained Scikit-Learn DecisionTreeClassifier into an interactive Gradio web interface.
Added input sliders and dropdowns for passenger features (Pclass, Sex, Age, SibSp, Parch, Fare, Embarked) with real-time survival prediction and probability output.
---

## How to Run
1. Open any .ipynb notebook in Google Colab.
2. Run the cells sequentially from top to bottom (required libraries and datasets are loaded within the notebooks).

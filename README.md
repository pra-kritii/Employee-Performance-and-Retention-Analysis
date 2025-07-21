# Employee Performance and Retention Analysis

This project aims to analyze employee data and build predictive models to forecast both employee performance and attrition (likelihood of leaving the organization). It applies concepts from statistics, machine learning, and deep learning to derive insights that can help in workforce management and retention planning.

## 📌 Project Objectives

- Perform Exploratory Data Analysis (EDA) on employee data.
- Identify trends, correlations, and anomalies affecting performance and attrition.
- Apply statistical techniques such as probability, Bayes' Theorem, and hypothesis testing.
- Build Machine Learning models for:
  - Predicting employee attrition (Classification)
  - Predicting employee performance (Regression)
- Implement Deep Learning models using TensorFlow/Keras for enhanced prediction accuracy.
- Derive actionable insights and HR recommendations.
- Visualize data and results effectively for reporting.

## 📂 Dataset Description

The dataset used (`employee_data.csv`) includes the following columns:

- `Employee ID`
- `Name`
- `Age`
- `Department`
- `Salary`
- `Years at Company`
- `Performance Score`
- `Attrition (Yes/No)`

## 📊 Project Structure

### 📌 Phase 1: Data Collection and EDA
- Load and clean the dataset (handle missing values, duplicates, inconsistencies).
- Perform descriptive statistics.
- Visualize data using pairplots, heatmaps, and boxplots.

### 📌 Phase 2: Predictive Modeling
- Apply feature engineering and encoding techniques.
- Build:
  - **Classification Model** to predict attrition (e.g., Logistic Regression, Random Forest).
  - **Regression Model** to predict performance score (e.g., Linear Regression).
- Evaluate models using metrics like accuracy, F1-score, MSE, and R².

### 📌 Phase 3: Deep Learning Models
- Construct neural networks using Keras/TensorFlow for:
  - Employee performance prediction (regression).
  - Employee attrition prediction (classification).
- Evaluate models with appropriate metrics.

### 📌 Phase 4: Insights and Reporting
- Highlight key factors affecting performance and attrition.
- Recommend strategic actions to improve retention and productivity.
- Present findings with visualizations (line plots, bar charts, scatter plots).

## 📌 Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Data Handling: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
  - Deep Learning: `tensorflow`, `keras`
- **Tools**: Jupyter Notebook

## 📈 Results and Insights

- Developed ML models with high accuracy for attrition prediction.
- Identified strong correlation between department, salary, and attrition risk.
- Performance was strongly influenced by years at the company and age.
- Deep learning models slightly improved regression accuracy.
- Strategic insights included targeted retention plans and performance boosters.


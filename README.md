# Industry Performance Dataset – Machine Learning Project

## 📌 Project Overview

This project analyzes an Industry Performance Dataset containing information about companies, industries, employees, revenue, profit margins, customers, market ratings, countries, and regions.

The project combines **Exploratory Data Analysis (EDA)** with **Machine Learning Regression** to understand business performance and predict annual company revenue.

## 🎯 Objectives

* Perform data cleaning and preprocessing
* Analyze numerical and categorical variables
* Identify outliers
* Analyze skewness and kurtosis
* Study correlations between business variables
* Perform univariate, bivariate and multivariate analysis
* Build Machine Learning regression models
* Compare different ML algorithms
* Predict annual revenue
* Identify important factors affecting revenue

## 📊 Dataset

The dataset contains approximately **15,000 company records** and **12 original columns**.

Important variables include:

* Company Name
* Industry
* Country
* Employee Count
* Annual Revenue
* Profit Margin
* Founded Year
* Customer Count
* Market Rating
* Created Date
* Region

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

* Missing-value checking
* Duplicate checking
* Date conversion
* Feature engineering
* Categorical variable encoding
* Numerical feature scaling
* Train-test splitting

Additional features were created:

* Created Year
* Created Month
* Created Quarter
* Company Age

## 🤖 Machine Learning Models

The following regression algorithms were evaluated:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Extra Trees Regressor

## 📏 Evaluation Metrics

Models were evaluated using:

* MAE – Mean Absolute Error
* RMSE – Root Mean Squared Error
* R² Score

The model with the highest R² score was selected as the best-performing model.

## 📈 Analysis Performed

The project includes:

* Distribution analysis
* Histograms
* Boxplots
* Categorical count plots
* Outlier analysis
* Correlation heatmap
* Revenue relationship analysis
* Actual vs Predicted Revenue
* Feature importance analysis
* Model comparison

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy
* Jupyter Notebook
* VS Code
* Git & GitHub

## 📁 Project Structure

```text
Industry_Performance_ML/
│
├── data/
│   └── industry_dataset_csv.csv
│
├── models/
├── results/
│
├── industry_ml_project.ipynb
├── README.md
└── .gitignore
```

## 🚀 How to Run the Project

Clone the repository:

```bash
git clone https://github.com/YourUsername/industry-performance-ml.git
```

Move into the project directory:

```bash
cd industry-performance-ml
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy openpyxl joblib jupyter
```

Open the notebook:

```bash
jupyter notebook
```

Then open:

```text
industry_ml_project.ipynb
```

Machine Learning / Data Analysis Project

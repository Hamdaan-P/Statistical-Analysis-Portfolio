# Credit Risk Assessment in Finance

## Project Overview
This project performs a comprehensive statistical analysis of credit risk in the financial services industry. The objective is to develop predictive models that assess the likelihood of loan default based on borrower characteristics and financial metrics.

## Objective
The primary goals of this analysis are to:
- Identify key risk factors that contribute to loan defaults
- Build predictive models to classify borrowers as high-risk or low-risk
- Provide actionable insights for credit risk management and lending decisions
- Develop an interactive dashboard for risk monitoring

## Business Context
Credit risk assessment is critical for financial institutions to:
- Minimize loan defaults and financial losses
- Optimize lending strategies and interest rate pricing
- Comply with regulatory requirements (Basel III, IFRS 9)
- Maintain a healthy loan portfolio
- Make data-driven decisions about credit approvals

## Methodology
The analysis follows these key steps:

1. **Data Collection & Preparation**
   - Collected credit risk dataset from Kaggle
   - Cleaned and preprocessed data (handling missing values, outliers)
   - Feature engineering and transformation

2. **Exploratory Data Analysis (EDA)**
   - Univariate and bivariate analysis
   - Distribution analysis of key variables
   - Correlation analysis
   - Identification of patterns and trends

3. **Hypothesis Testing**
   - Chi-square tests for categorical variables
   - T-tests and ANOVA for continuous variables
   - Testing relationships between risk factors and default rates

4. **Predictive Modeling**
   - Logistic Regression
   - Random Forest Classifier
   - Gradient Boosting (XGBoost)
   - Model evaluation using ROC-AUC, precision, recall, F1-score

5. **Dashboard Development**
   - Interactive Power BI dashboard for risk monitoring
   - Key metrics and KPIs visualization

## Dataset Source
The dataset used in this analysis is publicly available on Kaggle:
- **Source**: [Credit Risk Dataset on Kaggle](https://www.kaggle.com/datasets/devavratapoilkar/credit-risk-dataset)
- The dataset contains borrower information including demographics, financial history, and loan characteristics

## Summary of Results
- Identified top 5 risk factors: Credit History, Income-to-Debt Ratio, Employment Length, Loan Amount, and Home Ownership
- Achieved 85%+ ROC-AUC score with ensemble models
- Random Forest and XGBoost models showed superior performance
- Developed risk segmentation framework for portfolio management

## Project Structure
```
Credit_Risk_Assessment_Finance/
├── data/                          # Dataset and data documentation
│   └── data_source.txt            # Dataset source and dictionary
├── notebooks/                     # Jupyter notebooks
│   └── Credit_Risk_Analysis.ipynb # Main analysis notebook
├── figures/                       # Visualizations and plots
│   ├── eda_histograms.png
│   ├── roc_curve.png
│   └── feature_importance.png
├── docs/                          # Documentation
│   └── methodology.pdf            # Detailed methodology
├── dashboard/                     # Power BI dashboard
│   └── PowerBI_RiskDashboard.pbix
└── README.md                      # This file
```

## Instructions

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost
- Power BI Desktop (for dashboard)

### Getting Started
1. Clone this repository
2. Download the dataset from the Kaggle link provided
3. Place the dataset in the `/data` folder
4. Open the Jupyter notebook in `/notebooks/Credit_Risk_Analysis.ipynb`
5. Run the cells sequentially to reproduce the analysis
6. Open the Power BI dashboard in `/dashboard` for interactive visualizations

### Installation
```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost jupyter
```

## Key Findings
- Credit history is the strongest predictor of default risk
- Borrowers with debt-to-income ratio > 40% show 3x higher default rates
- Employment stability significantly impacts creditworthiness
- Home ownership status correlates with lower default probability

## Future Work
- Incorporate macroeconomic indicators
- Develop real-time scoring API
- Implement deep learning models
- Expand analysis to include credit limit optimization

## Author
Hamdaan P

## License
This project is for educational and portfolio demonstration purposes.

---
*Last Updated: October 2025*

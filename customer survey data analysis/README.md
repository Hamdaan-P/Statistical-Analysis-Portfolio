#  Customer Survey Data Analysis (Basic)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF.svg)](https://www.kaggle.com/datasets/matinmahmoudi/sales-and-satisfaction)
[![Statistics](https://img.shields.io/badge/Analysis-Survey%20Statistics-green.svg)](https://scipy.org/)

> **Professional Survey Analysis Project**: Comprehensive examination of customer satisfaction intervention using experimental design methodology and advanced survey statistics.

##  Project Overview

This project demonstrates fundamental survey analysis and experimental design skills through examination of **real customer satisfaction data from Kaggle**. The analysis showcases proficiency in distribution testing, hypothesis testing, categorical analysis, and experimental evaluation using industry-standard statistical methods.

###  Dataset Information
- **🔗 Source**: [Kaggle - Sales and Satisfaction](https://www.kaggle.com/datasets/matinmahmoudi/sales-and-satisfaction)
- **📋 Size**: 10,000 survey responses (785 KB)
- **🔬 Design**: Randomized Control vs Treatment with Before/After measurements
- **📅 Scope**: Customer satisfaction intervention effectiveness study
- **📊 Variables**: 7 key measurements (satisfaction scores, sales data, purchase behavior)
- **💼 Context**: Business intervention impact on customer satisfaction and sales performance

###  Statistical Skills Demonstrated

#### 1. **Survey Distribution Analysis**
- Satisfaction score distribution assessment
- Response pattern analysis and completeness evaluation
- Customer segmentation performance analysis
- Experimental group balance verification

#### 2. **Distribution Testing & Normality**
- Shapiro-Wilk and Kolmogorov-Smirnov normality tests
- Missing data pattern analysis and impact assessment
- Outlier detection using Interquartile Range (IQR) method
- Survey response bias evaluation

#### 3. **Experimental Design Analysis**
- **Paired T-Tests**: Before vs After intervention comparisons
- **Independent T-Tests**: Control vs Treatment group analysis
- Assumption testing (equal variances, normality)
- Longitudinal data analysis methodology

#### 4. **Categorical Analysis**
- **Chi-Square Tests**: Independence testing for categorical associations
- Contingency table analysis and interpretation
- Purchase behavior pattern analysis
- Customer segment behavioral differences

#### 5. **Confidence Intervals & Effect Sizes**
- 95% confidence intervals for proportions and means
- Cohen's d calculation for practical significance
- Cramér's V for categorical association strength
- Statistical vs practical significance assessment

#### 6. **Survey Methodology**
- Missing data handling and impact evaluation
- Response rate analysis by experimental group
- Survey design quality assessment
- Statistical power and sample size considerations

##  Key Findings

### 🏆 Intervention Effectiveness
- **Sales Impact**: 30.8% improvement in Treatment vs Control group (p < 0.001)
- **Customer Satisfaction**: 3.6 point average increase (p < 0.001, medium effect)
- **Purchase Behavior**: Significant differences across customer segments
- **Statistical Confidence**: 4 out of 6 tests significant at p < 0.05 level

###  Experimental Results
| Comparison | Test Type | Result | Effect Size | Business Impact |
|------------|-----------|---------|-------------|-----------------|
| Satisfaction Before vs After | Paired t-test | ✅ Significant (p < 0.001) | Medium (d = 0.37) | Consistent improvement |
| Sales Before vs After | Paired t-test | ✅ Significant (p < 0.001) | Large (d = 1.74) | Substantial revenue growth |
| Control vs Treatment (Sales) | Independent t-test | ✅ Significant (p < 0.001) | Large (d = 0.98) | Treatment highly effective |
| Group vs Purchase Behavior | Chi-square | ❌ Not Significant (p = 0.25) | Small (V = 0.02) | Minimal association |

###  Customer Segmentation Insights
- **Low Value** customers: 51.2% purchase rate (highest conversion)
- **Medium Value** customers: 48.9% purchase rate
- **High Value** customers: 50.7% purchase rate
- Statistical significance detected across segments (χ² test, p < 0.001)

## 🛠️ Technical Implementation

###  Dependencies
pandas>=1.5.0 # Data manipulation and survey analysis
numpy>=1.21.0 # Numerical computing
scipy>=1.9.0 # Statistical testing (t-tests, chi-square)
matplotlib>=3.6.0 # Data visualization
seaborn>=0.12.0 # Statistical plotting
jupyter>=1.0.0 # Interactive analysis environment



###  Quick Start
Clone repository
git clone https://github.com/yourusername/customer-survey-analysis.git
cd customer-survey-analysis


Download dataset from Kaggle
Place 'Sales_with_NaNs_v1.3.csv' in project directory
Run analysis
jupyter notebook Customer_Survey_Analysis.ipynb
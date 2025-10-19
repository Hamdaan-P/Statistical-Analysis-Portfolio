-
 Missing data handling and impact evaluation
-
 Response rate analysis by experimental group
-
 Survey design quality assessment
-
 Statistical power and sample size considerations
##
  Key Findings
###
 🏆 Intervention Effectiveness
-
 
**
Sales Impact
**
: 30.8% improvement in Treatment vs Control group (p < 0.001)
-
 
**
Customer Satisfaction
**
: 3.6 point average increase (p < 0.001, medium effect)
-
 
**
Purchase Behavior
**
: Significant differences across customer segments
-
 
**
Statistical Confidence
**
: 4 out of 6 tests significant at p < 0.05 level
###
  Experimental Results
|
 Comparison 
|
 Test Type 
|
 Result 
|
 Effect Size 
|
 Business Impact 
|
|------------|-----------|---------|-------------|------------------|
|
 Satisfaction Before vs After 
|
 Paired t-test 
|
 ✅ Significant (p < 0.001) 
|
 Medium (d = 0.37) 
|
 Consistent improvement 
|
|
 Sales Before vs After 
|
 Paired t-test 
|
 ✅ Significant (p < 0.001) 
|
 Large (d = 1.74) 
|
 Substantial revenue growth 
|
|
 Control vs Treatment (Sales) 
|
 Independent t-test 
|
 ✅ Significant (p < 0.001) 
|
 Large (d = 0.98) 
|
 Treatment highly effective 
|
|
 Group vs Purchase Behavior 
|
 Chi-square 
|
 ❌ Not Significant (p = 0.25) 
|
 Small (V = 0.02) 
|
 Minimal association 
|
###
  Customer Segmentation Insights
-
 
**
Low Value
**
 customers: 51.2% purchase rate (highest conversion)
-
 
**
Medium Value
**
 customers: 48.9% purchase rate
-
 
**
High Value
**
 customers: 50.7% purchase rate
-
 Statistical significance detected across segments (χ² test, p < 0.001)
##
 🛠️ Technical Implementation
###
  Dependencies
pandas>=1.5.0 # Data manipulation and survey analysis
numpy>=1.21.0 # Numerical computing
scipy>=1.9.0 # Statistical testing (t-tests, chi-square)
matplotlib>=3.6.0 # Data visualization
seaborn>=0.12.0 # Statistical plotting
jupyter>=1.0.0 # Interactive analysis environment
###
  Quick Start
Clone repository
git clone https://github.com/Hamdaan-P/Statistical-Analysis-Portfolio.git
cd customer-survey-analysis
Download dataset from Kaggle
Place 'Sales_with_NaNs_v1.3.csv' in project directory
Run analysis
jupyter notebook Customer_Survey_Analysis.ipynb

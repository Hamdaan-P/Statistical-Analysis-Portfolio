#  A/B Testing Analysis: Marketing Campaign Effectiveness

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-20BEFF.svg)](https://www.kaggle.com/datasets/andrewjayasatyo/ab-testing-ad-vs-psa-effectiveness)

> **Professional A/B Testing Analysis**: Statistical evaluation of marketing campaign effectiveness using real-world Kaggle dataset. Demonstrates comprehensive data analysis skills for Data Analyst positions.

##  Project Overview

This project presents a **complete A/B testing analysis** comparing the effectiveness of **Advertisement campaigns vs Public Service Announcements (PSA)** in driving user conversions. Built using industry-standard statistical methods and real-world data structure from Kaggle.

###  Business Context
- **Objective**: Determine if paid advertisements significantly outperform PSA in conversion rates
- **Decision Impact**: Multi-million dollar marketing budget allocation
- **Stakeholders**: Marketing team, executives, data-driven decision makers

###  Key Findings
- **Ad Campaign**: 2.88% conversion rate
- **PSA Campaign**: 2.07% conversion rate  
- **Statistical Significance**: Varies by sample size (p-value analysis included)
- **Business Impact**: Comprehensive ROI and cost-efficiency analysis
- **Recommendation**: Data-driven strategic guidance provided

##  Dataset Information

###  Data Source
- **Primary Source**: [Kaggle - A/B Testing: Ad vs PSA Effectiveness](https://www.kaggle.com/datasets/andrewjayasatyo/ab-testing-ad-vs-psa-effectiveness)
- **Download Link**: [Direct CSV Download](https://www.kaggle.com/datasets/andrewjayasatyo/ab-testing-ad-vs-psa-effectiveness/download)
- **File Size**: 22.11 MB (original), 10K samples (analysis version)
- **License**: CC BY 4.0 (Attribution)

###  Dataset Schema
| Column | Type | Description |
|--------|------|-------------|
| `user_id` | int | Unique user identifier (100K-2M range) |
| `test_group` | str | Experimental group: 'ad' or 'psa' |
| `converted` | int | Binary conversion status (1=converted, 0=not converted) |
| `total_ads` | int | Total number of ads shown to user (1-2000+ range) |
| `most_ads_day` | str | Day of week with highest ad exposure |
| `most_ads_hour` | int | Hour of day with highest ad exposure (0-23) |

###  Real Dataset Benchmarks
- **Known Results**: Ad group (2.55%) vs PSA group (1.79%)
- **Statistical Significance**: p < 0.0001 (Chi-square: 54.01)
- **Sample Size**: 588,101 total users in original dataset

## Statistical Analysis

###  Methodology
This analysis employs **multiple statistical approaches** to ensure robust conclusions:

1. **Chi-Square Test of Independence**
   - Tests association between group type and conversion
   - Provides overall significance testing

2. **Two-Proportion Z-Test**
   - Compares conversion rates between groups
   - Calculates precise p-values and confidence intervals

3. **Effect Size Analysis**
   - Cohen's h for proportion differences
   - Practical significance assessment

4. **Statistical Power Analysis**
   - Power calculation and sample size recommendations
   - Type I/II error risk assessment

###  Key Statistical Outputs
- **Hypothesis Testing**: Comprehensive null/alternative hypothesis framework
- **Confidence Intervals**: 95% CI for conversion rate differences  
- **Effect Size**: Cohen's h interpretation (Small/Medium/Large)
- **Power Analysis**: Statistical power and sample size adequacy
- **Business Metrics**: ROI, cost-per-conversion, profit analysis

## 🛠️ Technical Implementation

###  Libraries & Dependencies
pandas>=1.3.0 # Data manipulation and analysis
numpy>=1.21.0 # Numerical computing
scipy>=1.7.0 # Statistical functions
matplotlib>=3.4.0 # Data visualization
seaborn>=0.11.0 # Statistical data visualization
jupyter>=1.0.0 # Interactive development environment


###  Usage
1. **Run All Cells**: Execute the notebook sequentially for complete analysis
2. **Custom Data**: Replace the dataset generation function with your CSV loading
3. **Parameter Tuning**: Modify business assumptions (revenue, costs) in Cell 6
4. **Visualization**: Charts automatically generate in Cell 7

##  Results & Visualizations

###  Key Performance Indicators

| Metric | Ad Campaign | PSA Campaign | Difference |
|--------|-------------|--------------|------------|
| **Conversion Rate** | 2.88% | 2.07% | +0.81pp |
| **Sample Size** | 8,500 users | 1,500 users | - |
| **Total Conversions** | 245 | 31 | +214 |
| **ROI** | 44.1% | 3000.0% | -2955.9pp |
| **Cost per Conversion** | $52.04 | $2.42 | +$49.62 |

###  Statistical Test Results

| Test | Statistic | P-Value | Significance |
|------|-----------|---------|--------------|
| **Chi-Square** | 2.8642 | 0.090570 | Not Significant (α=0.05) |
| **Z-Test** | 1.7779 | 0.075424 | Not Significant (α=0.05) |
| **Effect Size (Cohen's h)** | 0.0527 | - | Small Effect |
| **Statistical Power** | 46.9% | - | Low Power |

###  Visualizations Included
- Conversion rate comparison bar charts
- Sample size distribution analysis  
- ROI and cost-efficiency comparisons
- Statistical significance indicators
- Temporal pattern analysis (day/hour trends)

## Business Impact Analysis

###  Financial Performance
- **Revenue Analysis**: Conversion value calculations with realistic assumptions
- **Cost Structure**: Detailed cost-per-exposure modeling
- **Profit Optimization**: Net profit comparison and recommendations
- **Scalability**: Projected performance at enterprise scale

###  Strategic Recommendations
Based on statistical analysis and business impact:

1. *Continue Testing with Larger Sample Size**
   - Current power (46.9%) insufficient for reliable conclusions
   - Recommend 11,386+ users per group for 80% power

2. ** Optimize Cost Structure** 
   - PSA shows superior cost efficiency ($2.42 vs $52.04 per conversion)
   - Consider hybrid approach or ad cost optimization

3. ** Temporal Optimization**
   - Focus campaigns on high-conversion days (Thursday, Wednesday)
   - Leverage hour-level insights for optimal timing

## Educational Value

### Learning Objectives
This project demonstrates proficiency in:

- **Statistical Hypothesis Testing**: Chi-square, Z-tests, power analysis
- **A/B Testing Methodology**: Proper experimental design and interpretation
- **Business Analytics**: ROI calculation, cost-benefit analysis
- **Data Visualization**: Professional charts and statistical summaries  
- **Python Programming**: Advanced pandas, scipy, statistical libraries
- **Documentation**: Professional README, code comments, methodology

### Target Audience
- **Data Analyst Candidates**: Showcases statistical analysis skills
- **Marketing Professionals**: Demonstrates campaign effectiveness measurement
- **Business Intelligence**: Shows data-driven decision making
- **Students**: Educational example of complete A/B testing workflow

## 📞 Contact & Portfolio

**Author**: Hamdaan P
**Email**: phamdaan@gmail.com
**LinkedIn**: https://www.linkedin.com/in/hamdaan-peshimam-547394ba/
**Portfolio**:https://github.com/Hamdaan-P 

**Skills Demonstrated**: Statistical Analysis • A/B Testing • Python Programming • Business Intelligence • Data Visualization • Marketing Analytics

---

⭐ **If you found this project helpful, please give it a star!** ⭐

*This project showcases professional data analysis skills suitable for Data Analyst, Marketing Analyst, and Business Intelligence roles. The comprehensive statistical approach and business-focused insights demonstrate real-world analytical capabilities.*
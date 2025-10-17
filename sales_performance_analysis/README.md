# Sales Performance Analysis

This repository contains a Jupyter Notebook that demonstrates basic statistical analysis on a sales dataset. The project is designed to showcase statistical skills in data analysis, suitable for a Data Analyst portfolio. It covers data exploration, descriptive statistics, visualizations, correlation analysis, grouped statistics, and hypothesis testing.

## Project Overview

- **Objective**: Analyze sales performance using a sample sales dataset to compute key statistics, visualize distributions, identify correlations, perform grouped aggregations, and conduct hypothesis testing (e.g., comparing sales between the USA and other countries).
- **Tools/Languages**: Python (Jupyter Notebook), with libraries for data manipulation and visualization.
- **Key Techniques**:
  - Descriptive statistics (mean, median, std deviation).
  - Data visualization (histograms, heatmaps).
  - Correlation analysis.
  - Grouped aggregations.
  - Hypothesis testing (independent t-test).

## Dataset

The analysis uses the "Sample Sales Data" dataset from Kaggle, which includes sales records with columns like `SALES`, `QUANTITYORDERED`, `PRODUCTLINE`, `COUNTRY`, and more.

- **Source**: [Sample Sales Data on Kaggle](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)
- **File**: `sales_data_sample.csv` (download and place it in the same directory as the notebook).
- **Encoding**: The dataset is loaded with `latin1` encoding to handle special characters.

**Note**: You must download the dataset separately (Kaggle requires login). The notebook assumes the CSV file is in the project root.

## Requirements

- Python 3.x
- Jupyter Notebook (or JupyterLab/Google Colab for running the `.ipynb` file)

### Required Libraries

Install the following Python libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scipy
```

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical computations.
- `matplotlib` & `seaborn`: For visualizations (histograms, heatmaps).
- `scipy`: For statistical tests (e.g., t-test).

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone git clone https://github.com/Hamdaan-P/Statistical-Analysis-Portfolio.git
   cd your-repo-name
   ```

2. **Download the Dataset**:
   - Go to the [Kaggle link](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data).
   - Download `sales_data_sample.csv` and place it in the repository root.

3. **Set Up Environment** (optional, if using virtualenv):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt  # If you create a requirements.txt file
   ```

4. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
   - Open `sales_performance_analysis.ipynb` in your browser.
   - Run the cells sequentially (Shift + Enter).

Alternatively, upload the notebook to [Google Colab](https://colab.research.google.com/) and upload the CSV file there.

## Notebook Structure

The notebook (`sales_performance_analysis.ipynb`) is structured as follows:

1. **Import Libraries**: Load necessary Python packages.
2. **Load the Dataset**: Read the CSV file and display the first few rows.
3. **Data Exploration**: Use `df.info()` and `df.describe()` to understand the data.
4. **Handling Missing Values**: Fill missing values in non-critical columns (e.g., ADDRESSLINE2, STATE).
5. **Descriptive Statistics**: Compute mean, median, and standard deviation for `SALES` and `QUANTITYORDERED`.
6. **Visualization - Sales Distribution**: Histogram with KDE for sales values.
7. **Correlation Analysis**: Heatmap of correlations between numerical variables.
8. **Grouped Statistics**: Aggregate mean, median, and std deviation of `SALES` by `PRODUCTLINE`.
9. **Hypothesis Testing**: Independent t-test to compare sales between USA and other countries (with p-value interpretation).

## Sample Outputs

- **Descriptive Stats Example**:
  ```
  Mean Sales: 3553.88907190932
  Median Sales: 3184.8
  Standard Deviation of Sales: 1841.8651057401805
  ```

- **Hypothesis Test Example**:
  ```
  T-statistic: 1.2782975174677325
  P-value: 0.20124970583793125
  No significant difference.
  ```

Run the notebook to see full outputs, including plots.

## License

This project is licensed under the MIT License. Feel free to use it for educational or portfolio purposes.

## Contact

If you have questions or suggestions, open an issue in this repository or contact me at [phamdaan@gmail.com].


This project was created to showcase statistical skills for a Data Analyst role.

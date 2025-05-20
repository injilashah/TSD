# TSD Project

This project focuses on time series data analysis and preprocessing techniques, with an emphasis on achieving stationarity. It explores various methods for analyzing time series data, handling non-stationarity, and applying transformations to make the data suitable for modeling.

## Installation

Install dependencies using:

```
pip install -r requirements.txt
```

## Usage

To start the project, run:

```
python main.py
```

## Project Structure

- `src/` - Source code (if any)
- `Univariate_analysis.ipynb` - Jupyter Notebook containing the time series analysis and preprocessing steps.
- `data/` - Directory containing the Electric_Production.csv dataset.
- `requirements.txt` - Lists the Python packages required to run the notebook.
- `public/` - Static assets (if any)
- `package.json` - Project configuration (if any)

## Key Steps Covered in the Notebook:

1.  **Data Exploration:** Loading and inspecting the time series data, checking for missing values, and visualizing the data.
2.  **Time Series Decomposition:** Decomposing the time series into trend, seasonal, and residual components to understand underlying patterns.
3.  **Stationarity Testing:** Applying Augmented Dickey-Fuller (ADF) and KPSS tests to check for stationarity.
4.  **Skewness and Kurtosis Analysis:** Checking the distribution of the data.
5.  **Variance Analysis:** Checking the variance of the data.
6.  **Autocorrelation Analysis:** Checking the correlation of the data with its past values.
7.  **ARCH Effect Testing:** Applying ARCH test to check for heteroskedasticity.
8.  **Stationarity Transformation:** Applying transformations such as differencing and logarithmic transformation to convert non-stationary data into stationary data.
9.  **GARCH Modeling:** Applying GARCH model to check for stationarity.
10. **Seasonality Analysis:** Applying tests to check for seasonality.

## License

MIT

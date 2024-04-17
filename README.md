# **Time Series Forecasting of Superstore Sales Data**
### **_Author: Paridhi Arya, S20210020305_**
#### _Python for Data Science Project, March 2024_
## Exploratory Data Analysis (EDA)

The Exploratory Data Analysis (EDA) phase is a crucial preliminary step in my project on time series forecasting for Superstore sales data. my focus here is to leverage visualizations to understand the general trends, detect seasonal patterns, identify outliers, and gain quick insights that will inform my forecasting models. This README outlines the objectives, methodologies, and tools used in the EDA process.

### Objectives

The primary objectives of my EDA are to:

1. Understand the general sales trends for the categories "Furniture," "Technology," and "Office Supplies."
2. Detect any seasonal patterns or cyclic behaviors in the sales data.
3. Identify outliers or anomalies that may need further investigation.
4. Assess the stationarity of the time series data.
5. Explore correlations and relationships between different variables.
6. Aggregate data at different temporal resolutions to uncover broader trends.
7. Compare sales performance across different categories.
8. Understand the distribution of sales data.

## How to run the project
1. Firstly, there is the 'General_EDA.ipynb' file for general EDA. 
2. A corresponding dashboard 'dashboard.pbix' is also attached - Power BI dashboard 
3. ARIMA Prediction and Forecasting for 3 item categories:
   - 'main_OfficeSupplies.ipynb' :  For 'Office Supplies' category
   - 'main_Furniture.ipynb' :  For 'Furniture' category
   - 'main_Technology.ipynb' :  For 'Technology' category
  
## Methodologies and Tools

### Python Libraries Used

The following Python libraries and packages form the backbone of my Exploratory Data Analysis (EDA) for the time series forecasting project:

- **Warnings**: Used to suppress warnings to ensure clean notebook outputs.
- **OS**: Provides a way of using operating system dependent functionality.
- **Itertools**: Offers a suite of tools for creating iterators for efficient looping.
- **Pandas**: Essential for data manipulation and analysis, particularly for working with structured data.
- **NumPy**: Adds support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these arrays.
- **Datetime**: Enables manipulation of dates and times.
- **Statsmodels**: Provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests, and statistical data exploration. Noteworthy sub-modules used include:
  - **Time Series Analysis**: Tools for time series analysis, such as plotting functions for Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF), and the implementation of the Augmented Dickey-Fuller (ADF) test.
  - **Seasonal Decompose**: Helps in decomposing the time series data into trend, seasonal, and residual components.
- **Dateutil**: Extends the datetime module with additional features.
- **Seaborn**: A visualization library based on Matplotlib that provides a high-level interface for drawing attractive and informative statistical graphics.
- **Matplotlib**: A plotting library for creating static, animated, and interactive visualizations in Python. It includes:
  - **Matplotlib Dates (mdates)**: Provides helper functions for working with dates in plotting functions.
  - **RCParams**: Allows customization of Matplotlib plots.
- **Inline Magic (%matplotlib inline)**: Enables the inline display of Matplotlib plots within Jupyter Notebooks.


### Visualization Techniques:

1. **Line Charts and Area Plots:** For visualizing general trends and assessing stationarity.
2. **Seasonal Plots and Heatmaps:** To detect seasonal patterns or cyclic behaviors.
3. **Box Plots and Scatter Plots:** For identifying outliers or anomalies.
4. **Correlation Matrices and Heatmaps:** To explore relationships between variables.
5. **Bar Charts:** For visualizing aggregated data at different temporal resolutions.
6. **Grouped Bar Charts and Overlaying Line Plots:** To compare sales across categories.
7. **Histograms and Kernel Density Plots:** To understand the distribution of sales data.

### Insights from EDA

My EDA has unearthed several key insights that will guide the subsequent phases of my time series forecasting project. These insights include identifying underlying trends, seasonal patterns, and potential stationarity issues within the dataset. Through visual and statistical analysis, we have a better understanding of the data's characteristics and the challenges that lie ahead in forecasting.

### Concluding Remarks

The methodologies and tools outlined above have equipped us with a comprehensive understanding of the Superstore sales data's underlying trends, seasonal patterns, and peculiarities. These insights are invaluable as we proceed to the modeling stage, where we will apply time series forecasting models to predict future sales. The EDA process has ensured that my approach to forecasting is data-driven and informed by a deep understanding of the dataset's characteristics.

### License

This project and its contents are made available under the MIT License, which offers wide flexibility for use, modification, and distribution, under the condition of giving credit to the original authors and source.

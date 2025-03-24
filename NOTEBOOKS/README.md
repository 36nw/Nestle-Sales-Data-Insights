# Notebooks Directory

This directory contains Jupyter Notebooks used for the analysis of Nestle's sales data.

## Contents

-   `01_Exploratory_Data_Analysis.ipynb`: This notebook performs exploratory data analysis (EDA) on the Nestle sales dataset. It includes data cleaning, visualization of sales trends, and initial insights into the data.
-   `02_Market_Basket_Analysis.ipynb`: This notebook attempts to perform Market Basket Analysis (MBA) on the sales data, exploring product associations. (Note: This analysis was adapted due to the prevalence of single-item transactions).
-   `03_Time_Series_Forecasting.ipynb`: This notebook uses time series forecasting techniques, including ARIMA and Prophet, to predict future sales trends.
-   `04_Segmentation_Analysis.ipynb`: This notebook performs segmentation analysis using K-Means and DBSCAN clustering to categorize sales locations and mediums based on performance metrics.
-   `05_Geospatial_Visualization.ipynb`: This notebook creates an interactive map to visualize sales performance by location, using Folium.

**(Add your other notebook titles and descriptions here as you create them)**

## Usage

These notebooks are designed to be run sequentially to follow the analysis process. Ensure that the `nestle_sales_data.xlsx` file is located in the `data/` directory.

1.  Navigate to the `notebooks/` directory.
2.  Open a Jupyter Notebook server: `jupyter notebook`
3.  Open the desired notebook (`.ipynb` file).
4.  Run the cells in the notebook to reproduce the analysis and visualizations.

## Dependencies

The notebooks in this directory rely on the following Python libraries:

-   Pandas
-   NumPy
-   Scikit-learn
-   Prophet
-   Folium
-   Matplotlib
-   Seaborn

Ensure that these libraries are installed before running the notebooks. You can install them using:

```bash
pip install -r ../requirements.txt

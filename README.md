# Nestle Sales Insights: From Data Deluge to Strategic Decisions
A project analyzing Nestle's sales data to improve sales strategies through forecasting, segmentation, and interactive visualizations. Includes Prophet forecasting, K-Means/DBSCAN clustering, geospatial analysis, and Tableau dashboard creation.

## Table of Contents

- [Project Overview](#project-overview)
- [Business Problem](#business-problem)
- [Goal](#goal)
- [Data Source](#data-source)
- [Tools & Technologies](#tools--technologies)
- [Methodology](#methodology)
- [Results & Findings](#results--findings)
- [Conclusion & Recommendations](#conclusion--recommendations)
- [Project Structure](#project-structure)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Authors](#authors)

## Project Overview

This project analyzes Nestle's sales data to extract actionable insights for strategic improvement. We navigate through challenges like single-item transactions to provide robust sales forecasts and segmentation, driving informed decision-making and optimizing resource allocation. Furthermore, this project includes the creation of a Tableau dashboard to provide interactive and easily understandable visualizations of key sales insights.

## Business Problem

Nestle faces challenges in understanding customer purchasing patterns, forecasting sales accurately, and optimizing sales channels and regional strategies. The complexity of sales data requires advanced analytical techniques to uncover hidden insights and drive business growth.

## Goal

The goals of this project are to:

* Identify product associations (initially) and individual product performance.
* Accurately forecast future sales trends.
* Segment sales data by location and medium to optimize strategies.
* Develop interactive visualizations to communicate findings effectively, including a comprehensive Tableau dashboard.
* Provide clear, data-driven business recommendations.

## Data Source

The dataset used in this project is Nestle's internal sales data, containing information on sales count, total revenue, sales medium, and location. The dataset consists of 18,115 rows and 13 columns.

## Tools & Technologies

* **Python:** Pandas (data manipulation), NumPy (numerical computations), Scikit-learn (machine learning), Prophet (time series forecasting).
* **Folium:** (Geospatial visualization).
* **Jupyter Notebooks:** (Analysis and code documentation).
* **Tableau:** (Interactive dashboard creation and data visualization).

## Methodology

1. **Data Loading and Preprocessing:** Cleaning and preparing the dataset for analysis.
2. **Exploratory Data Analysis (EDA):** Visualizing sales trends and identifying key patterns.
3. **Market Basket Analysis (MBA):** (Initial attempt, adapted due to data characteristics).
4. **Time Series Forecasting:** Utilizing ARIMA and Prophet models.
5. **Segmentation Analysis:** Applying K-Means and DBSCAN clustering.
6. **Geospatial Visualization:** Mapping sales performance by location.
7. **Tableau Dashboard Creation:** Developing an interactive dashboard to present key insights.
8. **Business Insight Extraction:** Translating findings into actionable recommendations.

## Results & Findings

* Prevalence of single-item transactions, necessitating a shift from MBA.
* Prophet demonstrated superior accuracy in sales forecasting.
* Significant disparities in sales performance across locations and mediums.
* Direct sales showed higher effectiveness compared to online channels.
* Interactive mapping revealed key sales hotspots and areas for improvement.
* A comprehensive Tableau dashboard was created to provide an intuitive and interactive overview of these findings, enabling easier exploration and deeper understanding of the data.

## Conclusion & Recommendations

* Prioritize online sales improvement through targeted strategies.
* Leverage Prophet for ongoing sales forecasting.
* Tailor regional marketing efforts based on segmentation analysis.
* Analyze and scale direct sales success.
* Utilize interactive visualizations, including the created Tableau dashboard**, for informed decision-making.

This project underscores the importance of adaptable analytical approaches and data-driven strategies for optimizing sales performance and informing strategic decision-making within Nestle. The inclusion of a Tableau dashboard enhances the accessibility and impact of the insights.

## Project Structure

Nestle_Sales_Insights/
* data/             # Contains the sales dataset
* notebooks/        # Jupyter notebooks with analysis and code
* visualizations/   # Saved visualizations and interactive maps
* tableau_dashboard/ # (Optional) Information or assets related to the Tableau dashboard
* reports/        # Final reports and presentations, including project overview and executive summary
* requirements.txt  # Python dependencies
* README.md         # This file


## Setup & Installation

1. Clone the repository: `git clone [https://github.com/your-username/Nestle_Sales_Insights.git]`
2. Navigate to the project directory: `cd Nestle_Sales_Insights`
3. Create a virtual environment (recommended): `python -m venv venv`, `source venv/bin/activate` (macOS/Linux), `venv\Scripts\activate` (Windows)
4. Install dependencies: `pip install -r requirements.txt`
5. Open the Jupyter notebooks in the `notebooks/` directory to explore the analysis. The Tableau dashboard can be accessed separately using Tableau Desktop or Tableau Public.

## Usage

- Explore the Jupyter notebooks to understand the data analysis process.
- Run the notebooks to reproduce the results and visualizations.
- Use the interactive map in the `visualizations/` directory to explore sales performance by location.
- Access the Tableau dashboard (if shared) to interact with key sales insights and explore the data visually.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues to suggest improvements or report bugs.

## License

The code in this repository is licensed under the MIT License.

## Authors

- Linkedin [@mugeyalcin](https://www.linkedin.com/in/mugeylcn/)

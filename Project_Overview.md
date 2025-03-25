# Nestle Sales Insights: From Data Deluge to Strategic Decisions

## Project Overview

This project aimed to transform Nestle's complex sales data into actionable insights, addressing the initial challenge of unexpected data structures and ultimately delivering strategic recommendations for sales optimization.

## The Hook 

"Nestle's sales data was a puzzle! We thought we'd find product pairings, but got single-item buys instead. How did we turn this data disaster into a goldmine of insights?"

## The Story 

We embarked on a mission to decode Nestle's sales data, initially aiming to find hidden product combinations with Market Basket Analysis (MBA). Imagine trying to build a recipe with only single ingredients – that's what we faced. The data was overwhelmingly composed of single-item transactions, rendering traditional MBA ineffective. This unexpected finding created a "conflict" that needed resolution.

## The Build-Up (Exploratory Data Analysis)

We started by exploring the data, visualizing daily sales trends. We noticed peculiar spikes in revenue, like sudden surges in early 2019 and 2020. We also observed a significant disparity between direct and online sales, with direct sales clearly outperforming online. This initial exploration built the context: there were hidden stories in the data, but we needed a new way to uncover them.

## The Hypothesis

"We can identify strong product associations to boost sales using Market Basket Analysis." This hypothesis was quickly challenged by the data's structure, forcing us to pivot.

## The Resolution

We shifted our focus to time series forecasting and segmentation analysis. We used Prophet to predict future sales, which proved far more accurate than ARIMA, especially in handling the unusual spikes. We also segmented sales data by location and sales medium using K-Means and DBSCAN, revealing key performance clusters.

We discovered:

-   **Prophet's forecasting accuracy:** It reliably predicted sales trends, showing us where to focus.
-   **Direct sales dominance:** Direct sales were a major revenue driver, highlighting the need to understand their success.
-   **Online sales opportunity:** Online sales lagged, indicating a clear area for improvement.
-   **Geographic performance variations:** Sales performance differed significantly across locations, requiring tailored strategies.

## The "Productionization" (Interactive Visualizations)

We created an interactive map that visualized sales performance by location. In addition to this geospatial analysis, a comprehensive Tableau dashboard was developed to provide an interactive and in-depth view of sales performance across various dimensions.** This tool allowed for easy identification of high-performing regions and areas needing attention, making the data accessible and actionable. The Tableau dashboard further enhanced this by offering a multi-faceted exploration of the data, including key metrics, trends, and comparisons, all in an intuitive visual format.

## The Business Value

Nestle should:

-   **Prioritize online sales improvement:** Implement targeted strategies to boost online revenue, leveraging our segmentation analysis.
-   **Leverage Prophet for ongoing sales forecasting:** Utilize Prophet’s accuracy to predict and prepare for future sales trends.
-   **Tailor regional marketing strategies:** Use the interactive map to focus on high-potential areas and address underperforming regions.
-   **Analyze and scale direct sales success:** Investigate the factors driving direct sales performance to replicate and enhance them.

## The Powerful Story

This project is a story of adaptability. We started with a clear goal, faced a significant challenge, and successfully pivoted to extract valuable insights. By combining forecasting and segmentation, we provided Nestle with actionable recommendations to optimize sales and drive growth. This project demonstrates how data analysis can turn a seemingly negative situation into a positive and profitable outcome.

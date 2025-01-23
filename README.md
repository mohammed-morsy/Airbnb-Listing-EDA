# Airbnb Listings EDA: Albany, New York

## Project Description

This project performs an Exploratory Data Analysis (EDA) of Airbnb listings in Albany, New York. The analysis investigates various factors such as price, availability, location, and property type to uncover trends and patterns that influence the demand for Airbnb listings in this region. The goal is to provide a comprehensive understanding of the Airbnb market in Albany, aiding stakeholders in making informed decisions regarding investments in this area.

## Objectives
	•	Analyze the key factors influencing the demand for Airbnb listings in Albany, including price, availability, location, and property type.
	•	Clean the dataset thoroughly by removing outliers, handling missing values, and ensuring data consistency.
	•	Visualize the trends and patterns in the dataset using advanced data visualization techniques.
	•	Perform statistical analysis to validate findings and derive actionable insights.

## Tools Used
	•	Python and Jupyter Notebook were employed for the analysis and visualizations.
	•	Libraries used: Pandas, NumPy, Matplotlib, Seaborn.

## Data Source

The dataset used in this analysis was obtained from Inside Airbnb, and it contains 404 Airbnb listings from Albany, New York, updated until March 10, 2024.

## Dataset Overview
	•	404 observations and 75 columns of data.
	•	Contains a mixture of categorical and numerical features.
	•	Data was preprocessed to focus solely on listings located in Albany, New York (dropping all other locations).

## Key Features:
	•	Price: The price range for Airbnb listings in Albany varies from $26 to $628, with the majority of listings priced between $50 and $150.
	•	Property Type: Most listings are categorized as Entire rental unit (51%), Private room in home (17.5%), and Entire home (15.5%).
	•	Room Type: Entire home/apt (75%) and Private room (25%) are the most demanded room types in Albany.
	•	Number of Bedrooms: Listings with 1 or 2 bedrooms account for the highest demand (60% and 20% respectively).

## Actions Taken for Data Cleaning:
	1.	Dropped unuseful features and observations not related to Albany, NY.
	2.	Handled missing values (2571 null values identified).
	3.	Handled outliers by filtering extreme values from price and other relevant columns.
	4.	Formatted data to ensure consistency and usability.

## Data Analysis and Insights

Price Distribution:
	•	The most popular price range is between $50 and $150.
	•	Prices above $250 are associated with a significant drop in demand.

## Key Factors Influencing Demand:
	•	Number of Beds: Listings with 1 or 2 beds are the most popular, accounting for 50% and 28% of the demand.
	•	Number of Accommodates: Listings with 2, 4, 1, and 3 accommodates are in high demand.
	•	Number of Bedrooms: Listings with 1 or 2 bedrooms account for 80% of the demand.
	•	Property Type: The most in-demand property types are Entire rental unit, Private room in home, and Entire home.

## Visualizations:
	•	Pair Plot: Shows relationships between multiple variables, highlighting the correlation between price, accommodates, bedrooms, and beds.
	•	Bar Plots and Box Plots: Illustrate the distribution of key features like price and bedrooms across different categories (e.g., room types, property types).

## Business Insights:
	•	High Demand Price Range: Listings priced between $50 and $150 are the most attractive for investment.
	•	Small Number of Beds: Listings with 1 or 2 beds are more likely to be in demand, whereas listings with 5 or more beds experience lower demand.
	•	Accommodates: Listings with 2 or 4 accommodates are preferred, making them the best choices for investment.
	•	Property Type: The most popular property type for investment is the Entire rental unit, followed by Private room in home and Entire home.

## Business Conclusion:
	•	Albany, NY is a highly sought-after market for Airbnb listings, and focusing on listings within the $50 to $150 price range with 1 or 2 beds and 2-4 accommodates will yield the best returns on investment.
	•	Property types like Entire rental unit are the most in-demand and thus should be prioritized in investment decisions.

## Versions of Libraries Used:
	•	pandas version: 2.2.2
	•	matplotlib version: 3.9.2
	•	seaborn version: 0.13.2
	•	numpy version: 1.26.4

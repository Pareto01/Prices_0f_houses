# Prices-of-houses

### Abstract

This project explores the variations in house prices across different locations in Nigeria, with a specific focus on the influence of inherent characteristics such as the number of bedrooms, bathrooms, and parking spaces. By leveraging data from data.world and employing R for data analysis and visualization, this study aims to identify patterns and insights that can inform stakeholders about the real estate market in Nigeria. Key findings include the identification of the most and least expensive locations to buy houses and the factors that significantly impact house prices.

### Methodology

**1. Data Collection:**
   - The dataset was sourced from data.world, containing information about house prices in various locations across Nigeria.
   - Data attributes included state, town, number of bedrooms, bathrooms, parking spaces, and price.

**2. Data Preparation:**
   - Imported the dataset into R using the `read.csv` function.
   - Loaded necessary packages, including `tidyverse`, for data manipulation and visualization.
   - Conducted an initial inspection of the dataset using functions like `glimpse()` and `head()` to understand its structure and contents.
   - Cleaned the dataset by handling missing values and ensuring the data was suitable for analysis.

**3. Data Analysis:**
   - **Average Price Analysis:** Calculated the average price of 3-bedroom flats across different states and towns using group-by and summarize functions.
   - **Location-Specific Analysis:** Focused on high-demand areas such as Lagos and Abuja, identifying the towns with the highest and lowest prices for 3-bedroom flats.
   - **Price Determinants:** Explored the relationship between house prices and inherent characteristics (e.g., number of bedrooms, bathrooms, parking spaces) using scatter plots and summary statistics.

**4. Visualization:**
   - Created various visualizations to illustrate findings:
     - **Interactive Maps:** Used geographical plotting to show the distribution of house prices across states.
     - **Heatmaps:** Highlighted areas with high and low house prices.
     - **Scatter Plots:** Demonstrated correlations between house prices and specific characteristics (e.g., bedrooms, parking spaces).

**5. Key Insights:**
   - Identified Lagos, Abia, Abuja, Delta, and Anambra as the most expensive states for purchasing houses.
   - Determined that the number of bedrooms and parking spaces significantly influence house prices, while the number of bathrooms has a lesser impact.
   - Highlighted Ikoyi as the most expensive location in Lagos and Imota as the cheapest.
   - Identified Gwagwalada as the cheapest area in Abuja, with Maitama being the most expensive.
   - Concluded that semi-detached duplexes are the most expensive house types, whereas semi-detached bungalows are the cheapest.

By combining data analysis with insightful visualizations, this project provides a comprehensive overview of the real estate market in Nigeria, aiding stakeholders in making informed decisions.

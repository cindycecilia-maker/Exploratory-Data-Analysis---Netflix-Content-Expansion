# Exploratory Data Analysis: Netflix Content Expansion (US vs Asia)

## 1. Objectives
* To analyze and compare the production growth trends of Netflix content between the United States and key Asian regions (Taiwan, South Korea, Japan) between 2017 and 2021.
* To compare the distribution of content types (Movies vs. TV Shows) produced by each region.

## 2. Pseudocode & Algorithm
1. **Initialize:** Load the Netflix dataset into a dataframe.
2. **Determine Range:** Find the maximum `release_year` in the dataset to set the 5-year window.
3. **Filter Data:** Keep only rows where `release_year` falls within the 5-year window.
4. **Categorize (If-Else Logic):**
   - Read each row in the dataset.
   - `IF` the `country` column contains "United States", categorize as "US Production".
   - `ELSE IF` the `country` column contains "Taiwan", "South Korea", or "Japan", categorize as "Asian Production".
5. **Aggregate:** Count total productions grouped by year, region, and content type.
6. **Output:** Plot a line chart for production growth and a grouped bar chart for content type comparison.

## 3. Source Code & Execution
The complete Python script with data processing and visualization can be found in the attached `.ipynb` notebook file in this repository. You can also view and run it directly on Google Colab.

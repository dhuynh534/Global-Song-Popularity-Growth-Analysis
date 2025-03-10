# Global-Song-Popularity-Growth-Analysis
SQL Data Cleaning and Tableau Dashboard for Spotify Data Visualization

## Project Overview
This project analyzes the **[Top Spotify Songs in 73 Countries](https://www.kaggle.com/datasets/asaniczka/top-spotify-songs-in-73-countries-daily-updated)** dataset by Asaniczka on Kaggle. The objective was to explore song popularity growth across 73 countries and uncover insights into the trends, relationships, and factors influencing monthly performance.

## Key Insights
- **Notable Growth Pattern**: The analysis revealed a distinct ebb and flow in the average song popularity growth, particularly from March to July. This pattern was most evident in non-western countries.
- **Western Markets**: Western countries exhibited a more consistent growth pattern and were resilient to changes, showing stability in song popularity over time.
- **Regional Differences**: There is a clear contrast in song popularity growth between western and non-western countries. Further investigation into the factors driving these differences could provide valuable insights for targeted marketing.

## Methods

### Data Cleaning (SQL):
- Removed duplicates and missing data from the original dataset.
- Standardized column data types and formatting for consistency.
- Checked for outliers to ensure the quality of the analysis.

### Visualizations (Tableau):
- Created a **world heat map** to visualize regional popularity trends.
- Used a **bar chart** to compare growth rates across countries.
- Created a **line graph** to illustrate the fluctuation in average song popularity growth over time.

## Next Steps
The anomaly between the growth rates of western and non-western countries warrants further investigation into the underlying factors. Understanding these factors could help inform business decisions, such as tailoring marketing efforts to coincide with specific "hot months" for song releases or promotions.

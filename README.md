# Coffee Production Analysis

## Overview
This project analyzes coffee production and price trends across different countries using Python. The analysis includes data visualization of production volumes and price changes over time, focusing on major coffee-producing countries like Brazil and Colombia.

## Features
- Time series analysis of coffee production trends
- Price trend analysis across different countries
- Data cleaning and preprocessing
- Interactive visualizations using Matplotlib and Seaborn

## Technologies Used
- **Python 3.x**
- **NumPy**: For numerical computations and array operations
- **Pandas**: For data manipulation and analysis
- **Matplotlib**: For basic data visualization
- **Seaborn**: For enhanced statistical visualizations

## Dataset
The project uses a CSV file (`coffee_production.csv`) containing the following columns:
- `year`: Production year
- `country`: Coffee producing country
- `production`: Coffee production volume
- `price`: Coffee price

## Implementation Details

### Data Preprocessing
- Converting year to datetime format
- Converting production and price columns to numeric format
- Grouping data by year and country for aggregate analysis

### Visualizations
1. **Production Trends**
   - Line plot showing production volumes over time
   - Color-coded by country
   - Interactive visualization with legend

2. **Price Analysis**
   - Time series visualization of coffee prices
   - Country-wise price comparison
   - Trend analysis across years



## Future Improvements
- Add more countries to the analysis
- Implement statistical tests for trend analysis
- Add seasonal analysis
- Include weather data correlation
- Export capabilities for processed data

# Page View Time Series Visualizer

This project involves visualizing time series data using line charts, bar charts, and box plots. The dataset represents daily page views on the freeCodeCamp.org forum from **May 9, 2016, to December 3, 2019**. The visualizations aim to identify patterns, trends, and seasonal variations in page visits.  

## Project Objectives  
1. **Data Preparation**  
   - Load the dataset (`fcc-forum-pageviews.csv`) using Pandas, with the date column as the index.  
   - Clean the data by filtering out extreme outliers (top and bottom 2.5% of page views).  

2. **Data Visualizations**  
   - **Line Chart**:  
     Visualize daily page views over the entire dataset timeline.  
   - **Bar Chart**:  
     Show average monthly page views grouped by year.  
   - **Box Plots**:  
     Compare page view distributions:  
     - Year-wise trends.  
     - Month-wise seasonality.  

## Features  
- **Line Chart**:  
  - Title: *Daily freeCodeCamp Forum Page Views 5/2016-12/2019*.  
  - X-axis: *Date*.  
  - Y-axis: *Page Views*.  

- **Bar Chart**:  
  - Average monthly views per year with a legend for month labels.  
  - X-axis: *Years*.  
  - Y-axis: *Average Page Views*.  

- **Box Plots**:  
  - Year-wise Box Plot: Title: *Year-wise Box Plot (Trend)*.  
  - Month-wise Box Plot: Title: *Month-wise Box Plot (Seasonality)*.  
  - Properly labeled axes and month names starting from January.  

## Development  
- Implement the visualizations in `time_series_visualizer.py`.  
- Use `main.py` to test and debug your code during development.  

## Testing  
- Unit tests are available in `test_module.py`. They are integrated into `main.py` for easier execution.  

## Tools Used  
- **Python Libraries**: Pandas, Matplotlib, Seaborn.

--- 

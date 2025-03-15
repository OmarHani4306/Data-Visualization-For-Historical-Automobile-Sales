# Data-Visualization-For-Historical-Automobile-Sales



## Project Overview
This project analyzes historical automobile sales data to understand how economic recessions impact vehicle sales. The goal is to provide insights to company directors by creating data visualizations and interactive dashboards.

## Dataset
The dataset contains:
- **Date**: Observation date  
- **Recession**: Binary indicator (1 = recession, 0 = normal)  
- **Automobile_Sales**: Number of vehicles sold  
- **GDP**: Per capita GDP value (USD)  
- **Unemployment_Rate**: Monthly unemployment rate  
- **Consumer_Confidence**: Index representing consumer spending confidence  
- **Seasonality_Weight**: Seasonal effect on sales  
- **Price**: Average vehicle price  
- **Advertising_Expenditure**: Advertising spending  
- **Vehicle_Type**: Type of vehicle sold (Supermini, Small family, Medium family, Executive, Sports)  
- **Competition**: Market competition measure  
- **Month, Year**: Extracted from Date  

## Project Structure
This project is divided into two main parts:

### **Part 1: Data Visualization**
Using Matplotlib, Seaborn, and Folium, we generate various plots:
- **Line charts**: Analyze annual sales trends.
- **Comparative line plots**: Evaluate sales trends of different vehicle types during recessions.
- **Bubble plots**: Visualize seasonality effects on sales.
- **Scatter plots**: Examine correlations between vehicle price and sales.
- **Pie charts**: Show advertising expenditure distributions.
- **Subplots**: Compare GDP variations during recession vs. non-recession periods.

### **Part 2: Interactive Dashboard**
Built using Dash and Plotly to allow company directors to explore key statistics interactively:
- Dropdowns for selecting time periods and vehicle types.
- Dynamic graphs showing recession trends and yearly sales statistics.
- Callback functions for real-time data updates.



## Key Insights
- Sales generally decline during recessions, with varying impact across vehicle types.
- Unemployment rate and consumer confidence significantly affect automobile sales.
- Price fluctuations and advertising expenditure influence sales trends during economic downturns.


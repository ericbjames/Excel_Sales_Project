# Excel_Sales_Project
## Overview
- Used Python (Pandas) to clean a years worth of sales data from a mock technology retail company containing over 180,000 rows.
- Visualized and gained insights from data by building a dashboard through Excel which included sales by city, product, and time.

### Original Data Formatting
Without cleaning and formatting the data, no insights could have been gained. The data came in individual month .csv files with many blanks and duplicated values.
<p align="center">
<img width="600" alt="Original formating" src="https://user-images.githubusercontent.com/101911329/182044263-21b0d4d8-7ed8-4a53-a015-46f762073c5b.png">
</p>

# Data Preparation
Tasks completed during preparations step:
- Combine the 12 individual .csv files.
- Clean rows with blanks and duplicates.
- Split columns with multiple pieces of information such as date/time or purchaser's address.
- Create a new copy with only the columns necessary for analysis.
- Categorize product types to aid in future analysis and visualization.

View code [Here](https://github.com/ericbjames/Excel_Sales_Project/blob/main/Data%20Preparation.ipynb)

# Analysis

## Insights:
- October and December had the highest sales of the year. 
- 12:00 and 19:00 were the times with the highest sales.
- Cell phones, laptops, and headphones accounted for over 70% of sales.
- San Francisco, Los Angeles, and New York accounted for 53% of total sales.
- Apple products accounted for 55% of total sales.

## Actionable steps for the business:
- Look at the current strategy for attaching accessories to a purchase. Better store positioning, add-on deals, or website recommendations could boost attach rate. This should also include adding more accessories based on market research that pair well with the site’s most sold products: iPhone, Google phone, MacBook Pro, and ThinkPad.
- Focusing marketing efforts on the typical customer during a given period such as a students/parents during back to school season should increase sales year-over-year.

## Points for further analysis:
- What deals were active during October and December? What part did back to school season and holiday have on the best months?
- What is the typical customer profile? Student or business?
- Gaining access to data for the profit/loss of products would help decide on which products to remove and which to keep stocked.


<p align="center">
<img width="600" alt="Import   Cleaning" src="https://user-images.githubusercontent.com/101911329/182038453-c7787c04-0ec8-4139-8417-fe33ce7d9c75.png">
</p>
<p align="center">
<img width="600" alt="Create and separate columns" src="https://user-images.githubusercontent.com/101911329/182038450-db9ed136-eb0d-4bda-ad84-b9a1cdd0bc9b.png">
</p>
<p align="center">
<img width="600" alt="Export" src="https://user-images.githubusercontent.com/101911329/182038452-b6ee1b1f-bde7-4bee-94b7-5c8776941baa.png">
</p>

### Sales by Product
<p align="center">
<img width="600" alt="Sales by Product" src= "https://user-images.githubusercontent.com/101911329/186280316-02f8a6a7-d5b1-4761-b1d6-27d154c35737.png">

</p>
### Sales by Category
<p align="center">
<img width="600" alt="Sales by Category" src="https://user-images.githubusercontent.com/101911329/181634820-c98646e4-96f8-4df9-93d3-cdf78888a55e.png">
</p>
### Top 5 Cities by Sales
<p align="center">
<img width="600" alt="Top 5 Cities" src="https://user-images.githubusercontent.com/101911329/181634835-650418b4-2afb-4313-bce9-54121bea61ca.png">
</p>
### Sales by Month
<p align="center">
<img width="600" alt="Sales by Month" src="https://user-images.githubusercontent.com/101911329/181634858-400c6e04-96c8-472a-8c34-45405f228ae4.png">
</p>
### Sales by Hour
<p align="center">
<img width="600" alt="Sales by Hour" src="https://user-images.githubusercontent.com/101911329/181634865-4223010b-b6a4-4c2d-af3c-d04df177a7de.png">
</p>

# Final Dashboard
<p align="center">
<img width="1112" alt="Dashboard" src="https://user-images.githubusercontent.com/101911329/181634710-dbcfc90b-b964-4f27-b836-8b3970d7c257.png">
</p>

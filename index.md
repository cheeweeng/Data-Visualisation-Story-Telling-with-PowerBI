This repository contains the datasets, the PowerBI workbook with visualizations and dashboards developed and submitted to Ngee Ann Polytechnic School of InfoComm Technology in December 2025.  
The goal of this assignment is to design and implement an interactive dashboard using Power BI to explore the Housing and Development Board (HDB) resale flat prices dataset in Singapore, spanning 1990 to 2022.
The primary objectives are to prepare and clean the dataset for analysis, formulate meaningful exploratory questions tailored to a target audience of regular Singapore residents — who often rely on HDB flats 
as primary housing and investment assets — and derive actionable insights through univariate/multivariate analyses and visualizations, cumulating in interactive dashboards to answer real-world business questions.  

* Location-based Visuals *

<heatmap>
This visualisation is a heatmap to explore which towns are the most expensive in terms of average resale price per sqft. 
The colour gradient allows the audience to quickly spot areas of high and low intensity at a glance without conscious effort.   

<highest transaction>
This bar chart shows the total transactions by town. When complement with a flat-type slicer, this chart shows liquidity for which flat-type in which town, i.e. high transaction volume equals easier to buy/sell.  

<undervalued>
This filled-map visual paints each Singapore town according to percent_of_txn of 3-room flats in storey range 4 to 6 that are below the national average. 
The darker shades indicates where undervalued opportunities appear more frequently and lighter shades the opposite. The viewer can quickly scan the landscape and spot where value resides.  

<Time Trends>
 
This column bar chart provides insights into whether there is seasonal trend in resale volume. The Asian Financial Crisis started in July 1997 and Singapore weathered the spillover effect 
through to the second half of 1998 (Chew, 2016). From the transaction volume on this chart, there was a slight dip towards the end of 1997, after that there was a consistent uptrends in transaction volume. 
As a matter of fact, the highest resale transaction volume could be seen from Oct 1997 to Aug 1998.  

<multiple lines>
The above multi-line chart shows the trend of average flat size (sqft) for all flat type changes over the years. This visual can validate the general consensus that flats are getting smaller and smaller. 
The average floor area (sqft) peaked in the mid-1990 and has been on a rather sharp downward trend, implying flat size are getting smaller and smaller. 
Executive flats can be seen as having the most dramatic reduction in average flat size (sqft).   

<high floors>
This bar chart shows the average resale price across different storey ranges, arranged from the highest floors on the left to the lowest floors on the right. 
The visual confirms a strong height premium — the higher the floor, the higher the typical resale price, even surpassing the million-dollar mark.  

<scatter>
This scatter plot shows the correlation between floor area (sqft) and resale price, with colours distinguishing different flat types. 
Generally, there is a positive correlation, i.e. the bigger the floor area, the higher the resale price. The dashed trend line reinforces the overall positive relationship.  

The HDB Resale Flat Data Story: An Overview  
<image>
The HDB Resale flat data from 1990 to 2022 reveals a clear and dramatic long-term growth trend in the average resale price, currently standing at $308K with a National Average Price per Square Foot (PSF) of $295.35. 
The long-term price trend shows sustained upward momentum, illustrated in the national trend line, reflects steady demand amid economic growth, urbanization, and evolving buyer preferences.
The overall increase is driven primarily by factors of size and location, leading to a visible price premium for central areas and higher floors. In terms of market activity, 4-room and 3-room flats dominate the transaction volume, 
indicating they are the most liquid segments of the market.
Analysis of the top-performing towns confirms that geographical location remains a prime value driver, with Punggol and Bukit Timah commanding the highest average resale prices. 
Overall, the data story establishes a strong, positive relationship between flat size and resale price, while the high transaction volume underscores a consistently robust and active market over the analyzed period. 
This overview serves as a summary of the full data story, which can be further explored through the dedicated Trends, Location, and Features dashboards.  

Dashboard 1: Resale Price Trends
This dashboard focuses on price fluctuations over time, seasonal patterns and lease decay effect on resale price.  
<image>
The dashboard display the general resale price trends throughout the years. Users can toggle the slicers to discover seasonality patterns, explore relationships between resale price and floor area and see the effect of lease decay.  

Dashboard 2: Location-Based Analysis
This dashboard focuses on geographical trends, liquidity, and value.
<image>
It consist of heatmap showing which towns are the most expensive in terms of average resale price per sqft, a bar chart showing the towns with highest total number of transactions 
and a filled map showing the areas with percentage of transaction that are below national average.
The slicers of Flat type and Storey range allow users to drill down and see how price and volume change based on specific flat characteristics
This dashboard has all the necessary components for a regular Singaporean property hunter to perform high-quality location analysis.  

Dashboard 3: Flat Features
This dashboard focuses on how physical characteristics of the flat (size, type) correlate with price and change over time.
<image>
This informative dashboard summarizing key HDB flat features like size, height! It consists of three powerful visuals that work well together: floor area trends, storey-range price premium, and price-per-square-foot (PSF) by flat type. 
With the addition of flat type and geographical slicers, it allows interactivity and makes the dashboard more insightful.



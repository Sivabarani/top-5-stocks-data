# Top 5 Stocks Data Visualization
This Python project demonstrates the analysis and visualization of stock market data for the Top 5 stocks over a period of 5 years, from 01-12-2019 to 01-12-2024. The dataset includes the following stocks:
1. Tesla (TSLA)
2. Intel (INTC)
3. Supermicro Inc. (SMCI)
4. NVIDIA (NVDA)
5. Palantir Technologies (PLTR)
It focuses on visualizing the opening prices of these stocks and analyzing their performance over time using interactive charts created with the Plotly library.

**Packages**
1. Pandas: For data manipulation and processing.
2. Plotly Express: For creating interactive visualizations such as line charts, pie charts, sunburst charts, and animated bar charts.
   
**Charts Explanation**
_1. Line and Area Chart_
This chart displays the relationship between the opening prices and years for each stock. I created separate line and area charts for each stock to show how the opening prices have varied over time. These charts help visualize the overall price trend for each stock from 2019 to 2024.
_2. Pie Chart_
A pie chart visualizes the proportion of each stock’s opening price relative to the others. This chart helps highlight the share of each stock's maximum opening price over the past 5 years, making it easy to see which stock had the most significant performance.
_3. Animated Bar Chart_
This animated bar chart dynamically shows how stock opening prices evolve year by year. By playing the animation, we can observe how each stock's opening price compares across different years. It allows for a clearer comparison of the stocks’ performances over time.
_4. Sunburst Chart_
The sunburst chart visualizes the lowest and highest opening prices for each stock across different years. The chart uses a hierarchical structure:
The inner ring represents the year.
The outer ring represents the stock tickers.
This allows users to explore the highest and lowest opening prices for each stock across the years.

Maximum and Minimum Opening Prices
The Maximum Opening Prices chart shows the highest opening prices for each stock over the past 5 years.
The Minimum Opening Prices chart displays the lowest opening prices during the same period.
Using the sunburst diagram, you can select a particular year and analyze the maximum and minimum opening values of each stock.

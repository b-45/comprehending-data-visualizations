## Making sense of Data Visualization

There are a lot of different charts in the data visualization lexicon and in this post I intend to explore and research when is the right time to use any particular visualization from the most simple to complex.     

#### Tool
These charts were created with *Vega*.  *Vega* is a....You can explore the code that produced these charts [here](https://beta.observablehq.com/d/85a39c2b2101ee95) 
  

#### Dataset
The dataset that produces these charts is sample dataset that comes with downloads of Tableau. It includes data points on isntances of sales with the following fields:
- Order: "CA-2013-152156",
- Order Date: "11/9/13",
- Ship Date: "11/12/13",
- Ship Mode: "Second Class",
- Customer ID: "CG-12520",
- Customer Name: "Claire Gute",
- Segment: "Consumer",
- Country: "United States",
- City: "Henderson",
- State: "Kentucky",
- Postal Code: 42420,
- Region: "South",
- Product ID: "FUR-BO-10001798",
- Category: "Furniture",
- Sub-Category: "Bookcases",
- Product Name: "Bush Somerset Collection Bookcase",
- Sales: 261.96,
- Quantity: 2,
- Discount: 0,
- Profit: 41.9136

*Lets get into it!*
***

### Bar Chart
Bar charts can be very useful on different occcasion. Below are a few occasions you may wnat to use a bar chart.

1. Ranking - Rankings are very useful where visualizing instances where ordering of elements are important. Lets rank sum of sales per state.

![Sales Per State](https://github.com/b-45/comprehending-data-visualizations/blob/master/charts/sales-per-state.png)
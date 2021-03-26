__[Note]__ Please use NB viewer for plotly graphs visualization rendered in code. Here is the link:
https://nbviewer.jupyter.org/ <br>
Copy and paste notebook url in the search engine.

## Retail Data - Exploratory Data Analysis
***
#### Problem Statement:
As a business manager, finding out weak areas where you can work to make more profit<br>
What other business problems that can be formulated with this data

### Data cleaning and pre-processing:
* Data type reset, dealing with null values, dropping duplicate rows
* Addition of columns with latitude and longitude for map rendering
* Addition of column on gross profit margin:

__Gross Profit Margin:__
The gross margin is a financial ratio metric, which helps assess the profitability of a business and also its operational efficiency.
It is the relationship between Gross Profit and sales, and it is expressed in percentage:
(𝐺𝑟𝑜𝑠𝑠 𝑃𝑟𝑜𝑓𝑖𝑡÷𝑆𝑎𝑙𝑒𝑠)𝑥100

### A. Initial Observation:
***
#### Categorical Data Analysis
* Shipping Mode: Most preferred choice of shipping mode is standard class while very few have opted for same day delivery.<br>
* Customer Segment: Majority of customers are individual consumers.<br>
* Product Categories: The data provides info on sales for three main categories of products of which office supplies have been sold most, next comes furniture and then technology products.<br>
* Location: The customers belong to four regins of US of which west contributes most and south region contributes the least.<br>
* Among US states, majority of customers belong to California, New York, Texas while the store has least customer base in Wyoming, West Virginia, North Dakota etc.<br>

#### Numerical Data Analysis
* The data is about 9977 customers'transactions of which the time frame for data collection is not provided.<br>
* The store has sold total of 37,820 units of products for total sales of USD 2,296,195.6 and profit of USD 286,241.42.<br>
* On an average a customer has purchased 3.79 units ranging from minimum of 1 unit to maximum of 14 units.<br>
* The store has made an average sales of USD 230.14 per customer with minimum sales of USD 0.44 and maximum sales of USD 22,638.48.<br>
* The store has made maximum profit of USD 8,400 and experienced maximum loss of USD 6,600 to a customer with average profit of USD 28.69 per customer.<br>
* Average of 15% discount with maximum 80% discount.<br>

### B. Overall profit insights:
***
* Gross profit margin seem to be decreasing with increment in discount on products.
* Beyond 40% discount, the store has experienced loss only.
* Store has been able to make higher profit, with less than 20% discount, majority being without any discount.

### C. Location Insights:
***
* The majority of sales for the store is observed in states of California, New York, Texas, Washington , Pennsylvania and so on.
* States like Texas, Pennsylvania, Florida, Ohio have experienced loss despite the higher sales.
* Gross profit margin is lowest in central region.
* The data shows higher discount might have increased sales but at the cost of profit. The locations with discount more than 30% are incurring only loss.

![alt text](https://github.com/sayaliba01/TSF-Projects/blob/main/1.%20EDA-Retail%20Data/pareto-states.png)
### D. Product Category Insights
***
* Technology product sales and profit are highest while furniture has made lowest profit.
* Tables, bookcases and supplies are incurring loss in sales.
* Products when sold with higher discounts, more than 40%, have incurred loss only.
* Storage, accessories and supplies have shown profit without discount than with 20% discount.
* Supermarket is making good profit from products when sold without discount.
* The quantities sold are not increasing with increasing discount.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
* The majority of sales come from phones (technology), chairs (furniture), and storage products (office supplies) followed by tables, binders and machines.
* The highest demand is seen for binders, paper, furnishings, phones, storage and so on.
* Fasteners, machines, copiers, tables, supplies, bookcases are in less demand. With the exception of copiers all other products are being sold with lowest gross margin.
* The highest gross profit making product is copiers, next to which comes binders.

## Observations:
***
<t>The retail data for a superstore provides data for 9977 transactions across USA for selective product categories of technology, furniture and office supplies. As per the data, the store has sold 37,820 units of product items with revenue of USD 2,296,195.6 and gross profit of USD 286,241.42. For USD 230.14 sales per transaction, the store has gained profit of USD 28.69 per transaction. Majority of revenue comes from technology products. Binders and paper are having highest demand while phones, chairs are having highest sale. Highest profit comes from copiers.

<t>When the products and locations are analysed for profit, it is observed that the transactions have incurred loss when discounts of more than 40% have been applied on products. The gross profit margin is negatively correlated with the discount. States like Texas, Pennsylvaia, Florids despite having higher sales are bringing loss to the store.

<t>Overall, products like tables, bookcases and supplies are not making profit in total and have been sold with higher discounts. With increasing discount, the quantities sold for a product item are not more, rather seem to be less in most cases. The store has performed well when no discount or less than 20% discount is applied. The store might benefit by reducing discount on loss making product items.

<t>Additionally, marketing and advertisement in regions with less customer base might help to increase the store presence, thereby increased sales.

## Conclusion and future directions:
***
<t>The store might benefit by targetting states with higher sales (top 80%) like California, New York, Texas etc. Considering the strong negative correlation between discount and gross profit margin, store can make strategies to reduce loss from product categories like 'Binders', 'Tables', 'Machines', 'Bookcases', and 'Chairs' by adjusting discount level, preferably reducing discount offered.

<t>Further business questions can be asked with this data, but are out of scope for current analysis:
For example:
1. Is there significant change in profit pattern across product categories among groups of three customer segment?
2. Is quantity ordered per transaction for each customer segment and also for each shipping mode significantly different?

### Limitations:
1. It is a cross-sectional data. The effects of external time-dependent factors like seasonal changes, holidays etc are ignored.
2. The analysis shows the probable negative correlation between profit and discount and does not provide cause-effect analysis.
***
### Acknowledgement:
I would like to thank The Sparks Foundation community, my peers and mentors for support and guidance.

### References:
1. Book: 'Retail Analytics: The revolution in consumer market.',Paul Odame and Gloria Jubi
2. You-Tube Channel: 'Charming Data' by Adam. https://www.youtube.com/channel/UCqBFsuAz41sqWcFjZkqmJqQ

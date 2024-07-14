# Financial-Performance-Dashboard-Power-BI
Financial Performance Dashboard - Power BI

Step 1: Import financial data such as revenue, expenses, and profit from your accounting system or Excel spreadsheet.
Step 2: Clean and format the data for analysis.
Step 3: Develop visualizations to analyze key financial metrics such as profit margins, cash flow, and return on investment.
Step 4: Include trend analysis visualizations (e.g., line charts, waterfall charts) to track financial performance over time.
Step 5: Add slicers for filtering data by financial period, business unit, and expense category.

Dataset: https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download

Dashboard: https://github.com/KrutikaRajpure/Financial-Performance-Dashboard-Power-BI/blob/main/Financial%20Dashboard.pbix
## Page 1
<img width="596" alt="image" src="https://github.com/user-attachments/assets/3e40bc8b-e53a-4cbb-ba45-107824f43c24">

## Page 2
<img width="599" alt="image" src="https://github.com/user-attachments/assets/df1d3146-bb22-4159-a159-5e8236acc027">

## Tooltips
<img width="314" alt="image" src="https://github.com/user-attachments/assets/7436447c-7f92-4414-be3f-09e7d690aacb">
<img width="194" alt="image" src="https://github.com/user-attachments/assets/32218122-14a7-4d78-bf3a-3f288d628a8d">


## Explanation: 
My is Financial Performance Dashboard 

The data i got from microsoft power bi website 
It is a sample financial data
Kings Manufacturing Company Dataset
is a winery manufacturing firm with 6 brands of wine product
and has 5 organizational units located across 5 countries.

My data initially had 16 columns and 700 rows and each row which indicates number of transactions 
It has data from Sept 2013 and for all months of 2014.

Columns:
1. Segment are the sales occurred (5)
 channel partners, Enterprise,
Government, Midmarket, Small Business 

2. Country where sale made
Canada, France, Germany, Mexico, USA

3.Product sold
Amarilla, Carretera
Montana, Paseo, Velo, VTT

4. Discount Band: category applied 
 High, Low, Medium, None

5. Units Sold: 

6: Manufacturing Price: Cost to manufacture one unit of the product

7. Sale Price: Selling price per unit

8. Gross Sales: Total Revenue from sale before discount

9. Discount: discount amount applied

10. Sales: Net sale amount after discount

11. COGS: (Cost of goods sold) sum of the direct cost of making a product

12. Profit: Net Profit is after all expenses deducted from total revenue

13. Date: when sale occurred

14. Month Number, Month Name, Year

17. Gross Profit: Profit after deducting the cogs 

19. Manufacturing Expense: total costs calculated produced to the unit sold

---------------------
---------------------
### Measures 

Profit Margin:
profitability expressed as a percentage, indicating 
how much profit a company makes for each dollar of sales 


----------------------
----------------------
On  the dashboard left hand side I have all the sliders 
1. is year as i have data for 2013 and 2014
2. Quarter 
3. Country
3. Month Name
4. Product

I have a gauge chart 
Which shows the total number of units sold
and the target units to be sold 

as i didn't have target units sold I have calculated it manually 
by the formula Total Units Sold+1.2 M 

On the top I have all the cards 
Revenue and profit are key indicators of a company’s financial health.
So i have the Revenue 118.73 M for both the years. 
That is the total amount received from selling products before expense are taken out.

net profit 16.89M is basically the total earning after subtracting all expenses 

Total Discount : 9.21 M total amount of discount applied

Total Cost of goods sold : 101.83 M 
it is the total cost a business pays to cell a product . 
like raw materials, packaging, labor, storage, making charges, and others
 ------------------------------------------------------------------------
**Monthly revenue Analysis**
I have a area chart where the month name on x axis and 
total revenue and cogs on y axis.

We can do a comparative analysis for total revenue and cogs 
area under the red line represents total revenue for each month 
and area under the blue line represents the total cogs

The space bth the two lines represents the gross profit. Wider the gap higher the profit. 
As we can see the profit from sept to dec profit is increased 

**Profit by Product** 

I have used a column chart and 
the bars indicates the profit level for each product
we can see that paseo has the highest profit 4.6 Million 
followed by VTT 3 Million, Amarilla 2.8 M 
, Vello 2.3 M , Montana 2.1 M and carretera 1.8 M.

I have also added tooltip 
So by hovering over a product, the tooltip shows a pie chart that breaks down the profit by segment for each product 
 
like we can see for paseo has the highest profit and th major profit comes from government segment and so on. 
 

**Operating Expense Breakdown**
I have line and column chart 
x axis represents time y axis represents manufacturing expenses
and line y axis represents units sold 

The column represents the fluctuate of expenses over time 
and the line shows the trend of units sold 
 and the we ca see that if the expenses increase then unit sold also rises, it shows higher production and sales

We can also analysis if there is over expenses and low sales that is inefficiencies

**Year Financial Summary**
Here is a matrix for Yearly financial summary for 2013,2014
We can also drill down to qtr for more detail level
We have sale , Net profit and Profit Margin:

Net sale amount after discount
Net Profit is after all expenses deducted from total revenue
Profit margin: profitability expressed as a percentage, indicating 
how much profit a company makes for each dollar of sales 

**Sales and Discount trend Over Time**
I have a line chart were on x axis is the months and sales and discount on y axis 

This chart help in understanding the effect of discount on sales over time 
in most of the month we can see that both sales and discounts are high which tells us that higher discount led to increase sales.
but in months like april and june we can see that the discount are higher but the sales have dropped down.

**Sales by Country**
 I have a tree map showing the sales for each country area of rectangle represents the sales 
 We can see that there is no major difference in sales for USA, France, Canada, Germany .
 Mexico has the lowest sales 
 
When hovering over a country tooltip shows matrix of year, profit generated in the country and units sold in the country.
By this matrix we can also see that sales for USA is greater than France but the profit and units sold are lower that it.

**Revenue breakdown by discount Band**
I have a stacked bar chart 
where x axis has total revenue, y axis product and legends  discount band

which shows the distribution of revenue for different products 
segmented by discount bands

by the different colors we ca see how much revenue is generated with and without discount
We can also see how discount strategies work 
We can clearly see that if there is no discount the revenue drops 

**YTD Units Sold Product**
Year to date total number of units sold for each product  

**Financial Performance by Segment and Product**
here is a matrix showing total revenue, 
total expenses, total gross profit, total net profit by product
 
we can also drill down in detail to segment wise for each product 


 


# Supply Chain Dashboard / Power BI
## Introduction
**Company Overview:** Aura Logistics & Cosmetics Co. is a company that operates within three main product categories : Haircare, Cosmetics, and Skincare. It runs a sophisticated **supply chain** based on international suppliers, shipping service providers, and different modes of transport including air, rail, road, and sea.

**The Problem:** The data was scattered into one single flat file (supply_chain_data.csv) and thus **limited visibility** for the executives. The corporation was faced with slim profit margins, inventory imbalances, and inconsistency in quality but without knowing the reasons behind them.

**The Aim:** The objective of the project was to consume raw operational data from the company, engineer **key performance indicators**, and create an interactive 3-page Business Intelligence report using **Power BI**.
<img width="1405" height="792" alt="Overview" src="https://github.com/user-attachments/assets/1308f0fb-c079-4e86-b537-5afc79f33555" />

[View intercative dashboard here on the Power BI Service](https://app.powerbi.com/view?r=eyJrIjoiYTE4NmY4MjYtY2VmOC00YTE2LWJlYjgtZTA4ZGU0M2FlZmJmIiwidCI6IjFlNzI1ZjFjLWFjMjUtNDhmMy04MWJiLWE4YjkzNWVhNWUwMyIsImMiOjh9)
## Skills Showcased
In this project, combining both **technical knowledge** and **domain knowledge** was the key to build the report:

**Data Engineering & ETL:** Loading files, changing data types, and cleansing text with Power Query.

**Business Intelligence (DAX):** Developing business rules that help derive actual profit numbers down to Stock Keeping Units (SKUs).

**Dashboard Structure:** functional layouts with clear design, navigation bars and conditional formatting.
**Operations & Analytics:** Combining individual metrics (such as: lead time to inventory level) to identifie bottlenecks.

## Dashboard Overview
### Executive Overview Page
**Focus:** Overall insights into the main key performance indicators of the company's supply chain.

**Core Metrics:** Total Revenue, Total Products Sold, Total Costs, Average Profit Margin, and Current Stock Levels using unified cards.

**Visual Elements:**  A revenue breakdown by Customer Demographics (Male, Female, Unknown) and Product Types via donut charts, alongside a column chart tracking distribution across individual Shipping Carriers and a horizontal ranking of the Top 5 SKUs by Revenue.

<img width="1405" height="792" alt="Overview" src="https://github.com/user-attachments/assets/7ba4dfab-ea05-46f2-b1bd-9e1b7a0d3490" />

### Product Insights Page
**Focus:** Inventory management and demand-supply alignment.

**Core Metrics:** Order quantities, storage capacities, and manufacturing timelines.

**Visual Elements:** Features paired column charts comparing current Stock Levels directly against Order Quantities across all 100 SKUs. Includes a clustered column chart contrasting supplier delivery lead times against internal Manufacturing Lead Times, and a scatter plot exploring price elasticity (Price vs. Total Products Sold) categorized by product type.

<img width="1407" height="795" alt="Product" src="https://github.com/user-attachments/assets/419124f0-f986-4683-b893-9623124463ef" />

### Supplier Analytics Page
**Focus:** Quality assurance, risk management, and logistics expenditure.

**Core Metrics:** Dissects vendor performance, defect frequencies, and freight cost allocation.

**Visual Elements:** Features a stacked bar chart breaking down cost compositions (Normal Cost, Manufacturing Cost, Shipping Cost) per supplier. Includes donut charts analyzing total cost distributions and average defect rates across different Transportation Modes. Concludes with an analytical scatter plot correlating supplier Defect Rates directly against net Profit Margins.

<img width="1412" height="801" alt="Supplier" src="https://github.com/user-attachments/assets/36e580c7-02c4-464e-a707-37dfade18c51" />

## Connecting the Dots: Identifying the Problems
By observing the data across the three pages, three critical supply chain problems were identified:

**In the Queue Time  Stock Issue:** we see that some of our highest revenue SKUs have very long manufacturing lead times which at the same time have very low stock levels. This puts the company at risk of stock outs and lost customer sales. 

**Transportation Waste:** We see that air freight makes up a large part of our total spend in logistics. Also we note that in the case of air transport we do not see a great reduction in product defects as we do with the more economic options of road or rail which in turn is causing our margins to drop. 

**High Defect Issues with Vendors:** We see that which suppliers we are working with have average defect rates which are very high above what we accept as the base line. These high defect rates in turn produce hidden costs which we see at the manufacturing stage and which in large part eat into our net profits.

## Action Plan: Supply Chain Optimization
To address these operational issues and improve the company’s supply chain, we have put the following three phase action plan:

**Short-Term (Immediate):** We will set dynamic safety stock levels for our top 5 revenue generating SKUs. Also we will review reorder points for products which have internal manufacturing lead times that surpass standard supplier delivery times and we will adjust as required to ensure continuous fill rate.

**Medium-Term (3–6 Months):** we will see a shift in Freight Mode which is a gradual process.We will be moving out of air freight which is used for non-urgent large volume SKU’s into more economic modes of transport like Road and Rail. Also we will be going back to the drawing board with our shipping contracts to put in place performance based freight rates.

**Long-Term (6+ Months):**for Supplier Quality Assurance (QA) we will put in place a strict vendor score card program. We will put into action a corrective improvement plan or will phase out suppliers that continuously exceed the max defect threshold in in favor of better quality, higher margin options.

## Conclusion
This project has shown how the conversion of raw operational data into **business intelligence data** can help reveal **supply chain** weaknesses. We prepared the supply_chain_data.csv file with Power Query and put together a very clean 3 page Power BI report. In the process we went beyond just data collection to business analysis which in turn we put toward the implementation of the put forth optimization strategy which will see the company **plug profit leaks** and **avoid loss**. 

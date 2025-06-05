# Blinkit-Analysis-Dashboard
## Business Requirement
To conduct a comprehensive analysis of blinkit's sales performance, customer satisfaction, and inventory distributaion to identify key insights and opportunaties for using various KPI's and visualization in power BI.  
### KPI's Requirement  
**1. Total Sales:** The overall revenue generated from all items sold.  
**2. Average Sales:** The average revenue per sale.  
**3. Number of items:** The total count of different items sold.  
**4. Average Rating:** The average customer rating for items sold.  

### Chart's Requirement  
#### 1. Total Sales by Fat Content:  
      Objective: Analyze the impact of fat content on total sales.  
      Additional KPI Metrices: Assess how others KPIs(Average Sales, Number of Items, Average Rating) very with fat content.  
      Chart Type: Dounut Chart.  

#### 2. Total Sales by Item Type:  
      Objective: Identify the performance of different item types in terms of total sales.  
      Additional KPI Metrices: Assess how others KPIs(Average Sales, Number of Items, Average Rating) very with fat content.  
      Chart Type: Bar Chart.
      
#### 3. Fat Contant by Outlet for Total Sales:  
      Objective: Compare total sales across different outlets segmented by fat content.  
      Additional KPI Metrices: Assess how other KPIs(Average Sales, Number of Items, Average Rating) very with fat content.  
      Chart Type: Stacked Column Chart.

#### 4. Total Sales by Outlet Establishment:  
      Objective: Evaluate how the age or type of outlet establishment influences total sales.
      Chart Type: Line Chart.

#### 5. Sales by Outlet Size:  
      Objective: Analyze the correlation between outlet size and total sales.
      Chart Type: Donut/pie Chart.  

#### 6. Sales by Outlet Location:
      Objective: Assess the geographic of sales across different locations.
      Chart Type: Funnel Map.

#### 6. All Metrices by Outlet Type:  
      Objective: Provide a comprehensive view of all key metrics(Total Sales, Average Sales, Number of items, Average Rating) broken down by different outlet types.
      Chart Type: Matrix Card.


## Steps In Project
1. Requirement Gathering / Business Requirements
2. Data Walkthrough
3. Data Connection
4. Data Cleaning / Quality Check
5. Data Modeling
6. Data Processing
7. DAX Calculations
8. Dashboard Lay outing
9. Charts Development and Formatting
10. Dashboard / Report Development
11. Insights Generation

Show what the dashboard looks like:- ![Alt text](https://github.com/Rishavsagar/Blankit-Analysis-Dashboard/blob/main/dashboard.png)
      
This dashboard provides a comprehensive view of Blinkit's retail performance, segmented by item type, outlet location, size, fat content, and store type. Below are the key insights derived from the visual elements:      
      
📊 KPI Summary            
| Metric                  | Value   |
| ----------------------- | ------- |
| **Total Sales**         | ₹ 1.20M |
| **Avg. Sales per Item** | ₹ 141   |
| **No. of Items Sold**   | 8,523   |
| **Average Rating**      | 3.9 / 5 |

➡️ Interpretation:

      -> The average item performs reasonably well (₹141 per item) in a high-volume environment.
      -> A 3.9 rating suggests moderate to high customer satisfaction.      

🧪 Fat Content Contribution

Regular Fat items dominate with ₹ 776.32K in sales.      
Low Fat items contribute ₹ 425.36K.
      
➡️ Insight:      
      
      -> Although healthier (low-fat) items have a significant share (~35%), regular-fat products still drive the bulk of revenue.      
      
🍱 Sales by Item Type      
      
Top-selling categories:      

* Fruits & Vegetables: ₹ 0.18M      
* Snacks: ₹ 0.18M      
* Household: ₹ 0.14M
      
Low performers:            
* Seafood, Breakfast, Starchy Foods: < ₹ 0.03M each
      
➡️ Insight:      
      
      ->Focus on expanding high-performing categories and optimizing/retiring underperforming SKUs.      

📍 Sales by Outlet Location Type      
| Tier   | Sales     | % Contribution |
| ------ | --------- | -------------- |
| Tier 3 | ₹ 472.13K | Highest        |
| Tier 2 | ₹ 393.15K | Medium         |
| Tier 1 | ₹ 336.40K | Lowest         |

➡️ Insight:      
      
      ->Contrary to common expectations, Tier 3 cities outperform Tier 1 in total sales, indicating strong rural demand.

🏪 Outlet Type Breakdown      
| Outlet Type     | Sales     | Items | Avg Sales | Rating | Visibility |
| --------------- | --------- | ----- | --------- | ------ | ---------- |
| Darkstore Type1 | ₹ 787.55K | 5577  | ₹ 141     | 3.9    | 0.06       |
| Darkstore Type2 | ₹ 131.48K | 928   | ₹ 142     | 3.9    | 0.06       |
| Grocery Store   | ₹ 151.94K | 1083  | ₹ 140     | 3.9    | 0.10       |
| Darkstore Type3 | ₹ 130.71K | 935   | ₹ 140     | 3.9    | 0.06       |

➡️ Insight:      

     -> Darkstore Type1 contributes the majority of sales and item count.
     -> Grocery stores have higher item visibility (0.10), suggesting potential for improving discoverability in dark stores.

🕰️ Outlet Establishment Trend (2012–2022)      
      
* Sales peaked in 2018 (₹ 205K).      
* Initial growth was steady from 2012–2016, followed by a sharp spike and drop.
         
➡️ Insight:      
      
      ->2018 appears to be a pivotal growth year, possibly due to expansion or marketing. Sales normalized post-2020, likely impacted by external factors (e.g., COVID-19).

🧩 Sales by Outlet Size      
      
* High-sized outlets: ₹ 507.90K      
* Medium-sized outlets: ₹ 248.99K      
      
➡️ Insight:      
      
      ->Larger outlets drive more sales, indicating economies of scale or better inventory capacity.

✅ Recommendations      

1. Increase promotion of low-fat products in Tier 3 cities.      
2. Investigate why smaller outlet types (like Type3) have comparable performance to bigger ones.      
3. Improve item visibility across all dark store types to enhance product discoverability.      
4. Explore growth levers from 2018 to replicate for future campaigns.      
5. Consider phasing out or revamping low-performing categories (e.g., seafood, breakfast items).      







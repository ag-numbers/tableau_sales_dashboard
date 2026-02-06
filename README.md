# sql_tableau_sales_dashboard


## 🎯 Goal and Summary
**Goal:** A project aimed at showcasing data cleaning skills in SQL and visualizing and analyzing sales data for a furniture e-commerce store.

**Summary:** Sales went up because of discounts, but profits went down.
The data showed that most sales came from the Bedroom and Desk categories, making the business too dependent on them. 


**Analysis and recommendations to the business**
- Sales grew from April to June, then slightly declined in summer. --> Check what caused lower sales- low traffic, stock issues, technical bug or price competitiveness. Act accordingly.
- Quantity sold rose in August while AOV dropped suggesting lower-priced purchases. --> Implement upsell/cross sell strategy before the user checks out.
- Discounts (~18%) increased over time, showing they strongly drive sales.--> Revise the strategy of discounts to keep value of products as the main driver for sales.
- Desk and Bedroom categories generate 60%+ of sales, creating dependency risk. --> The business should promote other categoes to mitigate the risk. At the same time secure enough stock for bestselling products in tgese categories.

## 🧹 Data Cleaning & Preparation in SQL
- Cleaned and joined orders and events tables in **PostgreSQL**.
- Handled nulls, removed duplicates
- Standardized date/time formats
- Set up correct data types
- Checked and identified unique keys
- Did data profiling to exclude ouliers, negative values.
- Filled in data where lossibke for missing data 
- Created derived calculated metrics like discount %, AOV, and session duration

## 🧰 Tools Used
- **SQL (PostgreSQL)** — for cleaning and transformation  
- **Tableau** — for visualization and storytelling  
- **Excel / CSV** — for initial data structure  

## 📁 Files
- Interactive dashboard on Tableau Public https://public.tableau.com/views/Sales_orders_Project2_Alina/Story1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 

<img width="971" height="678" alt="Screenshot 2025-11-19 at 11 58 21" src="https://github.com/user-attachments/assets/7818d231-58e7-4ce7-a485-a4275c26aff6" />

<img width="975" height="679" alt="Screenshot 2025-11-04 at 15 54 05" src="https://github.com/user-attachments/assets/82dcc8c0-541b-498b-8217-9c413e6cc7cb" />

## ⚠️ Disclaimer
The dataset is **synthetic** and used for educational purposes only.

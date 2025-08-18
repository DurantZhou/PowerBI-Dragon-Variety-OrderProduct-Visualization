# PowerBI-Dragon-Variety-OrderProduct-Visualization
## 1. Project Overview
This dashboard aims to help sales reps better tracking the order history and preference of variable customers. With the dataset they can easily make
sales with the historic records without missing any products since our products range from kithenwares, partywares, homewares, toys, stationaries, personal care to travelling products. 
It also provides the customer information and ordering ranges to sales reps so they can try to hit the target sales baseline according to sales records. Besides, the dashboard demonstrates personnel sales data including amount, order status in different period.
They can check their sales situations at any time without opening the ordering system(Inflow), which is more convenient and effecient.

## 2. Data Model
<img width="1872" height="1011" alt="image" src="https://github.com/user-attachments/assets/5e0d7bb1-cd34-4556-b15b-ab492cb9bc82" />


### 1. SalesOrder Table
Fields: OrderNumber, OrderDate, OrderAmount, ProductSKU, ProductName, SalesPerson, Customer, etc.
### 2. Customer Table
Fields: CustomerID, CustomerName, City, Location, Contact, Address,etc.
### 3. Product Table
Fields: ProductSKU, ProductName, Category, Product_Price, Product_Cost, RetailPrice, etc.
### 4. ProductImage Table
Fields: ProductName, Photo
### 5. SalesOrder Amount
Fields: OrderNumber, OrderDate, PaymentStatus, SalesPerson, AmountPaid, OrderTotal
Used to calculate OrderTotal and AmountPaid

## Tools and Technology
#### Inflow (An inventory management system)
#### Excel- Extract and Clean data
#### PowerBI- Data modelling, Data Transformation, Data Visualization, Slicer, etc
#### AWS-RDS(In Progress), Sync Inflow data to the AWS Server
#### Dragon Variety Website- For publishing PowerBI dashboard, so users can access the dashboard by account and password

## Key Insights
** From the overview dashboard, total sales have experienced a graduate increase from 2013 to 2025.8. From 2022, the increasing efficiency has accelarated a lot compared with the past 10 years.  

** Total number of orders and product quantity have similar trends like total sales. However, the slope of total number of orders is more steep from 2013 to 2017, illustrating a faster increasing speed,
following by a slight decrease, and then climbed to the peak in 2024.  

** There is no big difference among the overall sales in 12 months. However, different years demonstrate a more apparent difference in each month's sales.  

** Customers from MCQ supermarkets and Oriental Groceries contributed most to total sales, accounting for around 40% of total sales, followed by the contribution of NP Supermarkets and Supermarket,
which both accounted for 14%.  

** The donut chart shows that Kitchenware accounts for the largest share of total sales (about 19.7%), followed by Homeware (~15.2%) and Party Use items (~14.1%), whereas Toys represent the smallest slice at roughly 4.5%.  

** Beyond the high-level Overview tab, this Power BI report acts as a full-funnel sales cockpit. Interactive filters (time, customer, category, industry, SKU) let reps slice the data in seconds, compare year-over-year performance, and spot emerging trends. Dedicated pages surface:

Product Image – pairs SKUs with photos so no item is overlooked when pitching or replenishing stock.

Customer Info – merges order value with contact details, making follow-ups and cross-selling effortless.

Sales Data – highlights order totals, fulfillment status, and payment progress, helping teams chase revenue gaps before they widen.

Popular Products – ranks best-sellers by quantity sold, flagging items that drive share-of-wallet and exposing white-space opportunities.

Together these views safeguard against missed products, pinpoint under-served niches, and quantify each customer’s contribution—ultimately boosting market share and empowering the sales team to make faster, data-backed decisions.

## Dashboard
### OrderProduct Visualization
<img width="1620" height="903" alt="image" src="https://github.com/user-attachments/assets/9b412e2b-6aa0-4d13-97bc-72bfcc2980b5" />
### Customer Info Visualization
<img width="1596" height="894" alt="image" src="https://github.com/user-attachments/assets/f33ca119-db03-4c1b-96f5-5609aad5ab89" />
### SalesData Visualization
<img width="1584" height="900" alt="image" src="https://github.com/user-attachments/assets/b77d3d22-1818-4c1c-874e-cdd275def46e" />
### Popular Products Calculation
<img width="1397" height="844" alt="image" src="https://github.com/user-attachments/assets/1dda24e3-0283-4583-a530-24e2d5185f93" />
### Overview of Sales
<img width="1365" height="801" alt="wechat_2025-08-15_235352_485" src="https://github.com/user-attachments/assets/78730d2c-f289-4f21-8eb7-a1e38a1b4891" />





## Conclusion
The dashboard delivers both a high-level Overview and drill-down detail, giving the sales team a complete, field-ready command center. The Overview tab surfaces headline KPIs—total sales, order volume, product mix, and top customers—so reps can grasp overall performance at a glance. From there, they can dive into dedicated pages to:

** Locate any customer instantly, filter by order number or category, and review the full purchase history in seconds.

** Spot best-selling products in real time, ensuring high-demand items are always part of the conversation.

** Tailor recommendations on the spot, backed by concrete data rather than intuition.

By turning raw order data into clear, actionable insights, the report helps sales professionals engage customers confidently, avoid missed opportunities, and ultimately expand revenue and market share.

## Contact me
Developed by Yulin Zhou
Feel free to email me: durantzhou0803@gmail.com
or reach out to me via Linkedin: https://www.linkedin.com/in/yulin-zhou-700003ba/
If you want to access the file, can contact me by email or linkedin.

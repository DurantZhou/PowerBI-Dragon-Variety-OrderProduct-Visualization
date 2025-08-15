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

## Dashboard
### OrderProduct Visualization
<img width="1620" height="903" alt="image" src="https://github.com/user-attachments/assets/9b412e2b-6aa0-4d13-97bc-72bfcc2980b5" />
### CustomerInfo Visualization
<img width="1596" height="894" alt="image" src="https://github.com/user-attachments/assets/f33ca119-db03-4c1b-96f5-5609aad5ab89" />
### SalesData Visualization
<img width="1584" height="900" alt="image" src="https://github.com/user-attachments/assets/b77d3d22-1818-4c1c-874e-cdd275def46e" />
### Popular Products Calculation
<img width="1397" height="844" alt="image" src="https://github.com/user-attachments/assets/1dda24e3-0283-4583-a530-24e2d5185f93" />
### Overview of Sales
<img width="1365" height="801" alt="wechat_2025-08-15_235352_485" src="https://github.com/user-attachments/assets/78730d2c-f289-4f21-8eb7-a1e38a1b4891" />





## Conclusion
The dashboard focuses on the quantitative analysis of orderproducts, aiming to help sales team serving customers professionally. When sales/users are on the field, they can search the customer, and choose orders or categories to 
view products history. In addition, they can identify the most popular products so they can introduce properly to their customers. 

## Contact me
Developed by Yulin Zhou
Feel free to email me: durantzhou0803@gmail.com
or reach out to me via Linkedin: https://www.linkedin.com/in/yulin-zhou-700003ba/
If you want to access the file, can contact me by email or linkedin.

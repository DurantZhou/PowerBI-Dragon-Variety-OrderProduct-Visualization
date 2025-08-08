# PowerBI-Dragon-Variety-OrderProduct-Visualization
## 1. Project Overview
This dashboard aims to help sales reps better tracking the order history and preference of variable customer. With the dataset they can easily do
sales with the historic records without missing any products since our products range from kithenwares, partywares, homewares, toys, stationaries, personal care to travelling products. 
It also provides the customer information to help sales reps access the info directly. Besides, the dashboard demonstrates personnel sales data including amount, order status in different period.

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
#### 5. SalesOrder Amount
Fields: OrderNumber, OrderDate, PaymentStatus, SalesPerson, AmountPaid, OrderTotal
Used to calculate OrderTotal and AmountPaid

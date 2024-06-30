
1. Menu_items: 
The system allows management of the restaurant's menu items, including their names, 
description, categories, prices, and availability status. 
Also adding item_id to identify unique menu items, allowing for easy tracking of individual 
dishes, their descriptions, prices, and availability. 
2. Orders: 
Table to track customer orders, including order ID, items ID, quantity, total price, customer 
ID and status (example- pending, completed). order_id is used for each customer order, 
enabling efficient order management, tracking, and retrieval of order-related information 
such as items purchased, quantity, total price, and status. 
3. Customers: 
Table to manage the details of customers like there Id, name, email, phone-number. 
 
4. Reservations: 
Table to manage restaurant reservations, including reservation ID, customer name, party size, 
reservation date/time, and status. 
5. Customer Feedback: 
Table to collect feedback from customers, including feedback ID, customer name, ratings, 
comments, and order_ID. 
order_id is used to display the dish id or names which they ordered and giving the ratings on 
that item. 
6. Staff Management: 
Tables for staff information, including staff ID, name, position, contact information, and 
access credentials.
7. Inventory: 
Table to track inventory levels of ingredients and supplies used in the restaurant, including 
item ID, name, quantity on hand, unit of measurement, and reorder threshold.

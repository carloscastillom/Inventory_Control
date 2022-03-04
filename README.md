# SQL Queries - SAP Business One
Using SAP business as our ERP I have implemented the following SQL queries which are functional for Operations and Sales control. I will explain what every every uploaded query does and why is it useful 

## Inventory

- [Inventory_Control](https://github.com/carloscastillom/SQL-Queries-SAP-Business-One/blob/main/Inventory_Control.sql)
The SQL query keeps track of critical items for our company. Critical is defined as items with a defined minimun level quantity(MLQ) by management. It prints the current stock of the items that have a minimun level quantity(MLQ), for an specific warehouse. It Helps to have an overview of the items Based on the current status of them. When the inventory of the stock is lower that the MLQ, is required to order that specific item. The amount to order is evaluated based on the forecas 

- [Inventory_Service_Engineers](https://github.com/carloscastillom/SQL-Queries-SAP-Business-One/blob/main/Inventory_Service_Engineers.sql)
Service engineers are employees that face the customer and commission our equiment on plant or remote. When they travel, the regularly take with them some items and  the company handles the inventory in our ERP as they were warehouses.  

## Production

### [Open_ProdOrder_Project](https://github.com/carloscastillom/SQL-Queries-SAP-Business-One/blob/main/Open_ProdOrder_Project.sql)
The SQL Query keeps track of the company´s open production orders and the percentage of materials issued. It prints all open production orders throughout the company, with the percentage of material already issued. the percentage of materials issed is calculated as  the amount  of items issued, divided by the total number of items. This is an overview of the work in process for the current week. 


## Procurement

### [Open_Purchase_Order](https://github.com/carloscastillom/SQL-Queries-SAP-Business-One/blob/main/Open_Purchase_Order.sql)
The SQL Query reports the items that the company is waiting on the suppliers to send. It can be used once a week or more frequently depending on the business dynamics. It prints the expected delivery date which helps in controlling the suppliers fulfillment

### [Supplier_Lead_Time](https://github.com/carloscastillom/SQL-Queries-SAP-Business-One/blob/main/Open_ProdOrder_Project.sql)
The SQL Query links tables related to the purchase Order and the delivery time of the items. The information is used to calculate the suppliers lead time and a great tool to control the inventory and adjust the item reorder policy


the SQL shows the current status of the service engineers. This is helpful to keep track of the inventory.

Carlos Castillo



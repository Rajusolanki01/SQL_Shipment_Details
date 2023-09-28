# SQL_Shipment_Details

**   Find details of Shipper(s) who has got Orders:**

     1) Explain the INNER JOIN with the "Orders" table on the "ShipperID" column.
     2) Describe the GROUP BY clause to group the results by shipper details.
     3) Mention the COUNT() function to count the number of orders for each shipper.

     

 **    Find details of Shipper(s) for whom there is no Order:**

     1) Explain the LEFT JOIN with the "Orders" table on the "ShipperID" column.
     2) Use the WHERE clause to filter rows where "Orders.ShipperID" is NULL, indicating no associated orders.


** Find details of Customer(s) whose orders can’t be shipped due to missing shipper details:**

     1) Join the "Customers" table with the "Orders" table on the "CustomerID" column.
     2) Use a LEFT JOIN to join the "Shippers" table on the "ShipperID" column.
     3) Add a WHERE clause to filter rows where "Shippers.ShipperID" is NULL, indicating missing shipper details.
     

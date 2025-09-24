# Supply-Chain-Management-System
🏭 Supply Chain Management System
A relational database project designed to streamline the management of suppliers, products, warehouses, orders, inventory, and shipments. Built using MySQL, this system simulates the real-world operations of a supply chain in a structured, query-driven environment.

📚 Features
Manage Suppliers with contact details
Track Products, unit prices, and associated suppliers
Maintain Inventory across multiple Warehouses
Monitor and query Shipments with status and delivery info
Handle Orders per warehouse with product-level details
Includes 20+ SQL queries for analysis, optimization, and reporting



🛠️ Technologies Used
Database: MySQL
File: project_supply_chain_management_system.sql
🗃️ Database Schema Overview
Suppliers(SupplierID, SupplierName, ContactName, Phone, Email, Address)
Warehouses(WarehouseID, WarehouseName, Location)
Products(ProductID, ProductName, Description, UnitPrice, SupplierID)
Inventory(InventoryID, ProductID, WarehouseID, Quantity)
Shipments(ShipmentID, SupplierID, WarehouseID, ShipmentDate, ArrivalDate, Status)
Orders(OrderID, ProductID, WarehouseID, Quantity, OrderDate, Status)




📦 How to Use
Import the database:

Open your MySQL client (e.g., phpMyAdmin or MySQL Workbench)
Create the database:
CREATE DATABASE Supply_Chain_Management_System;
Import the file: project_supply_chain_management_system.sql


Explore the schema:

Use SHOW TABLES; to see available tables
Run included queries to analyze inventory, orders, and more



🧠 Sample Analytical Queries
Top 5 most ordered products
Inventory value per product (price × quantity)
Delayed shipments beyond expected delivery
Cancelled or pending orders
Warehouses with the most shipment activity
Products that were never ordered
These are pre-written and available at the end of the .sql file under comments.





📝 License
This project is open-source and intended for academic, training, and demonstration purposes. Contributions are welcome!

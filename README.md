# E-WareHouse_System
> A robust web-based solution for digitizing and automating warehouse operations.
 ## 1. Project Statement 
The E-Warehouse System is a web-based solution designed to digitize and automate the core operations of a storage facility. Traditional manual record-keeping often leads to data silos, inventory inaccuracies, and delayed order fulfillment.

This system provides a centralized platform to manage real-time stock levels, supplier interactions, and warehouse movements (Inbound/Outbound). By leveraging the event-driven architecture of ASP.NET Web Forms, the application ensures data integrity and provides a responsive interface for warehouse managers to monitor assets, reduce overhead costs, and optimize the supply chain workflow.

---
## 2. Project Objectives
The objectives are divided into functional and technical goals:

#### Primary Functional Objectives

 **- *Inventory Tracking:***  Implement a robust CRUD (Create, Read, Update, Delete) system to manage products, categories, and stock quantities across multiple bin locations.

**- *Automated Stock Alerts:*** Develop a notification system that flags items falling below a predefined "Minimum Reorder Level."

**- *Supplier & Order Management:*** Create modules to track incoming shipments from suppliers and outgoing orders to customers or retail branches.

**- *User Role Security:*** Establish an authentication layer to distinguish between Admins (full system access) and Staff (view and update stock only).

#### Technical Objectives:

**- *State Persistence:*** Utilize ViewState and Session objects to maintain data consistency across postbacks in the Web Forms lifecycle.

**- *Dynamic Data Binding:*** Use GridView and Repeater controls to render real-time inventory reports directly from a SQL Server database.

**- *Optimized Data Access:*** Implement Stored Procedures in SQL Server to handle high-volume transaction processing for stock movements.

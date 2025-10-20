# SQL_Task_1
E-Commerce Database tables &amp; Relationships

🎯 Objective:-
The objective of this task is to design and create a relational database schema using SQL.
You will learn to:
Create databases and tables using DDL commands
Apply Normalization to avoid redundancy
Design an ER Diagram to represent entities and relationships
Define Primary and Foreign Keys for referential integrity

🏢 Domain: E-commerce System
📋 Entities Identified
Users – stores customer details
Products – stores product details
Orders – stores order information
OrderItems – stores items in each order

🧩 ER Diagram
erDiagram
    USERS ||--o{ ORDERS : places
    ORDERS ||--o{ ORDER_ITEMS : contains
    PRODUCTS ||--o{ ORDER_ITEMS : purchased

🧰 Tools Used
MySQL Workbench 
VS Code (for writing SQL scripts)
GitHub (for project submission)

🧠 Key Concepts Covered
🔹 DDL (Data Definition Language)
Used to define the structure of the database.
Commands used: CREATE DATABASE, CREATE TABLE, ALTER TABLE
🔹 Normalization
The schema is designed in 3rd Normal Form (3NF):
No data redundancy
Every non-key column depends only on the primary key
Separate tables for entities with relationships through foreign keys
🔹 ER Diagram
Visual representation of entities and relationships — shows 1-to-many relationships between:
Users → Orders
Orders → OrderItems
Products → OrderItems
🔹 Primary & Foreign Keys
Ensures unique identification and relationship integrity.

🧾 Outcomes
✅ A well-structured, normalized relational schema

✅ ER Diagram representing entity relationships
✅ SQL script with DDL and sample DML queries
✅ Understanding of database design and normalization principles

🏃‍♂️ How to Run
Open MySQL Workbench (or any SQL tool).
Create a new query tab and paste the SQL script from schema.sql.
Click the Run (⚡) button to execute all queries.
The database and tables will be created successfully.
You can then run the sample INSERT and SELECT queries to test the data.

✍️ Author
Name: Parag Kotkar
Role: MCA Student | Aspiring .NET & SQL Developer
Task: Database Setup and Schema Design
Date: October 2025

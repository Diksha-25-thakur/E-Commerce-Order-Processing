# 🛒 E-Commerce Order Processing System using PL/SQL

A **PL/SQL-based E-Commerce Order Processing System** that automates order creation, billing, and stock management.  
This project demonstrates how **database triggers, procedures, and functions** can be used in Oracle SQL Developer to execute business logic directly inside the database for improved **speed, accuracy, and consistency**.

---

## 🎯 **Objective**
The main objective of this project is to design a **database-driven order management system** that:
- Automates the process of order creation, billing, and inventory management.  
- Utilizes **PL/SQL procedures, functions, and triggers** to ensure data integrity.  
- Enhances business efficiency by executing logic directly at the database level.  

---

## ⚙️ **Tools and Technologies Used**

| Tool / Technology | Purpose |
|--------------------|----------|
| **Oracle Database 19c** | Main database and PL/SQL execution environment |
| **PL/SQL Language** | Business logic implementation (triggers, procedures, functions) |
| **Oracle SQL Developer** | IDE for writing and testing PL/SQL code |
| **Windows 10 / Linux** | Operating system for database execution |
| **Microsoft Word** | Documentation and report writing |

---

## 🧩 **Implementation Overview**

```sql
-- Step 1: Create database schema
@create_tables.sql

-- Step 2: Insert sample data
@insert_data.sql

-- Step 3: Create trigger, procedure, and function
@trg_update_stock.sql
@create_order_proc.sql
@calc_total_func.sql

-- Step 4: Execute and test the system
@test_script.sql

# Ecommerce Database Management System

This project is developed as part of the curriculum for the Database Management Systems (DBMS) course . It demonstrates the design and implementation of a comprehensive e-commerce database using PostgreSQL. The system replicates core functionalities of an online shopping platform by managing data related to customers, products, sellers, orders, payments, reviews, and more.

The platform is designed to assist small businesses in transitioning from offline to online commerce through a reliable, scalable, and normalized relational database. It incorporates relational modeling, data integrity constraints, transactions, and advanced SQL features such as triggers, views, and stored procedures.

---

## Table of Contents

- Project Overview  
- Core Features  
- Database Schema  
- Technology Stack  
- Setup and Execution  
- Queries and Procedures  
- Analytical Capabilities  
- Contributor

---

## Project Overview

In today’s digital economy, e-commerce systems are central to business scalability and customer engagement. This project presents a fully functional and normalized database solution designed for small to medium-sized enterprises. It supports essential business processes such as product management, order processing, payment tracking, review collection, and inventory management.

The system prioritizes data consistency, transactional reliability, and query efficiency. It features role-based access control for customers and sellers, and supports analytical reporting through complex SQL queries and statistical visualizations.

---

## Core Features

### Customer Features

- View and update personal account details  
- Search and filter products by category  
- Add/remove products from cart or wishlist  
- View cart total and place orders  
- Choose preferred payment methods (COD, UPI, Card, etc.)  
- Rate and review purchased products

### Seller Features

- Update stock availability of products  
- View daily, monthly, and yearly sales reports

### System-Level Features

- Enforce referential integrity and normalization (up to 3NF)  
- Manage transactional workflows with commit/rollback  
- Triggers for real-time stock updates and order calculations  
- Views for data abstraction and restricted access  
- Stored procedures for modular business logic

---

## Database Schema

The database consists of the following entities and relationships:

- Customer  
- Seller  
- Product  
- Category  
- Orders  
- Order_Item  
- Payment  
- Cart  
- Review  
- seller_product (junction table for seller-product relationship)  
- cart_product (junction table for cart-product relationship)

Each table is created using PostgreSQL DDL syntax with primary keys, foreign keys, NOT NULL constraints, and CHECK constraints as needed.

An ER Diagram is used to illustrate relationships, participation, and cardinalities. (Attach image if available.)

---

## Technology Stack

| Component         | Technology        |
|------------------|-------------------|
| Database Engine   | PostgreSQL        |
| Query Language    | SQL, PL/pgSQL     |
| Data Analysis     | Python (Pandas, Seaborn, Matplotlib) |
| Visualization     | Jupyter Notebook  |
| Tools Used        | pgAdmin, DBeaver |
| OS Compatibility  | Windows, Linux, macOS |

---

## Setup and Execution

1. Clone the repository  
2. Open schema.sql inside the /ddl directory  
3. Run the queries using pgAdmin or any PostgreSQL client  
4. Insert sample data using /dml/inserts.sql  
5. Execute analytical queries from /queries/analytics.sql  
6. Run visualizations using /notebooks/analysis.ipynb  

---

## Analytical Capabilities

This project goes beyond CRUD operations by integrating analytics:

- Correlation analysis (e.g., product price vs. rating)  
- Linear regression (e.g., age vs. order value)  
- Chi-square tests (e.g., uniformity in product ratings)  
- Boxplots, heatmaps, and trend charts for visualization  
- Drill-down visual analysis for deeper insights

Proposed future enhancements include AWS ETL integration using Kinesis, Glue, S3, Athena, and Streamlit dashboards.

---

## Contributor

- [Krisha Sompura](https://github.com/Krisha2000)  
- [Milan Nagvadia](https://github.com/mpn311)

---

## License

This project is intended for academic and educational purposes only.

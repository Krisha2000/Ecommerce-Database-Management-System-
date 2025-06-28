# Ecommerce Database Management System

This project is developed as part of the curriculum for the Database Management Systems (DBMS) course at Punjab Technical University (PTU). It demonstrates the design and implementation of a comprehensive e-commerce database using PostgreSQL. The project replicates core functionalities of an online shopping platform by managing data related to customers, products, sellers, orders, payments, reviews, and more.

The system is designed to help small businesses transition from offline to online commerce through a reliable, scalable, and consistent relational database solution. It implements relational modeling, normalized schema design, data integrity constraints, transactions, and advanced SQL functionalities such as triggers and stored procedures.

---

## Table of Contents

- [Project Overview]
- [Core Features]
- [Database Schema]
- [Technology Stack]
- [Setup and Execution]
- [Queries and Procedures]
- [Advanced Functional Enhancements]
- [Analytical Queries]


---

## Project Overview

In today’s digital economy, e-commerce has become a crucial component for business growth. The primary objective of this project is to develop a fully functional and normalized e-commerce database system that supports business operations such as product browsing, customer orders, payment tracking, and inventory management.

This database system is optimized for small to medium-scale enterprises and ensures data accuracy, security, and ease of querying. It serves both customers and sellers with isolated access roles and supports analytical queries for business decision-making.

---

## Core Features

### Customer Functionalities
- View and update account information.
- Search products by category.
- Add and remove items from the cart or wishlist.
- View cart totals and place orders.
- Select and manage payment options.
- Submit reviews and ratings for purchased products.

### Seller Functionalities
- Update stock levels for listed products.
- Track total sales by day, month, or year.

### System Functionalities
- Ensure data consistency and referential integrity.
- Handle transactional operations with commit and rollback.
- Maintain strict access controls between customers and sellers.
- Automatically update order amounts and stock levels via triggers.

---

## Database Schema

The database includes the following core entities:
- `Customer`
- `Seller`
- `Product`
- `Category`
- `Order`
- `Order_Item`
- `Payment`
- `Cart`
- `Review`
- `seller_product` (many-to-many)
- `cart_product` (many-to-many)

Each entity is designed using best practices in relational schema design with appropriate constraints, keys, and normalization.

An ER diagram (not included here) illustrates the relationships, cardinalities, and participation types among entities.

---

## Technology Stack

| Component         | Technology        |
|------------------|-------------------|
| Database Engine   | PostgreSQL        |
| Query Language    | SQL / PLpgSQL     |
| Tools Used        | pgAdmin |
| Operating System  | Cross-platform (Windows, Linux, MacOS) |



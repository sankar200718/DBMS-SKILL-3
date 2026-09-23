# Inventory Management System

This project is a simple **Inventory Management System** developed using **MySQL**. It manages seller details and product inventory using SQL commands.

## Features

* Create an Inventory database
* Store seller details
* Store product details
* Add new products to inventory
* Update product quantity
* Delete products from inventory
* Display seller and inventory records
* Find products with available stock
* Find out-of-stock products
* Find the product with the highest quantity
* Calculate average and total inventory quantity

## Database Structure

The project contains two tables:

### Seller Table

* seller_id
* seller_name
* phone
* email

### Inventory Table

* inventory_id
* product_name
* quantity
* price
* seller_id

The `seller_id` in the inventory table is connected to the seller table using a **foreign key**.

## SQL Operations

The project demonstrates:

* `CREATE DATABASE`
* `CREATE TABLE`
* `INSERT`
* `SELECT`
* `UPDATE`
* `DELETE`
* `COUNT()`
* `MAX()`
* `AVG()`
* `SUM()`
* Subqueries
* Primary Key
* Foreign Key

The script includes sample sellers and products such as Laptop, Mobile Phone, Keyboard, Mouse, Headphones, Monitor, and Printer.

## Inventory Analysis

The SQL queries are also used to calculate the number of products with available stock, identify out-of-stock products, find the product with maximum quantity, and calculate average and total quantity.

## Technologies Used

* MySQL
* SQL

## Project Purpose

The main purpose of this project is to understand **database creation, table relationships, CRUD operations, and basic SQL aggregate functions** using a practical inventory management example.

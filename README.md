# GearShop

GearShop is a Spring Boot based e-commerce web application for computer hardware and accessories. The project provides a complete shopping experience for customers and management tools for administrators, including product browsing, category-based navigation, cart and checkout flows, order history, and inventory management.

## Overview

This application is built with Spring Boot, Thymeleaf, JPA, and MySQL. It is designed as a full-stack web solution for an online hardware store, with separate client and admin templates for different user roles.

## Main Features

- Browse products by category
- View detailed product information
- Search products and manage the shopping cart
- Place orders and review transaction history
- Manage products, brands, vouchers, users, and invoices in the admin area
- Support refund requests and customer account information

## Tech Stack

- Java 17
- Spring Boot 3
- Spring Data JPA
- Thymeleaf
- MySQL
- HTML, CSS, and JavaScript

## Project Structure

- Source code: Source Code/src/main/java
- Static assets: Source Code/src/main/resources/static
- Templates: Source Code/src/main/resources/templates
- Database scripts: Source Code/sanpham.sql and Source Code/insertsp.sql

## How to Run

1. Configure the MySQL connection in Source Code/src/main/resources/application.properties.
2. Import the SQL scripts if the database needs sample data.
3. Run the Spring Boot application from the Source Code directory.
4. Open the application in your browser after the server starts.

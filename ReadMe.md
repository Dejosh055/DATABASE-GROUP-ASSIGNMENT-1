BookStore Database Project by 2JP-Tech group

This project implements a MySQL database for managing a bookstore's operations. The database stores information about books, authors, customers, orders, and shipping details.

Objective
The objective of this project is to design and implement a relational database system using MySQL to efficiently manage the key operations of a bookstore. This includes storing and retrieving information about books, authors, customers, orders, and shipping. The system aims to streamline data handling, enhance operational transparency, and support future scalability and reporting needs, ensuring smooth day-to-day bookstore management.



 Project Structure

- database_schema.sql: Contains all SQL commands for creating the database and tables
- schema_diagram.drawio: Visual representation of the database schema
- README.md: Project documentation

 Database Tables

The database consists of the following tables:

1. book: Stores information about books
2. book_author: Manages many-to-many relationship between books and authors
3. author: Stores author information
4. book_language: Lists possible book languages
5. publisher: Stores publisher information
6. customer: Stores customer information
7. customer_address: Manages customer addresses
8. address_status: Tracks address statuses
9. address: Stores address information
10. country: Lists countries
11. cust_order: Stores order information
12. order_line: Tracks order items
13. shipping_method: Lists shipping methods
14. order_history: Tracks order status changes
15. order_status: Lists possible order statuses

Setup Instructions

1. Install MySQL if not already installed
2. Run the database_schema.sql script to create the database and tables
3. Use the schema diagram for visual reference

 Features

- Comprehensive book and author management
- Customer order tracking
- Shipping and delivery management
- Address management for customers
- Order history tracking

 Security

The database implements proper user management and access control to ensure data security.

![alt text](<schema_diagram_complete [MConverter.eu].png>)
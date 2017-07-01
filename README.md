# dani-_livshiz-_project
CREATE DATABASE northwind;
CREATE TABLE northwind.customers (social_security INT(11), first_name VARCHAR(20), last_name VARCHAR(20), email VARCHAR(55), city VARCHAR(20));
CREATE TABLE northwind.salesmans (social_security INT(11), first_name VARCHAR(20), last_name VARCHAR(20), email VARCHAR(55), city VARCHAR(20), start_of_work_date DATE);
CREATE TABLE northwind.purchases (id INT(11), customer_social_security INT(11), salesman_social_security INT(11), quantity INT(11), purchase_date DATE);
CREATE TABLE northwind.products (id INT(11), name VARCHAR(20), price INT(11));
/*
Third step: Primary key & Foreign Key (PK & FK)

Customers table

The column social_security should be PK.

Salesmans table

The column social_security should be PK.

Purchases table

The column id should be PK. The column customer_social_security should be a FK of social_security field of Customers table. The column salesman_social_security should be a FK of social_security field of salesmans table.

Products table

The column id should be PK.
*/

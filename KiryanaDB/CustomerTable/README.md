# Customer Table Module

This folder contains the SQL file(s) related to the **Customers table** 
for the Kiryana Store borrowed-items database.

## Contents

- `customers_table.sql` – SQL script to create the Customers table 
  and insert sample data.
- `customers_select.sql` – Sample SELECT queries to retrieve 
  customer information from the table.

## Purpose

The Customers table stores information about the store's customers 
or borrowers, such as their ID, Name, and Contact details. 
This allows tracking of which customer borrowed items from the store.

## Sample Queries

- View all customers:
  ```sql
  SELECT * FROM Customers;

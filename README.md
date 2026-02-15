# Database
This repository contains some databases created as part of my learning
# Kiryana Store Borrowed Items Database

This is a simple SQL database module for a small village Kiryana Store, 
where borrowed items by customers are tracked manually. 
The goal of this project is to practice SQL table creation, 
data insertion, and SELECT queries for learning purposes.

## Tables

1. **Customers** - Stores customer information (ID, Name, Contact)
2. **Items** - Stores items available in the store (ID, Name, Quantity)
3. **BorrowRecords** - Tracks which customer borrowed which item, 
   the quantity, and borrowing/return dates

## Sample Queries

- View all customers:
  SELECT * FROM Customers;

- View borrowed items that are not yet returned:
  SELECT * FROM BorrowRecords WHERE DateReturned IS NULL;

- Check item availability:
  SELECT * FROM Items;

## Learning Notes

- This project is created for SQL learning purposes.
- Author: Qadir Bakhsh

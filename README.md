# 📚 LibraryDB - SQL Developer Internship Task

## 🧾 Project Overview

This project represents a **Library Management System** implemented using **SQL (MySQL syntax)**. It includes table creation, data insertion, updates, deletions, and various data retrieval operations using `SELECT`, `WHERE`, `ORDER BY`, and `LIMIT`.

It is part of the **SQL Developer Internship Task 3**, focused on learning how to extract, filter, and sort data using SQL.

---

## 🛠️ Technologies Used

- SQL (MySQL-compatible)
- MySQL Workbench / DB Browser for SQLite (for execution)

---

## 🗃️ Database Schema

The database contains the following tables:

- **Authors**: AuthorID, Name
- **Categories**: CategoryID, CategoryName
- **Books**: BookID, Title, AuthorID, CategoryID
- **Members**: MemberID, Name, Email
- **Borrow**: BorrowID, MemberID, BookID, BorrowDate, ReturnDate

---

## 🧩 Features

✅ Create tables with primary and foreign keys  
✅ Insert initial data  
✅ Perform updates and deletes  
✅ Extract data using SQL queries:
- `SELECT *`, specific columns
- `WHERE`, `AND`, `OR`, `LIKE`, `BETWEEN`
- `ORDER BY` (ASC/DESC)
- `LIMIT`
- `DISTINCT`
- Aliasing with

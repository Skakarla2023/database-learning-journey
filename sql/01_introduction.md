# Introduction to SQL

## 📌 What is SQL?

SQL (Structured Query Language) is a standard language used to store, retrieve, manage, and manipulate data in relational databases. It is used to interact with databases like MySQL, PostgreSQL, Oracle, SQL Server, and SQLite.

---

## 📌 Why Do We Need SQL?

We need SQL to:

* Store large amounts of data
* Retrieve required information quickly
* Update and delete records
* Maintain data accuracy and security
* Manage databases efficiently

Without SQL, working with structured data would be very difficult and time-consuming.

---

## 📌 Why Do We Use SQL?

SQL is widely used because it is:

* Easy to learn and understand
* Supported by almost all databases
* Powerful for data analysis
* Useful for backend development
* Essential for data-driven applications

---

## 📌 Key Features of SQL

* Works with relational databases
* Uses simple English-like commands
* Supports data manipulation and control
* Handles large datasets efficiently
* Provides security through access control

---

## 📌 Basic Components of SQL

### 1. Tables

Data in SQL is stored in tables consisting of rows and columns.

### 2. Rows

Each row represents a single record.

### 3. Columns

Each column represents an attribute of data.

Example Table: Students

| ID | Name   | Age | Course |
| -- | ------ | --- | ------ |
| 1  | Rahul  | 20  | CS     |
| 2  | Anjali | 21  | IT     |

---

## 📌 Types of SQL Commands

### 1. DDL (Data Definition Language)

Used to define database structure.

* CREATE
* ALTER
* DROP
* TRUNCATE

### 2. DML (Data Manipulation Language)

Used to manage data in tables.

* INSERT
* UPDATE
* DELETE
* SELECT

### 3. DCL (Data Control Language)

Used to control access.

* GRANT
* REVOKE

### 4. TCL (Transaction Control Language)

Used to manage transactions.

* COMMIT
* ROLLBACK
* SAVEPOINT

---

## 📌 Basic SQL Syntax Examples

### Create Table

```sql
CREATE TABLE Students (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    age INT,
    course VARCHAR(30)
);
```

### Insert Data

```sql
INSERT INTO Students VALUES (1, 'Rahul', 20, 'CS');
```

### Retrieve Data

```sql
SELECT * FROM Students;
```

### Update Data

```sql
UPDATE Students SET age = 21 WHERE id = 1;
```

### Delete Data

```sql
DELETE FROM Students WHERE id = 1;
```

---

## 📌 Advantages of SQL

* Easy to use
* High performance
* Portable across platforms
* Supports data security
* Scalable for large systems

---

## 📌 Applications of SQL

* Web applications
* Banking systems
* E-commerce platforms
* Data analysis
* Enterprise software

---

## 📌 Prerequisites

To learn SQL, you should have:

* Basic computer knowledge
* Understanding of tables and data
* Interest in databases

---

## 📌 Learning Objectives

After completing this section, you will be able to:

* Understand what SQL is
* Write basic SQL queries
* Create and manage tables
* Manipulate data efficiently
* Prepare for advanced SQL topics

---



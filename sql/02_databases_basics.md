<h1 align="center"><b>Database Basics</b> </h1>


## 1. What is a Database?

A **database** is an organized collection of data that is stored electronically and can be easily accessed, managed, and updated.

Instead of storing data in files or notebooks, we store it in databases for better security, speed, and management.

### Example:
A college database can store:
- Student details
- Marks
- Attendance
- Fees information

---

## 2. Why Do We Need Databases?

Databases are needed to:

- Store large amounts of data
- Retrieve data quickly
- Avoid data duplication
- Maintain data security
- Allow multiple users to access data
- Keep data consistent and accurate

Without databases, managing data becomes slow and error-prone.

---

## 3. Types of Databases

### 3.1 Relational Databases (RDBMS)

- Data is stored in tables (rows and columns)
- Uses SQL
- Most commonly used

Examples:
- MySQL
- Oracle
- PostgreSQL
- SQL Server

### 3.2 NoSQL Databases

- Data is stored in non-table formats
- Used for big data and real-time apps

Examples:
- MongoDB
- Cassandra
- Redis

### 3.3 Distributed Databases

- Data is stored on multiple servers
- Improves performance and reliability

---

## 4. What is DBMS?

DBMS (Database Management System) is software that helps us create, manage, and operate databases.

It acts as a bridge between users and databases.

### Functions of DBMS:
- Store data
- Retrieve data
- Update data
- Delete data
- Provide security
- Handle backup and recovery

---

## 5. What is RDBMS?

RDBMS (Relational Database Management System) stores data in the form of tables and maintains relationships between them.

### Features:
- Uses tables
- Supports SQL
- Follows ACID properties
- Maintains data integrity

---

## 6. What is a Table?

A **table** is a structure used to store data in rows and columns.

### Example: Student Table

| ID | Name  | Marks |
|----|-------|--------|
| 1  | Rahul | 85     |
| 2  | Anita | 90     |

- Row = Record
- Column = Field

---

## 7. What is a Record and Field?

### Record:
A complete row in a table.

Example:
| 1 | Rahul | 85 | → One record

### Field:
A single column in a table.

Example:
| Name | → Field

---

## 8. What is SQL?

SQL (Structured Query Language) is used to communicate with databases.

It is used to:
- Create tables
- Insert data
- Read data
- Update data
- Delete data

### Example:
```sql
SELECT * FROM students;
```

## 9. Types of SQL Commands

SQL commands are divided into different categories based on their purpose.

### 9.1 DDL (Data Definition Language)

Used to define and manage database structure.

Commands:
- CREATE
- ALTER
- DROP
- TRUNCATE
- RENAME

---

### 9.2 DML (Data Manipulation Language)

Used to manage and modify data in tables.

Commands:
- INSERT
- UPDATE
- DELETE

---

### 9.3 DQL (Data Query Language)

Used to retrieve data from the database.

Command:
- SELECT

---

### 9.4 DCL (Data Control Language)

Used for access control and permissions.

Commands:
- GRANT
- REVOKE

---

### 9.5 TCL (Transaction Control Language)

Used to manage transactions.

Commands:
- COMMIT
- ROLLBACK
- SAVEPOINT

---

## 10. What is Primary Key?

A **primary key** is a column that uniquely identifies each record in a table.

### Characteristics:
- Cannot be NULL
- Must be unique
- Only one primary key per table

### Example:
Student ID

---

## 11. What is Foreign Key?

A **foreign key** is used to create a relationship between two tables.

It refers to the primary key of another table.

### Example:
Student Table → Course Table

The foreign key connects both tables.

---

## 12. What is Normalization?

Normalization is the process of organizing data to reduce redundancy and improve data integrity.

### Advantages:
- Reduces duplication
- Saves memory
- Improves consistency

### Common Normal Forms:
- 1NF (First Normal Form)
- 2NF (Second Normal Form)
- 3NF (Third Normal Form)
- BCNF (Boyce Codd Normal Form)

---

## 13. What is Index?

An **index** improves the speed of searching data in a table.

It works like an index in a book.

### Advantage:
- Faster data retrieval

### Disadvantage:
- Takes extra memory
- Slows down insert and update operations

---

## 14. What is a View?

A **view** is a virtual table created using one or more tables.

It does not store data physically.

### Uses:
- Improves security
- Simplifies complex queries
- Supports reusability

---

## 15. What is a Transaction?

A **transaction** is a group of SQL operations executed as a single unit.

Either all operations succeed or none are applied.

### Example:
Money transfer in a bank system

---

## 16. ACID Properties

ACID properties ensure reliable and secure transactions.

### A - Atomicity
All operations succeed or none are applied.

### C - Consistency
Data remains valid before and after the transaction.

### I - Isolation
Transactions do not affect each other.

### D - Durability
Committed data is saved permanently.

---

## 17. What is Backup and Recovery?

### Backup:
A copy of database data stored separately.

### Recovery:
Restoring data from backup after failure.

Used to prevent data loss.

---

## 18. Database Security

Database security protects data from unauthorized access.

### Methods:
- Username and password
- Roles and permissions
- Encryption
- Firewalls

---

## 19. Advantages of Databases

- Fast data access
- High security
- Data consistency
- Easy backup
- Multi-user support
- Reduced redundancy

---

## 20. Disadvantages of Databases

- High setup cost
- Maintenance required
- Needs skilled professionals
- Risk of system failure

---

## 21. Real-World Applications of Databases

- Banking systems
- Hospital management systems
- College management systems
- E-commerce websites
- Social media applications
- Railway reservation systems

---


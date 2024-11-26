# Database Management System (DBMS) Questions and Answers

## 1. Components of a DBMS (Database Management System)

A Database Management System (DBMS) consists of several components working together to store, manage, and retrieve data efficiently:

1. **Hardware**:  
   Physical devices like servers, storage systems, and networking equipment required for storing and accessing the database.

2. **Software**:  
   The DBMS software that provides functionality for database operations, query execution, and user interaction.

3. **Data**:  
   The actual information stored in the database, typically organized in a structured format such as tables.

4. **Users**:  
   - **End Users**: Individuals interacting with the database through applications.  
   - **Database Administrators (DBAs)**: Professionals managing database performance, security, and availability.  
   - **Application Developers**: Create software that communicates with the database.

5. **Query Processor**:  
   Interprets and executes user queries, converting them into commands understood by the database engine.

6. **Database Engine**:  
   The core service that processes commands, manages data storage, and ensures efficient retrieval and updates.

7. **Data Dictionary**:  
   Stores metadata, including table definitions, relationships, and constraints. It helps maintain data consistency.

---

## 2. What is a Relational Database?

A **relational database** stores data in tabular formats consisting of rows and columns. Relationships between tables are established using keys such as primary and foreign keys, making it easy to link related data.

**Examples of Relational Databases:**
- MySQL
- PostgreSQL
- Oracle Database
- Microsoft SQL Server

---

## 3. Classifications of SQL

SQL is classified into three main categories:

1. **DDL (Data Definition Language)**:  
   Used to define and manage the structure of the database.  
   Examples: `CREATE`, `ALTER`, `DROP`, `TRUNCATE`.

2. **DML (Data Manipulation Language)**:  
   Used for data retrieval and manipulation.  
   Examples: `SELECT`, `INSERT`, `UPDATE`, `DELETE`.

3. **DCL (Data Control Language)**:  
   Used to control access to the database.  
   Examples: `GRANT`, `REVOKE`.

4. **TCL (Transaction Control Language)**:  
   Manages database transactions.  
   Examples: `COMMIT`, `ROLLBACK`, `SAVEPOINT`.

---

## 4. Difference Between Primary Key and Foreign Key

| **Primary Key**                 | **Foreign Key**                       |
|----------------------------------|---------------------------------------|
| Uniquely identifies each record in a table. | Establishes a relationship between two tables. |
| Cannot contain NULL values.      | Can contain NULL values.              |
| Must be unique within the table. | Can have duplicate values in the referencing table. |
| Example: `id` column in a `users` table. | Example: `user_id` column in an `orders` table referencing `users.id`. |

---

## 5. What is an Entity-Relationship Diagram?

An **Entity-Relationship Diagram (ERD)** is a visual representation of the database structure. It shows entities (tables), attributes (fields), and relationships (associations) between entities. ERDs are used during database design to model the logical structure of a system.

---

## 6. Advantages of Relational Databases

1. **Data Integrity**:  
   Enforces data accuracy and consistency through constraints like primary keys and foreign keys.

2. **Scalability**:  
   Easily handles growing amounts of data.

3. **Flexibility**:  
   Supports complex queries using SQL.

4. **Data Relationships**:  
   Manages and queries related data effectively using joins.

5. **Security**:  
   Provides robust access controls.

---

## 7. Four Types of Data Types Used to Store Data in Tables

1. **Integer (INT)**: Stores whole numbers.
2. **Varchar (VARCHAR)**: Stores variable-length text.
3. **Date/Time (DATE, TIMESTAMP)**: Stores date and time values.
4. **Decimal/Float (DECIMAL, FLOAT)**: Stores numbers with decimals.

---

## 8. What is the Purpose of a Database Management System (DBMS)?

The purpose of a DBMS is to:

1. **Data Storage and Retrieval**: Efficiently store large volumes of data and retrieve it using queries.
2. **Data Integrity**: Maintain data accuracy and consistency.
3. **Security**: Restrict unauthorized access through user authentication and permissions.
4. **Concurrency Control**: Allow multiple users to access the database simultaneously without conflicts.
5. **Backup and Recovery**: Provide mechanisms to restore data in case of failures.

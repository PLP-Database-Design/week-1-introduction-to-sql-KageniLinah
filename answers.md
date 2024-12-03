State and Explain the components of a DBMS(Database Management System)

Query Processor
It interprets the queries received from user and executes them to commands for the database.
Query Processor contains the following components 
DML Compiler Converts Data Manipulation Language statements into instructions
DDL Interpreter Converts Data Definition Language statements into metadata 

Database Engine
Handles the storage, retrieval, and update of data and also ensures data consistency and manages query execution.

Data Dictionary
A metadata repository storing information about the database schema, constraints, and user permissions.

Database Schema
Defines the structure and organization of the data, such as tables, fields, and relationships.

What is a relational database? Give 4 examples.

A relational database is a collection of information that organizes data into tables which are known as relations with rows which represent records and columns thaat represent fields, making it easy to see and understand how different data structures relate to each other.

Examples

MySQL
PostgreSQL
Microsoft SQL Server
Oracle Database
MariaDB

State and Explain three classifications of SQL?

Data Definition Language(DDL)

Defines the structure of the database.
Examples: CREATE, ALTER, DROP.
Example: CREATE TABLE students (id INT, name VARCHAR(50));

Data Manipulation Language(DML)

Used to insert, update, delete, or retrieve data.
Examples: INSERT, UPDATE, DELETE, SELECT.
Example: SELECT * FROM students;

Data Control Language(DCL)

Manages user permissions and access.
Examples: GRANT, REVOKE.
Example: GRANT SELECT ON students TO user1;

What is the difference between a Primary Key and a Foreign Key?

Primary Key	Uniquely identifies each record in a table while Foreign Key establishes a link between two tables it references the primary key in another table

What is an Entity-Relationship Diagram?

An Entity-Relationship Diagram is a visual representation of how items in a database relate to each other. It illustrates entities, attributes, and the relationships between them. 

What are the advantages of relational databases?

Ensures data integrity by providing accuracy and consistency using constraints like primary and foreign keys.
Easy to Use since SQL provides a straightforward way to query and manipulate data.
Scalable since it can supports large datasets and can handle multiple users concurrently.
Data Security since it includes access controls to restrict unauthorized access.

State four types of data type used to store data in tables?

Integer - Stores whole numbers
 Example INT

Character/String - Stores text data 
Example: CHAR, VARCHAR, TEXT

Date/Time - Stores dates and times
Example: DATE, DATETIME

Floating Point - Stores decimal numbers.
Example: FLOAT, DECIMAL.

What is the purpose of a database management system (DBMS)?

The primary purpose of a DBMS is to provide an efficient and reliable way to store, retrieve, and manage data while ensuring data consistency, security, and integrity.
##State and Explain the components of a DBMS(Database Management System)
 Database Management System (DBMS) is a software system that enables users to create, manage, and manipulate databases efficiently. It acts as an intermediary between the user and the database. The key components of a DBMS are outlined and explained below:
1. Database Engine
Purpose: The core component responsible for storing, retrieving, and updating data in the database.

Functions:
Executes database queries (e.g., SELECT, INSERT, UPDATE, DELETE)..
2. Database Schema
Purpose: Defines the logical structure of the database.
Functions:
Includes tables, fields, relationships, views, and indexes.
3. Query Processor
Purpose: Translates user queries into commands the DBMS can execute.
Functions:
Optimizes and interprets SQL commands for efficient execution.
Checks the syntax and semantics of user queries.
Communicates with the database engine to retrieve data.
4. Database Manager
Purpose: Manages the interaction between the database and other components.
##What is a relational database? Give 4 examples.
A relational database is a type of database that organizes and stores data in a structured format using tables (rows and columns). Each table represents an entity (e.g., customers, products) and contains rows (records) and columns (attributes).
Examples of Relational Databases
MySQL:
An open-source RDBMS widely used for web applications.
Known for reliability, scalability, and performance.
PostgreSQL:

An open-source RDBMS with advanced features like JSON support and extensibility.
Highly suited for complex applications requiring data integrity.
Oracle Database:

A powerful commercial RDBMS with enterprise-grade features for large-scale applications.
Known for its robust performance, scalability, and security.
Microsoft SQL Server:

A commercial RDBMS by Microsoft, often used in enterprise environments.
Offers integration with Microsoft tools like Excel and Power BI.

State and Explain three classifications of SQL?
1. Data Definition Language (DDL)
Purpose:
DDL commands are used to define, create, modify, and delete database structures, such as tables, schemas, and indexes.
2. Data Manipulation Language (DML)
Purpose:
DML commands handle the manipulation of data stored in the database. This includes inserting, updating, deleting, and querying data.
3. Data Control Language (DCL)
Purpose:
DCL commands manage user access and permissions in the database.
##What is the difference between a Primary Key and a Foreign Key?
A Foreign Key is a column (or combination of columns) in one table that establishes a relationship with the Primary Key in another table.
A Primary Key is a column (or combination of columns) in a table that uniquely identifies each row in that table.

##What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a visual representation of the entities in a database and the relationships between them. It is used in database design to map out the logical structure of a system, helping to identify the data requirements and relationships before building the actual database.

##What are the advantages of relational databases?
1. Data Integrity and Accuracy
Relational databases enforce constraints like primary keys, foreign keys, and unique keys to ensure data consistency.
Relationships between tables are explicitly defined, reducing data duplication and ensuring reliable connections between datasets.
2. Flexibility in Querying Data
With Structured Query Language (SQL), relational databases allow users to query and manipulate data efficiently.
Complex queries, such as joins, nested queries, and aggregations, are easily supported.
3. Scalability and Performance
Relational databases can scale vertically (adding resources to a single server) or horizontally (using sharding or replication across multiple servers).
Optimization techniques like indexing and query optimization improve data retrieval performance.
4. Standardization
Relational databases adhere to established standards like SQL, ensuring compatibility across systems and platforms.
Standardization simplifies integration with third-party tools and applications.
5. Data Security
Relational databases offer robust security features:
Role-based access control (RBAC): Restricts data access based on user roles.
Encryption: Protects sensitive data during storage and transmission.
Authentication and authorization: Ensures only authorized users can access or modify the database.

##State four types of data type used to store data in tables?
1. Numeric Data Types
Purpose: Store numeric values, such as integers, decimals, or floating-point numbers.
Examples:
INT (INTEGER): Stores whole numbers.
2. Character/String Data Types
Purpose: Store textual data.
Examples:
CHAR(n): Fixed-length string with a defined size.
3. Date and Time Data Types
Purpose: Store date, time, or datetime values.
Examples:
DATE: Stores only the date in YYYY-MM-DD format.
Example: 2024-12-01.
4. Boolean Data Type
Purpose: Stores logical values (TRUE or FALSE).
Examples:
BOOLEAN: Stores TRUE, FALSE, or sometimes 1 (true) and 0 (false).
Example: 1 for "is_active" or 0 for "is_deleted".
##What is the purpose of a database management system (DBMS)?
Key Purposes of a DBMS
1. Data Storage and Organization
Purpose: Store large volumes of data in a structured format for easy retrieval and management.
How It Helps: Organizes data into tables, rows, and columns to represent relationships clearly.
2. Data Retrieval
Purpose: Allow users and applications to query the database to retrieve specific information.
How It Helps: Uses SQL (Structured Query Language) to enable complex data queries and analytics.
3. Data Manipulation
Purpose: Enable users to insert, update, delete, or modify data within the database.
How It Helps: Maintains the flexibility to adjust data as business or application requirements change.

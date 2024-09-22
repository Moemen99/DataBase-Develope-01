# Database Development Process

## 1. Database Design

The process begins with database design, which includes:

1. Requirement gathering
2. Conceptual design
3. Logical design

## 2. Entity-Relationship Diagram (ERD)

- After the design phase, we create an Entity-Relationship Diagram (ERD)
- ERD visually represents the relationships between entities in the database

## 3. Database Mapping

- ERD is then mapped to create the database schema
- The schema shows tables and their relationships

## 4. Implementation

### 4.1 Database Management System (DBMS)

To implement the database, we use a Database Management System such as:
- SQL Server
- MySQL
- Oracle
- PostgreSQL

### 4.2 Server Requirements

Before creating the database, you need a server:

- A server is a computer with enhanced capabilities:
  - More RAM
  - Powerful processor
  - Specialized operating system
- Designed to handle multiple requests and high loads
- Accessible over the internet

#### Types of Servers

1. **Local Server**
   - Your PC can act as a local server
   - Only accessible by the user (you)

2. **Company Server**
   - Used in corporate environments
   - Teams work with it remotely
   - Can be located on-premises or elsewhere
   - Connection via Remote Desktop Connection application
   - Access restricted to authorized users

### 4.3 Working Environment

For database development, we often use a local machine as a local server:

1. Install the necessary database service on your computer
2. This allows your PC to function as a database server

## 5. Remote Access (for Company Servers)

- Connect to remote servers using their IP address
- Use Remote Desktop Connection or similar applications
- Access restricted to authorized users

## 6. SQL Server Setup and Connection

### 6.1 Installing SQL Server

1. Download SQL Server (choose Development Edition for local development)
2. Install the SQL Server database engine service
   - This service executes and runs queries (commands to create, insert, delete, or update data)

### 6.2 Installing SQL Server Management Studio (SSMS)

1. Download and install SSMS to manage your SQL Server instance

### 6.3 Connecting to the Server

1. Open SSMS
2. Choose server type: "Database Engine"
3. Server name: 
   - Use your device name
   - Or use "." if you have only one SQL Server instance
4. Select authentication method: "Windows Authentication"
5. Click "Connect"

### 6.4 Database Files

SQL Server uses two types of database files:

1. **MDF (Main Database File)**
   - Contains all the information in the database
   - Stores tables, views, stored procedures, etc.

2. **LDF (Log Database File)**
   - Stores transaction logs
   - Used for database recovery and maintaining data integrity

## 7. Working with the Database

After connecting to the server:

1. Create the database using the schema developed earlier
2. Implement tables and relationships
3. Begin data entry and database operations
4. Use SQL queries to manipulate and retrieve data

## 8. Next Steps

- Learn SQL syntax for various operations (SELECT, INSERT, UPDATE, DELETE)
- Understand database backup and recovery processes
- Explore performance tuning and optimization techniques

---

**Note**: This document outlines the general process of database development, from design to implementation, with a focus on SQL Server. Always refer to official Microsoft documentation for the most up-to-date information on SQL Server installation and management.

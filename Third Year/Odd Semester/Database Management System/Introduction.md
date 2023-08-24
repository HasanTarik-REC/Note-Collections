### Chapter 1 (Introduction)

### **<br/>Database Management System**

A database-management system (DBMS) is a collection of interrelated data and a set of programs to access those data. The collection of data, usually referred to as the database, contains information relevant to an enterprise. The primary goal of a DBMS is to provide a way to store and retrieve database information that is both convenient and efficient.


### **<br/> Application of Database Management System**

Databases are widely used. Here are some representative applications:

- `Banking:` For customer information, accounts, loans, and all transactions.
- `Airlines:` For reservations and schedule information.
- `Universities:` For student information, course registrations, and grades.
- `Sales:` For customer, product, and purchase information.
- `Manufacturing:` For management of the supply chain, orders, inventory, and production of items in factories.
- `Human resources:` For information about employees, salaries, tax deductions, etc.

Databases touch all aspects of our lives.


### **<br/>Level of Data Abstraction**

- Physical level: The lowest level of abstraction describes how the data are actually stored. 
The physical level describes complex low-level data structures in detail.
- Logical level: The next-higher level of abstraction describes what data are stored in the database, and what 
relationships exist among those data. The logical level thus describes the entire database in terms of a small number 
of relatively simple structures. Database administrators, who must decide what information to keep in the database, use the logical level of abstraction.
- View level: The highest level of abstraction describes only part of the entire database. Even though the logical level 
uses simpler structures, complexity remains because of the variety of information stored in a large database. 
Many users of the database system do not need all this information; instead, they need to access only a part of the database. 
The view level of abstraction exists to simplify their interaction with the system. The system may provide many views for 
the same database.


### **<br/>Responsibilities of a Database Administrator**
- Periodically backing up the database, either onto tapes or onto remote servers, to prevent loss of data in case of disasters such as flooding.
- Ensuring that enough free disk space is available for normal operations, and upgrading disk space as required.
- Monitoring jobs running on the database and ensuring that performance is not degraded by very expensive tasks submitted by some users.


## **<br/>Six major steps that you would take in setting up a database for an enterprise**

1. Define the high-level requirements of the enterprise (this step generates a document known as the system requirements specification.)
2. Define a model containing all appropriate types of data and data relationships.
3. Define the integrity constraints on the data.
4. Define the physical level.
5. For each known problem to be solved on a regular basis (e.g., tasks to be carried out by clerks or Web users) define a user interface to carry out the task, and write the necessary application programs to implement the user interface.
6. Create/initialize the database.


## **<br/>Five main functions of a database administrator**

1. To create the scheme definition
2. To define the storage structure and access methods
3. To modify the scheme and/or physical organization when necessary
4. To grant authorization for data access
5. To specify integrity constraints


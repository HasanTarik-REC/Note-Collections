### Chapter 1 (Introduction)

### **<br/>Database Management System**

A database-management system (DBMS) is a collection of interrelated data and a set of programs to access those data. The collection of data, usually referred to as the database, contains information relevant to an enterprise. The primary goal of a DBMS is to provide a way to store and retrieve database information that is both convenient and efficient.

### **<br/>Purpose of Database Management System**

Database management systems were developed to handle the following difficulties of typical file processing systems supported by conventional operating systems.
  - Data redundancy and inconsistency
  - Difficulty in accessing data
  - Data isolation
  - Integrity problems
  - Atomicity of updates
  - Concurrent access by multiple users
  - Security problems 

### **<br/> Application of Database Management System**

Databases are widely used. Here are some representative applications:

- `Banking:` For customer information, accounts, loans, and all transactions.
- `Airlines:` For reservations and schedule information.
- `Universities:` For student information, course registrations, and grades.
- `Sales:` For customer, product, and purchase information.
- `Manufacturing:` For management of the supply chain, orders, inventory, and production of items in factories.
- `Human resources:` For information about employees, salaries, tax deductions, etc.

Databases touch all aspects of our lives.


### **<br/>Purpose of Database systems**
<p>The purpose of database systems is to make the database user-friendly and do easy operations. Users can easily insert, update, and delete. The main purpose is to have more control of the data.<br/></p>

The purpose of database systems is to manage the following insecurities:<br/>
1. Data redundancy and inconsistency
2. Difficulty in accessing data,
3. Data isolation,
4. Atomicity of updates,
5. Concurrent access,
6. Security problems, and
7. Supports multiple views of data.


### **<br/>Advantage of DBMS over file system**

- `No redundant data:` Redundancy removed by data normalization. No data duplication saves storage and improves access time.
- `Data Consistency and Integrity:` As we discussed earlier the root cause of data inconsistency is data redundancy, Data inconsistency has also been taken care of as part of it.
- `Data Security:` DBMS provides various security features to protect data from unauthorized access, modification, or destruction. 
- `Easy access to data:` Database systems manage data in such a way that the data is easily accessible with fast response time.
- `Data Sharing:` DBMS makes it easy to share data among multiple users and applications.
- `Data Scalability:` DBMS can be scaled to accommodate large amounts of data and users.
- `Data backup and recovery:` DBMS provides built-in backup and recovery features to protect data from loss or corruption.

### **<br/>Two disadvantages associated with database systems are listed below**
  a. Database system setup requires more knowledge, money, skills, and time.
  b. The complexity of the database may result in poor performance.

### **<br/>Level of Data Abstraction**

- **Physical level**: The lowest level of abstraction describes how the data are stored. 
The physical level describes complex low-level data structures in detail.
- **Logical level**: The next-higher level of abstraction describes what data are stored in the database, and what 
relationships exist among those data. The logical level thus describes the entire database in terms of a small number 
of relatively simple structures. Database administrators, who must decide what information to keep in the database, use the logical level of abstraction.
- **View level**: The highest level of abstraction describes only part of the entire database. Even though the logical level 
uses simpler structures, complexity remains because of the variety of information stored in a large database. 
Many users of the database system do not need all this information; instead, they need to access only a part of the database. 
The view level of abstraction exists to simplify their interaction with the system. The system may provide many views for 
the same database.


## **<br/>Six major steps that you would take in setting up a database for an enterprise**

1. Define the high-level requirements of the enterprise (this step generates a document known as the system requirements specification.)
2. Define a model containing all appropriate types of data and data relationships.
3. Define the integrity constraints on the data.
4. Define the physical level.
5. For each known problem to be solved on a regular basis (e.g., tasks to be carried out by clerks or Web users) define a user interface to carry out the task, and write the necessary application programs to implement the user interface.
6. Create/initialize the database.


### **<br/>Data storage and Querying**

The functional components of a database system can be broadly divided into the storage manager and the query processor components.
- The storage manager is important because databases typically require a large amount of storage space.
- The query processor is important because it helps the database system simplify and facilitate access to data.

### **<br/>Storage Manager**

A storage Manager is a program module that provides the interface between the low-level data stored in the database and the application programs and queries submitted to the system. The storage manager is responsible for the interaction with the file manager.<br/>

The storage manager components include:<br/>
- **Authorization and integrity manager**, which tests for the satisfaction of integrity constraints and checks the authority of users to access data.
- **Transaction manager**, which ensures that the database remains in a consistent state despite system failures and that concurrent transaction execution proceeds without conflict.
- **File manager**, which manages the allocation  of space on disk storage and the data structures used to represent information stored on disk.
- **Buffer manager**, which is responsible for fetching data from disk storage into main memory and deciding what data to cache in main memory. The buffer manager is a critical part of the database system since it enables the database to handle data sizes that are much larger than the size of the main memory.

The storage manager implements several data structures as part of the physical system implementation:<br/>
- Data files
- Data dictionary
- Indices

### **<br/>The Query Processor**

The query processor components include:
- **DDL interpreter**, which interprets DDL statements and records the definitions in the data dictionary.
- **DML compiler**, which translates DML statements in a query language into an evaluation plan consisting of low-level instructions that the query evaluation engine understands. The DML compiler also performs query optimization.
- **Query evaluation engine**, which executes low-level instructions generated by the DML compiler.


### **<br/>Transaction Managerment**

A transaction is a collection of operations that performs a single logical function in a database application.

### **<br/>Data Mining**

The term data mining refers loosely to the process of semiautomatically analyzing large databases to find useful patterns.


### **<br/>Database Users**

People who work with a database can be categorized as database users. There are four different types of database-system users.
- Naive users
- Application programmers
- Sophisticated users
- Specialized users


### **<br/>Database Administrator**

A person who has such central control over the system is called a database administrator(DBA).


## **<br/>Five main functions of a database administrator**

1. To create the scheme definition
2. To define the storage structure and access methods
3. To modify the scheme and/or physical organization when necessary
4. To grant authorization for data access
5. To specify integrity constraints

### **<br/>Responsibilities of a Database Administrator**
- Periodically backing up the database, either onto tapes or onto remote servers, to prevent loss of data in case of disasters such as flooding.
- Ensuring that enough free disk space is available for normal operations, and upgrading disk space as required.
- Monitoring jobs running on the database and ensuring that performance is not degraded by very expensive tasks submitted by some users.


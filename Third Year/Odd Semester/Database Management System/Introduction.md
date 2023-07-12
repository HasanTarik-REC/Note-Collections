Level of Data Abstraction

Physical level: The lowest level of abstraction describes how the data are actually stored. 
The physical level describes complex low-level data structures in detail.

Logical level: The next-higher level of abstraction describes what data are stored in the database, and what 
relationships exist among those data. The logical level thus describes the entire database in terms of a small number 
of relatively simple structures. Although implementation of simple structures at the logical level may involve 
complex physical-level structures the user of the logical level does not need to be aware of this complexity. 
Database administrators, who must decide what information to keep in the database, use the logical level of abstraction.

View level: The highest level of abstraction describe only part of the entire database. Even though the logical level 
uses simpler structures, complexity remains because of the variety of information stored in a large database. 
Many users of the database system do not need all this information; instead, they need to access only a part of the database. 
The view level of abstraction exists to simplify their interaction with the system. The system may provide many views for 
the same database. 

Responsibilities of a Database Administrator
1. Periodically backing up the database, either onto tapes or onto remote servers, to prevent loss of data in case of disasters such as flooding.
2. Ensuring that enough free disk space is available for normal operations, and upgrading disk space as required.
3. Monitoring jobs running on the database and ensuring that performance is not degraded by very expensive tasks submitted by some users.


Six major steps that you would take in setting up a database for an enterprise

• Define the high-level requirements of the enterprise (this step generates a document known as the system requirements specification.)
• Define a model containing all appropriate types of data and data relationships.
• Define the integrity constraints on the data.
• Define the physical level.
• For each known problem to be solved on a regular basis (e.g., tasks to be carried out by clerks or Web users) define a user interface to carry out the task, and write the necessary application programs to implement the user interface.
• Create/initialize the database.


Five main functions of a database administrator

• To create the scheme definition
• To define the storage structure and access methods
• To modify the scheme and/or physical organization when necessary
• To grant authorization for data access
• To specify integrity constraints


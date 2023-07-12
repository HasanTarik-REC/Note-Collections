Level of Data Abstraction

Physical level: The lowest level of abstraction describes how the data are actually stored. 
The physical level describes complex low-level data structures in detail.

Logical level: The next-higher level of abstraction describes what data are stored in the database, and what 
relationships exist among those data. The logical level thus describes the entire database in terms of a small number 
of relatively simple structures. Although implementation of the simple structures at the logical level may involve 
complex physical-level structures the user of the logical level does not need to be aware of this complexity. 
Database administrators, who must decide wha information to keep in the database, use the logical level of abstraction.

View level: The highest level of abstraction describe only part of the entire database. Even though the logical level 
uses simpler structures, complexity remains because of the variety of information stored in a large database. 
Many users of the database system do not need all this information; instead, they need to access only a part of the database. 
The view level of abstraction exists to simplify their interaction with the system. The system may provide many views for 
the same database. 
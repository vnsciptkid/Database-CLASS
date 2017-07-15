# Database-CLASS

Some concepts must understand: 
- Database : structured data (dữ liệu được tổ chức)
- Types of database
  + Relational Database (MySQL, SQL Server ...)
  + Non-relational Database (MongoDB)
  + Others
- Relational Database
- Table
- Attribute, Fields, Collumns
- Record, Rows
- Normalization : What , Why?
  + Process of breaking apart relation into smaller parts to remain accuracy of database
- What characteristics of a good design?
- What is integrity? What is duplication?  
- Denormalization?
  + As opposed with normalization, denormalization is process of combine different relations to a big one 
  + Why ? for simplicity perposes or increase speed of queries.
  + Extract information from a table without JOIN operation (expensive one in terms of time).
  + What about cost? modification anomalies, redundant data, more space storage required
- Modification Anomalies : What ? Example
- Insertion Anomaly, Deletion Anomaly, Update Anomaly : What are the differences?
- Normal Forms
  + 3 normal forms is good enough for many situations
  + 2nd form: data doesn't depend on the key
  + 3rd form: no redundant data
- Primary Key (PK) and Foreign Key (FK)
  + PK : identify a particular record in the table, its different with indexes
 
- Relationship? 1-1, 1-m, m-m
  

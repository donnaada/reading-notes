# 🗒️ Class 04: Data Modeling

## Reading

### #nosql vs sql

-What type of database is the best fit for the complex query intensive environment?
  > SQL Databases

-What type of database is the best fit for hierarchical data storage?
  > NoSQL

-Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
  > SQL Databases scale vertically meaning you keep adding on any additional resources needed to a single machine where as NoSQL DBs scale horizontally so if we need to scale up, we would just need to add another machine and distribute the load across all the machines.

### #sql modeling techniques

-Among data tables, what is a one-to-many relationship and how do we “relate” them?
  > One to many means that one entry in a table can be related to multiple entries in antoher table. we relate them by using `1..*`

-Prior to designing your relational database, it might be useful to ___a___ of the database tables and their relationships.
  > Create a Data Model

-Explain the difference between a primary and foreign key.
  > A primary key is a unique variable for a specific database table and a foreign key is a variable in that table that refers to the primary key in another table.

## Videos

### #sql vs nosql

-How do we treat keywords and parameters differently in SQL syntax?
  > Keywords are the commands and paramenters are the values, the whats and the wheres for example `SELECT * (all) FROM database WHERE id = 1`

-Define normalization within the context of schemas and data.
  > Normalization is the process of organizing and structuring the data in a database to reduce redundancy.

-Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
  > One-to-one: If we are looking at two tables, a one-to-one relationship means that one item from table A can ONLY HAVE one item from table B and vise versa.
  > one-to-many: One item from Table A can have many items from table B, think of like a team in the NFL, one team can have many players, but each player can only be in one team at a time.
  > many-to-many: Opposite of one-to-one relationships in that data in each table can have belong to many records in the other table. In order to properly handle this relationship type, we would need to create a new table to represent the relationship.
  
# 301 - Read14

## Database Normalization

Database normalization is a process used to organize a database into tables and columns. and make each table related to a specific topic. This allow us to reduce the number of duplicate data contained within our database.

**Reasons for Database Normalization** 

- Minimize duplicate data

- Avoid data modification issues 

- Simplify queries


**Modification Anomalies** 

- Insert Anomaly: We cannot record a new row until we know information about the entire row.

- Update Anomaly: We have to update all rows, or inconsistencies appear.

- Delete Anomaly: Deletion of a row causes removal of more than one set of facts


### Forms of Database Normalization (1NF, 2NF, and 3NF)

- First Normal Form (1NF) – The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.

- Second Normal Form (2NF) – The table is in first normal form and all the columns depend on the table’s primary key.

- Third Normal Form (3NF) – the table is in second normal form and all of its columns are not transitively dependent on the primary key.
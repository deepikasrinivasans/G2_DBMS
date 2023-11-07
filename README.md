# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## Date:
## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```
 create table student(rollno int,name char(20),age int,address varchar(20),phoneno int);
```
### OUTPUT:

![out01](https://github.com/deepikasrinivasans/G2_DBMS/assets/119393935/022e62e2-4a56-4a44-b505-1a37123ee806)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);
```
### OUTPUT:
![out02](https://github.com/deepikasrinivasans/G2_DBMS/assets/119393935/e6de9a84-8899-437a-b4be-8b278a127d9a)
### 3) Drop the student table
 
### SQL QUERY: 
 ```
drop table student;
```

### OUTPUT:
![out03](https://github.com/deepikasrinivasans/G2_DBMS/assets/119393935/29293724-c10b-408e-a9d5-7644fde3c403)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```
### OUTPUT:
![out04](https://github.com/deepikasrinivasans/G2_DBMS/assets/119393935/b77f7953-76e1-40b5-8fe3-969a8045ddc1)
### 5) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student rename to mystudent;
```
### OUTPUT:
![out06](https://github.com/deepikasrinivasans/G2_DBMS/assets/119393935/c06008fb-ed03-4009-867f-0c1c9305eff9)
### RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.

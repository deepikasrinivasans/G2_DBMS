# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

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

![out1](https://github.com/deepikasrinivasans/G2_DBMS/assets/119393935/037ab0ac-e2b7-48f5-9299-437288d1f983)
### 2) Change the above student table by adding another attribute department
### SQL QUERY: 
```
alter table student add department char(30);
```
### OUTPUT:
![out2](https://github.com/deepikasrinivasans/G2_DBMS/assets/119393935/a1b03bd4-0cfe-43f9-bef1-75a6437ea81c)
### 3) Drop the student table
 ### SQL QUERY: 
```
drop table student;
```
### OUTPUT:
![out3](https://github.com/deepikasrinivasans/G2_DBMS/assets/119393935/928b37df-5fbf-4837-9f35-3479845ca32b)
### 4) Delete the student table using truncate keyword
### SQL QUERY: 
```
truncate table student;
```
### OUTPUT:
![out4](https://github.com/deepikasrinivasans/G2_DBMS/assets/119393935/04feecc3-6236-47ac-95da-25f63b40a3bc)
### 5) Rename the student table to mystudent
### SQL QUERY: 
```
alter table student rename to mystudent;
```
### OUTPUT:
![out5](https://github.com/deepikasrinivasans/G2_DBMS/assets/119393935/e33618a8-2871-45e2-a350-909602696840)
## RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.


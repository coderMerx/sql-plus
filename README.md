# The SQL*Plus

## 1) how to create a table with out constrain 
<img src="image/1.png" width="1000" height="500">

```bash
create table EMPLOYEE
(
Sno number(5),
Name varchar(20),
Phone number(10),
branch varchar(5)
);
```
## 2) how to create a table with constrain 
<img src="image/2.png" width="1000" height="500">

```bash
create table table_name
(
Sno number(5) check(Sno>0) primary key,
Name varchar(20) not null,
Phone number(10) not null unique check(length(Phone)=10),
 branch varchar(5) not null
);

```

## 3) how to rename table name 
<img src="image/3.png" width="1000" height="500">

```bash
RENAME Old_name to new_name;
```
## 4) how to delete table permanently from data base 

```bash
truncate table EMPLOYEE2;
```
### Truncate will empty the table (will not remove the table structure)

## 5) how to drop the table from database
<img src="image/4.png" width="1000" height="500">

```bash
drop table table_name;
```

## 6) 

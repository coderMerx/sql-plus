# The SQL*Plus

## 1) how to create a table with out constrain 
<img src="https://raw.githubusercontent.com/Narayanan-info/Narayanan-info/main/g1.gif" width="1000" height="500">

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
<img src="https://raw.githubusercontent.com/Narayanan-info/Narayanan-info/main/g1.gif" width="1000" height="500">

```bash
create table table_name
(
Sno number(5) check(Sno>0) primary key,
Name varchar(20) not null,
Phone number(10) not null unique check(length(Phone)=10),
 branch varchar(5) not null
);

```
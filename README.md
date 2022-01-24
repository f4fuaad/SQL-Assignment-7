# SQL-Assignment-7

Q-1. Write an SQL query to show only odd rows from a table.
Ans select* from worker 
    where id_no%2=1

Q-2. Write an SQL query to clone a new table from another table.

Ans select * into emp_table
         From worker_table

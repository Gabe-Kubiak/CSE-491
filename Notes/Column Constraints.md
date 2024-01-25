## HAVE TO BE Unique:
- Used to specify a column whose values will always be unique for every row.
>[!example]
>```SQL
>CREATE TABLE students (msu_id TEXT UNIQUE, pid INTEGER UNIQUE, first_name TEXT);

>[!warning]
>The DBMS will raise an error if the constraint is violated.

This is why [[NOT NULL]] exists
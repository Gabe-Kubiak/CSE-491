- Each table can have at most one PRIMARY KEY.
	- It is implicitly NOT NULL and UNIQUE
	- It is used to specify a specific column in the [[TABLE]] 
```SQL
CREATE TABLE students (msu_id TEXT PRIMARY KEY, grade REAL);
```


# Composites
- You can create a primary key out of multiple columns if the combination is unique
>[!example]
>```SQL
>CREATE TABLE students (first_name TEXT, last_name TEXT, PRIMARY KEY (first_name, last_name));

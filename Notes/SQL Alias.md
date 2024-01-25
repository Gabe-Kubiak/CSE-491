Another helpful piece of syntax is aliases if you want to refer to a column by a different name. 
```SQL
SELECT msu_net_id AS id FROM students WHERE id = 'mariani4';
```

 • You can also use it on [[TABLES]]:
 ```SQL
 SELECT cse380.msu_net_id FROM students AS cse380; 
```

- Implicit Alias, not recommended
```SQL
SELECT cse380.msu_net_id FROM students cse380;
```

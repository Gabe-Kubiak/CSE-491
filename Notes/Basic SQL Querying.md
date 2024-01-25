SQL Values  
– Integers and real values (floats) are represented as  
you would expect  
– Strings are as well, except they require single  
quotes  
• Two single quotes = one real quote  
– 'Joe''s Bar' = Joe's Bar  
– Any value can be NULL  
• For now, we will learn later how this can be prevented  

## Insertion  
- To [[INSERT]] a single record:  
>[!warning] If you don't specify an order it will default
```SQL
INSERT INTO <relation>  
VALUES ( <list of values> );  
– Example: add Star Wars to our Movies relation  
INSERT INTO Movies  
VALUES (‘Star Wars’, 1977, 124, ‘sciFi’);  
```

## [[SELECT]] 
- Using a Movies [[Relations|Relation]], what movies have been released?  
`SELECT title `  <- Column selected
`FROM Movies` <- [[Table]] we want to [[SELECT]] from

## [[SELECT]] and [[ORDER BY]] 
-  Using our Movies relation, what movies came out, ordered from oldest to newest  
```SQL
SELECT title  /*Column we want to select */ 
FROM Movies  /*Table we want to select from*/
ORDER BY year; /*Column to order results by*/
``` 
- Can do [[Custom Collations]] to [[ORDER BY]] <- Taught in CSE 480

# [[Wild Card]] Character '\*'

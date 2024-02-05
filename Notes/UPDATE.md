- Updates data values in [[Databases]]
- Can update 1 or more records in a table
- Use [[WHERE]] clause to update only certain records
>[!example]
>```SQL
>UPDATE students SET spelling = 0 WHERE spelling >10;

- '||' is concatenate in SQL
>[!example]
>```SQL
>UPDATE students SET spelling = 0 WHERE spelling >10; UPDATE students SET fav_word = fav_word || '!';

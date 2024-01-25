>[!example]
>```SQL
>SELECT title, genre FROM Movies WHERE length BETWEEN 90 AND 130;
>```
>>[!warning]
>>`BETWEEN` is inclusive of the bounds

# Can't do this:
>[!example]
>```SQL
>SELECT title, genre FROM Movies WHERE length >= 90 AND length <= 130;


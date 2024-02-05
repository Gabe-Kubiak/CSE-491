- You can also use a [[SELECT]] clause to generate the needed rows, but you need to return the correct column types and order.
>[!example]
>```SQL
>INSERT INTO spelling_team (first_name, spelling) SELECT students.first_name, students.spelling FROM students ORDER BY spelling DESC LIMIT 10;


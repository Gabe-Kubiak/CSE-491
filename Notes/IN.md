- Only tests for inclusion in a [[Set]]
	- Static parenthesized list
>[!example]
>```SQL
>SELECT title, genre FROM Movies WHERE length IN(90,130);

basically means does it equal 90 or does it equal 130
>[!warning]
>NOT similar to [[BETWEEN]]
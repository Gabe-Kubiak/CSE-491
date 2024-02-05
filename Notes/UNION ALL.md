- [[UNION]] performs a DISTINCT on the result set, eliminating any duplicate rows.
- UNION ALL does not remove duplicates, and it therefore faster to perform than [[UNION]]
>[!example]
> If I wanted the Artists and Album names, but duplicates were okay: 
> ```SQL
>  SELECT Artist.Name FROM Artist UNION ALL SELECT Album.Title FROM Album;

- UNION combines the result sets of two [[Query|Queries]]
- Column data types in the two [[Query|Queries]] must match
- UNION combines by column position rather than column name
>[!example]
>If we wanted all the names of Artists and Albums:
>```SQL
>SELECT Artist.Name FROM Artist UNION SELECT Album.Title FROM Album;

# ALSO SEE [[UNION ALL]]
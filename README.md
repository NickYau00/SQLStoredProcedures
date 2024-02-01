# SQL Stored Procedures - What They Are, Best Practices, Security, and More...
# Youtube Video by IAmTimCorey
```
CREATE PROCEDURE [new stored procedure name] AS
BEGIN
  SELECT [column1], [colomn2], [colomn3]
  FROM [table];
END
```
Add `SET nocount on;` to tell the SP not to return a count at the end.




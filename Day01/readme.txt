learned about sql case statement, length function substring, concatination techniques

1. learned about blind sql injection
2. Two ways to exploit sql injection
      1. exploiting blind SQL Injection by triggering conditional response
      2. Exploiting blind SQL injection by triggering conditional errors

learned SQL injection vulnerability neccessory steps:

1. gather parameters from the target and find the parameter that uses a query to fetch any data from the backend.
2. try to modify the query and cause an SQL error then after try to balance payload. ( use: ' , ;, #, @ etc) 
3. examine the database and Find out the type of valid SQL comment 
4. find the number of columns on the table
5. find the column which contains string value
6. find the name of the table,
7. find the name of the columns
8. retrieve contents from the columns

https://systemweakness.com/blind-sql-injection-with-conditional-errors-166be147f8c9
portswigger 
https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/07-Input_Validation_Testing/05-Testing_for_SQL_Injection

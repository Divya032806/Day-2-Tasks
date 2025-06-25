
This project demonstrates basic SQL operations such as creating a table, inserting data, updating values, handling nulls, filtering, and deleting records using a `users` table.
I have created and populated a simple users table and practiced INSERT, UPDATE, and DELETE operations, in MySQL. Handled NULL values and conditional deletions.
First created a database Demo, created table users and then inserted 3 datas initially then viewed using select * from users script.
Then updated age for Boby and Cary, then inserted a user with missing age for Dave. I updated Cary's email to NULL.
Then viewed using 
select * from users 
where email is NULL or age is NULL;
Last I deleted user 'Dave' and using where deleted age greater than 27.
Finally viewed select * from users.



### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
It is a highly stable database management system.  PostgreSQL is used as the primary data store or data warehouse for many web, mobile, geospatial, and analytics applications.

- What is the difference between SQL and PostgreSQL?
PostgreSQL is easy-to-use with a full stack of RDBMS database features and capabilities for handling data. It can be easily installed on Linux environments. SQL Server is a Relational Database Management System (RDBM) developed and operated by Microsoft.

- In `psql`, how do you connect to a database?
first we need to open psql server by `sudo service posgresql start` to run the `psql` server. Then we need to know the database name so we can use terminal. `psql database_name` to open the database.

- What is the difference between `HAVING` and `WHERE`?
`Where` clause is used to filter the records from a table that is based on a specified condition. `Having` clause is used to filter the record from the groups based on the specified condition.

- What is the difference between an `INNER` and `OUTER` join?
The inner join will keep only the information from both tables that's related to each other (in the resulting table). An outer join will also keep information that is not related to the other table in the resulting table.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
Left Outer Join is returns all the rows from the LEFT table and matching records between both the tables. Right Outer Join is returns all the rows from the RIGHT table and matching records between both the tables.

- What is an ORM? What do they do?
An object-relational mapper provides an object-oriented layer between relational databases and object-oriented programming languages without having to write SQL queries. It standardizes interfaces reducing boilerplate and speeding development time.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
An AJAX request is just an HTTP request made by JavaScript code. Browsers load web pages by sending requests to the server using HTTP. Each time a page loads, a request is made. JavaScript code can do the same thing, but without needing to reload the whole page.

- What is CSRF? What is the purpose of the CSRF token?
Cross site request forgery (CSRF), also known as XSRF, Sea Surf or Session Riding, is an attack vector that tricks a web browser into executing an unwanted action in an application to which a user is logged in. A successful CSRF attack can be devastating for both the business and user.

- What is the purpose of `form.hidden_tag()`?
The form. hidden_tag() template argument generates a hidden field that includes a token that is used to protect the form against CSRF attacks.
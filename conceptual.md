### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  - It is an object-relational database

- What is the difference between SQL and PostgreSQL?
  - SQL is only a relational database, meaning it is more limmited on the kinds of realtionships it can have.

- In `psql`, how do you connect to a database?
  - \c "data_base_name"

- What is the difference between `HAVING` and `WHERE`?
  - Where is to filter individual peices of data, and HAVING is to filter groups of data

- What is the difference between an `INNER` and `OUTER` join?
  - INNER join is the data from two tables where the data overlaps, and OUTER is where non of the data overlaps.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  - LEFT OUTER I believe refers to the first table in the comparison and RIGHT OUTER is the later comparison.

- What is an ORM? What do they do?
  - Object relational mapping and they make it easy to refer to tables that relate to one another through what looks like object oriented programs. 

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  -When requesting from an API from the server side all request are made to my server, thus hiding, on the client side, where the request is really being sent to. 

- What is CSRF? What is the purpose of the CSRF token?
  - Cross-Site Request Forgery tokens prevent bad actors from takeing advantage of a user that be authorized and making request to steal information

- What is the purpose of `form.hidden_tag()`?
    - This will hide the CSRF token from being displayed.
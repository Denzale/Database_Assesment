### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
PostgreSQL is an open-source, object-relational database management system (DBMS). It is known for its robustness, reliability, and adherence to industry standards. PostgreSQL, often referred to as simply "Postgres," offers advanced features and capabilities that make it a popular choice for a wide range of applications.

- What is the difference between SQL and PostgreSQL?
SQL is a language that provides a standardized way to interact with databases. It defines the syntax and semantics for querying, inserting, updating, and deleting data. PostgreSQL, on the other hand, is a specific RDBMS that implements the SQL language and provides additional features and functionality beyond what the SQL standard specifies.

- In `psql`, how do you connect to a database?

In the command line, type \c \<databasename\>\


- What is the difference between `HAVING` and `WHERE`?

he WHERE clause is used to filter rows from a result set based on a specific condition or set of conditions. It is applied during the query's execution and filters the rows before any grouping or aggregation takes place. The WHERE clause operates on individual rows.


The HAVING clause is used to filter the result set after the grouping and aggregation operations have been performed. It applies conditions to the grouped data and filters the groups based on those conditions. The HAVING clause operates on the grouped data.
- What is the difference between an `INNER` and `OUTER` join?

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

In a LEFT OUTER JOIN, all the rows from the left table (the table specified before the LEFT OUTER JOIN keyword) are included in the result set, regardless of whether there is a matching row in the right table. If there is no matching row in the right table, NULL values are used for the columns of the right table in the result set.

In a RIGHT OUTER JOIN, all the rows from the right table (the table specified before the RIGHT OUTER JOIN keyword) are included in the result set, regardless of whether there is a matching row in the left table. If there is no matching row in the left table, NULL values are used for the columns of the left table in the result set.

- What is an ORM? What do they do?

An ORM (Object-Relational Mapping) is a programming technique that allows developers to interact with a relational database using object-oriented programming concepts. It provides a layer of abstraction between the application code and the database, enabling developers to work with database entities as objects in their programming language.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?

  Execution Context
  Cross-Origin Requests
  Request Handling

- What is CSRF? What is the purpose of the CSRF token?

It is a security token sent to a client from the server so that it can be returned and verify that requests are being made by that server

- What is the purpose of `form.hidden_tag()`?

In Jinja, this hides the Flask form of CSRF tokens in the UI

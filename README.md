# mongoDB

## The Definition of CRUD
Within computer programming, the acronym CRUD stands for create, read, update and delete. These are the four basic functions of persistent storage. Also, each letter in the acronym can refer to all functions executed in relational database applications and mapped to a standard HTTP method, SQL statement or DDS operation.

## Benefits of CRUD
Instead of using ad-hoc SQL statements, many programmers prefer to use CRUD because of its performance. When a stored procedure is first executed, the execution plan is stored in SQL Server’s procedure cache and reused for all applications of the stored procedure.

When a SQL statement is executed in SQL Server, the relational engine searches the procedure cache to ensure an existing execution plan for that particular SQL statement is available and uses the current plan to decrease the need for optimization, parsing and recompiling steps for the SQL statement.

If an execution plan is not available, then the SQL Server will create a new execution plan for the query. Moreover, when you remove SQL statements from the application code, all the SQL can be kept in the database while only stored procedure invocations are in the client application. When you use stored procedures, it helps to decrease database coupling.

Furthermore, using CRUD operations helps to prevent SQL injection attacks. By utilizing stored procedures instead of string concatenation to build dynamic queries from user input data for all SQL Statements means that everything placed into a parameter gets quoted.

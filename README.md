Create a database called "sales" with a table called "orders"that contains the following columns:orders_id(int),customer_id(int),order_date(date),order_total(decimal).
CREATE DATABASE sales;
CREATE TABLE orders(
order_id INT,customers_id INT,order_date DATE,order_total DECIMAL(10,2) );
In this example ,we first create a database called "sales" using the 'CREATE DATABASE' statement.Then we switch to using that database with the 'USE'statement.
Next, we create a table called "orders" within the "sales"database. The table has the following columns:
'order_id':This column stores the unique identifier for each order and is of the integer data type ('INT').
'customers_id':This column stores the unique identifiers for each customers and is of the integers data type ('INT').
'order_data':This column stores the data when the order was placed and is of the data type('DATA').
'order_total':This column stores the total amount of the order and is of the decimal data type ('DECIMAL(10,2)'),allowing up to 10 digits with 2 decimal places.

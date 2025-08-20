1. Retrieve checkNumber, paymentDate, and amount from payments table
SELECT checkNumber, paymentDate, amount
FROM paymen

2. Retrieve orderDate, requiredDate, and status of 'In Process' orders, sorted by orderDate descending
SELECT orderDate, requiredDate, status
FROM orders
WHERE status = 'In Process'
ORDER BY orderDate DESC;

3. Retrieve firstName, lastName, and email of employees whose job title is 'Sales Rep', ordered by employeeNumber descending
SELECT firstName, lastName, email
FROM employees
WHERE jobTitle = 'Sales Rep'
ORDER BY employeeNumber DESC;

4. Retrieve all columns and records from offices table
SELECT *
FROM offices;

5. Retrieve product Name and quantityInStock from products table, sort by buyPrice ascending, limit to 5 records
SELECT productName, quantityInStock
FROM products
ORDER BY buyPrice ASC
LIMIT 5;
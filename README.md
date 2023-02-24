# SQL-Essentials-Bootcamp-assignment--LetsUpgrade
Assignment Answer

SELECT salesman.name AS "Salesman",
customer.cust_name, customer.city 
FROM salesman,customer 
WHERE salesman.city=customer.city;

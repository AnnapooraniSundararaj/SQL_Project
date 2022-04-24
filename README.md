# Sakila_SQL_Project 
You can download the Sakila database from https://dev.mysql.com/doc/index-other.html
The Sakila database is a nicely normalised database modelling a DVD rental store.

A set of MySQL queries to get data from the tables actor, address, category, city, country, customer, film, film actor, film category, inventory, language, payment, rental, staff, and store in the famous sakila schema. 

Queries_used
Data Definition Language Statements:
    ALTER
    DROP
    CREATE VIEW
    DROP VIEW   
Data Manipulation Language Statements:
    SELECT
    APPEND
    DELETE
    UPDATE
    JOIN
Aggregate Functions:
    SUM
    COUNT
    GROUP BY
    WHERE

Description of queries:

QS 1.1 => Query that lists each film, its category (Animation, Children, Classics, Comedy, Family, and Music), and the number of times it has been rented. 

QS 1.2 => Created a table with movie title and divided into 4 level using NTILE(4) of the rental duration for movies across all categories. 

QS 1.3 => Created a table with category, Rental length category and count where the count column is sorted first by category and rental duration category.

QS 2.1 => Using DATE_PART got the number of rental orders for each store fulfilled for that month and using JOIN joined store table & staff and JOIN rental and staff, and created a table with rental month, rental year, store ID and count rentals.

QS 2.2 => Concatenated first name and full name to customer name, generated month and year of the payment made by top 10 paying customers. 

QS 2.3 => Query to find out the difference across their monthly payments and compare the payments amounts in each successive month. 

Presentation 1 => Created a chart to display the most selled out category. 

Presentation 2 => Created a chart to display the top 10 customer shift overtime.

Presentation 3 => Created a chart to display the top 10 customers who rented the most dvds

Presentation 4 => Created a chart displaying the top paying cutomers is 2007.










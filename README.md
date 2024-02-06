# homework5
limit ve offset ödev 5

--SORU 1
SELECT * FROM film
WHERE title LIKE '%n'
ORDER BY length DESC
LIMIT 5 

--SORU 2
SELECT * FROM film
where title LIKE '%n'
order by length ASC
OFFSET 5
LIMIT 5

--SORU 3
SELECT * FROM customer
WHERE store_id=1
ORDER BY last_name DESC
LIMIT 4


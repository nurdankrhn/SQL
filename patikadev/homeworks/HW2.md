- List all columns from the film table where replacement_cost is greater than or equal to 12.99 and less than 16.99. (Use the BETWEEN … AND … structure.)<br>
`SELECT * FROM film 
WHERE replacement_cost BETWEEN 12.99 AND 16.99;`
<img width="1557" height="973" alt="image" src="https://github.com/user-attachments/assets/8aea7af9-9cf8-4e86-8dd3-042b497c1f20" />

- List the first_name and last_name columns from the actor table where first_name is 'Penelope', 'Nick', or 'Ed'. (Use the IN operator.)<br>
`SELECT first_name, last_name FROM actor 
WHERE first_name IN('Penelope', 'Nick','Ed');`
<img width="1571" height="969" alt="image" src="https://github.com/user-attachments/assets/52a31e22-e2f6-4582-ab78-ff4c5269c4f5" />

- List all columns from the film table where rental_rate is 0.99, 2.99, or 4.99 AND replacement_cost is 12.99, 15.99, or 28.99. (Use the IN operator.)<br>
`SELECT * FROM film 
WHERE rental_rate IN(0.99, 2.99, 4.99) AND replacement_cost IN(12.99, 15.99, 28.99);`
<img width="1568" height="973" alt="image" src="https://github.com/user-attachments/assets/bbe3c228-4f53-4edf-8a41-55a8ab17b417" />

Perform the following query scenarios on the dvdrental sample database:<br>

- From the film table, list the top 5 longest films (based on length) whose title ends with the letter 'n'.<br>
`SELECT * FROM film
WHERE title LIKE '%n'
ORDER BY length DESC
LIMIT 5;`
<img width="1563" height="972" alt="image" src="https://github.com/user-attachments/assets/9a4deaea-346c-414d-9316-f83309f44251" />

- From the film table, list the next 5 shortest films (positions 6, 7, 8, 9, 10) whose title ends with the letter 'n'.<br>
`SELECT * FROM film
WHERE title LIKE '%n'
ORDER BY length
OFFSET 5
LIMIT 10;`
<img width="1560" height="962" alt="image" src="https://github.com/user-attachments/assets/4c913394-6709-46ad-a8bc-4da11fa43d78" />

- From the customer table, when sorting by last_name in descending order, list the first 4 records where store_id = 1.<br>
`SELECT * FROM customer
WHERE store_id = 1
ORDER BY last_name DESC
LIMIT 4;`
<img width="1569" height="971" alt="image" src="https://github.com/user-attachments/assets/c4a78359-c8b8-4fea-b026-d25c9532c8d0" />

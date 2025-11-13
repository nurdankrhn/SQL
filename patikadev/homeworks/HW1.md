- List the data in the title and description columns from the film table.<br>
`SELECT title, description FROM film;`
<img width="1578" height="968" alt="image" src="https://github.com/user-attachments/assets/9dac89b0-b2af-44fe-9efd-476ad3be52fb" />

- List all columns from the film table where the length is greater than 60 AND less than 75. <br>
  `SELECT * FROM film WHERE length > 60 AND length < 75;`
  <img width="1575" height="973" alt="image" src="https://github.com/user-attachments/assets/4dc9b721-87e1-41fb-85c9-90c305d4177d" />

- List all columns from the film table where rental_rate is 0.99 AND replacement_cost is 12.99 OR 28.99. <br>
`SELECT * FROM film WHERE rental_rate = 0.99  AND replacement_cost  = 12.99 OR replacement_cost = 28.99;`
<img width="1569" height="984" alt="image" src="https://github.com/user-attachments/assets/f40bc499-ffe4-47c9-af6f-ee5468372db7" />

- In the customer table, what is the last_name of the customer whose first_name is 'Mary'? <br>
`SELECT first_name, last_name FROM customer WHERE first_name = 'Mary'; `
<img width="1562" height="614" alt="image" src="https://github.com/user-attachments/assets/4928fd36-1730-4f46-b869-91b0bcffb032" />

- List data from the film table where length is not greater than 50 and rental_rate is not 2.99 or 4.99. <br>
`SELECT * FROM film WHERE length > 50 AND NOT (rental_rate = 2.99 OR rental_rate = 4.99);`
<img width="1565" height="971" alt="image" src="https://github.com/user-attachments/assets/a061eae5-057d-46f7-b648-c435c36ff8c4" />


Perform the following query scenarios on the dvdrental sample database:<br>

- Write an INNER JOIN query that displays the city names (from the city table) together with their corresponding country names (from the country table).<br>
`SELECT city, country FROM city
INNER JOIN country ON country.country_id = city.country_id;`
<img width="1564" height="976" alt="image" src="https://github.com/user-attachments/assets/57209b98-578f-4ee4-b9f7-3848bc796b34" />

- Write an INNER JOIN query that displays the payment_id (from the payment table) together with the first_name and last_name values (from the customer table).<br>
`SELECT payment_id, first_name, last_name FROM customer
INNER JOIN payment ON payment.customer_id = customer.customer_id;`
<img width="1575" height="974" alt="image" src="https://github.com/user-attachments/assets/621d36bf-d5f5-4389-8f46-f67c164d787c" />

- Write an INNER JOIN query that displays the rental_id (from the rental table) together with the first_name and last_name values (from the customer table).<br>
  `SELECT rental_id, first_name, last_name FROM customer
INNER JOIN rental ON rental.customer_id = customer.customer_id;`
<img width="1576" height="976" alt="image" src="https://github.com/user-attachments/assets/61e6ca2d-0738-4556-b96f-3b2d33ebcdbd" />

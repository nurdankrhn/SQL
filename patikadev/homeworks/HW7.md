Perform the following query scenarios on the dvdrental sample database:<br>

- Group the films in the film table by their rating values.<br>
`SELECT rating, COUNT(rating) FROM film
GROUP BY rating;`
<img width="1558" height="968" alt="image" src="https://github.com/user-attachments/assets/a63af05d-f6ef-47ab-808b-94184258fb57" />

- When grouping the films in the film table by replacement_cost, list the replacement_cost values that have more than 50 films, along with their corresponding film counts.<br>
`SELECT replacement_cost, COUNT(*) FROM film
GROUP BY replacement_cost
HAVING COUNT(*) > 50;`
  <img width="1570" height="979" alt="image" src="https://github.com/user-attachments/assets/38f0638c-c2de-4311-be8c-4596ee22b85e" />

- In the customer table, what are the customer counts corresponding to each store_id value?<br>
`SELECT store_id, COUNT(*) FROM customer
GROUP BY store_id;`
<img width="1561" height="971" alt="image" src="https://github.com/user-attachments/assets/6f0a26bc-2e18-4816-859a-11136cf77fc9" />

- After grouping the city records in the city table by country_id, list the country_id that has the highest number of cities, along with the number of cities it contains.<br>
`SELECT country_id, COUNT(*) FROM city
GROUP BY country_id
ORDER BY COUNT(*) DESC
LIMIT 1;`
<img width="1567" height="974" alt="image" src="https://github.com/user-attachments/assets/dd77b40c-181e-40af-9442-6e76fcab5304" />

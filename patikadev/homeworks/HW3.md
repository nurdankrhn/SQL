Perform the following query scenarios on the dvdrental sample database.

- From the country table, list the country names that start with the character 'A' and end with the character 'a'. <br>
`SELECT country FROM country
WHERE country LIKE 'A%a';`
<img width="1573" height="971" alt="image" src="https://github.com/user-attachments/assets/93055719-bd58-41c8-a01d-5a0f464d9277" />

- From the country table, list the country names that are at least 6 characters long and end with the character 'n'.<br>

`SELECT country
FROM country
WHERE country LIKE '%n'
  AND LENGTH(country) <= 6;
`
<img width="1584" height="970" alt="image" src="https://github.com/user-attachments/assets/204ca20c-3878-40fb-84ad-74aa62f09be0" />

- From the film table, list the title of films that contain at least 4 occurrences of the letter 'T', case-insensitive.<br>
`SELECT title FROM film
WHERE title ILIKE '%t%t%t%t%';`
<img width="1560" height="982" alt="image" src="https://github.com/user-attachments/assets/3a803652-12eb-44ac-a077-527559ee2a84" />

- From the film table, list all columns for films where title starts with 'C', length > 90, and rental_rate = 2.99.<br>
`SELECT  * FROM film
WHERE title ILIKE 'C%' AND length > 90 AND rental_rate = 2.99;`
<img width="1572" height="970" alt="image" src="https://github.com/user-attachments/assets/2aadbc0b-1f15-40a2-922b-7663de65d95e" />

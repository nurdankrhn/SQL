Perform the following query scenarios on the dvdrental sample database:<br>

- What is the average value of the rental_rate column in the film table?<br>
`SELECT ROUND(AVG(rental_rate), 3) FROM film;`
<img width="1566" height="973" alt="image" src="https://github.com/user-attachments/assets/f1ef9246-0292-4448-bb49-e10d672d5aaf" />

- How many films in the film table start with the letter 'C'?<br>
`SELECT COUNT(*) FROM film
WHERE title LIKE 'C%';`
<img width="1569" height="965" alt="image" src="https://github.com/user-attachments/assets/3fbc1813-5159-4828-9fc6-719e1a602cb6" />

- Among the films in the film table where rental_rate = 0.99, what is the length (in minutes) of the longest film?<br>
`SELECT MAX(length) FROM film
WHERE rental_rate = 0.99;`
<img width="1558" height="971" alt="image" src="https://github.com/user-attachments/assets/f97cc81b-1510-44e3-9450-ee1dc97512d7" />

-For the films in the film table whose length is greater than 150 minutes, how many distinct replacement_cost values are there?<br>
`SELECT COUNT(DISTINCT replacement_cost) FROM film
WHERE length > 150 ;`
<img width="1572" height="965" alt="image" src="https://github.com/user-attachments/assets/7c3e006f-fac1-4714-9c0d-b6c3f7633ba7" />

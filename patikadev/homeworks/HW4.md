- List the distinct values in the replacement_cost column from the film table.<br>
`SELECT DISTINCT replacement_cost from film;`
<img width="1566" height="962" alt="image" src="https://github.com/user-attachments/assets/59e3d794-fb7f-474c-bad4-be941650871c" />

- How many distinct values exist in the replacement_cost column of the film table?<br>
`SELECT COUNT (DISTINCT replacement_cost) from film;`
<img width="1567" height="976" alt="image" src="https://github.com/user-attachments/assets/d2ab0031-a2bf-416c-a25e-308f2e031701" />

- How many film titles (title) start with the letter 'T' and also have a rating equal to 'G'?<br>
`SELECT COUNT (*) from film
WHERE title LIKE  'T%' AND rating = 'G';`
<img width="1569" height="969" alt="image" src="https://github.com/user-attachments/assets/48643573-1ced-48a6-ad1f-239c9b766146" />

- How many countries (country) in the country table have names that are exactly 5 characters long?<br>
`SELECT COUNT(*) FROM country
WHERE LENGTH(country) = 5;`
<img width="1572" height="968" alt="image" src="https://github.com/user-attachments/assets/281d26fd-fa3a-48e4-8a1c-bc1e83885952" />

- How many city names (city) in the city table end with the letter 'R' or 'r'?<br>
`SELECT COUNT(*) FROM city
WHERE city ILIKE '%R';`
<img width="1568" height="971" alt="image" src="https://github.com/user-attachments/assets/1fe0a78e-a7e4-4745-8270-630e34553f89" />

# SQL Queries for City Data Tasks

1️⃣ List all Canadian cities and their populations
```
SELECT city_name, population
FROM cities
WHERE country = 'Canada';
```
2️⃣ Order all the cities in the United States by their latitude from north to south
```
SELECT city_name, latitude
FROM cities
WHERE country = 'United States'
ORDER BY latitude DESC;
```
3️⃣ List all the cities west of Chicago, ordered from west to east
```
SELECT city_name, longitude
FROM cities
WHERE longitude < (
    SELECT longitude
    FROM cities
    WHERE city_name = 'Chicago' AND country = 'United States'
)
ORDER BY longitude ASC;
```
 4️⃣ List the two largest cities in Mexico (by population)
 ```
SELECT city_name, population
FROM cities
WHERE country = 'Mexico'
ORDER BY population DESC
LIMIT 2;
```
5️⃣ List the third and fourth largest cities (by population) in the United States and their population
```
SELECT city_name, population
FROM cities
WHERE country = 'United States'
ORDER BY population DESC
LIMIT 2 OFFSET 2;
```

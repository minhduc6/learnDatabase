Câu 1 :
SELECT title,rating,special_features from film  
where (rating = 'R' or rating = 'NC17') and special_features LIKE '%Trailers%'

Câu 2 :
SELECT title,length from film
where length < 70 and length > 100
ORDER BY length ASC

Câu 3 :
SELECT \* from actor
where first_name LIKE '%B'
ORDER BY last_name ASC

Câu 4 :
SELECT \* from film
where title NOT LIKE '%LIFE%' and description NOT LIKE '%LIFE%' and rating NOT LIKE 'PG'
ORDER BY length DESC

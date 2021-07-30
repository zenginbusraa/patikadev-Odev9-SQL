1. soru : city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

`` SELECT city.city, country.country
FROM city
JOIN country ON country.country_id = city.country_id; ``

2. soru : customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

`` SELECT customer.first_name, customer.last_name, payment.payment_id
FROM customer
JOIN payment ON payment.customer_id = customer.customer_id; ``

3. soru : customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

`` SELECT customer.first_name  , customer.last_name , rental.rental_id 
FROM customer
JOIN rental ON rental.customer_id = customer.customer_id; ``
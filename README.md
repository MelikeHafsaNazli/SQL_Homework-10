# SQL_Homework-10

Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.

1. city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz LEFT JOIN sorgusunu yazınız.

		SELECT city, country FROM city LEFT JOIN country ON country.country_id = city.country_id;

2. customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz RIGHT JOIN sorgusunu yazınız.

		SELECT customer, payment FROM customer RIGHT JOIN payment ON payment.customer_id = customer.customer_id;

3. customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz FULL JOIN sorgusunu yazınız.

		SELECT customer, rental FROM customer FULL JOIN rental ON rental.customer_id = customer.customer_id;


### Patika.dev linki: https://app.patika.dev/melikehafsa

1. SELECT title, description FROM film;

![](./images/1.png)

2. SELECT \* FROM film
   WHERE length > 60 AND length < 75;

   ![](./images/2.png)

3. SELECT \* FROM film
   WHERE rental_rate = 0.99 AND (replacement_cost = 12.99 OR replacement_cost = 28.99);

   ![](./images/3.png)

4. SELECT first_name, last_name FROM customer
   WHERE first_name = 'Mary';

   ![](./images/4.png)

5. SELECT \* FROM film
   WHERE length <= 50 AND (rental_rate <> 2.99 AND rental_rate <> 4.99);

   ![](./images/5.png)

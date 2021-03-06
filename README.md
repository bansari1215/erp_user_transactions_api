# PayPalCodingTest

Submitted by: **Bansari Patel**

## Techonologies: Spring Boot, Spring MVC, Spring JPA, Java 8, H2 Database, Maven, jUnit, Mockito, Swagger, Git


## A spring-based application which provides REST APIs for ##


- [x] Providing information on various types of payment transactions (Invoicing, billing, subscriptions) done on a specific day by all users 
</br> http://localhost:8083/paypal/userTransactions?date=2020-05-12

- [x] Providing information specifically to a particular user ID (you can define a user id however you would want to. For eg: email, account number, mobile, etc.) on the basis of year, month, day, hours. 
</br> http://localhost:8083/paypal/userTransactions?user=bansari@gmail.com
</br> http://localhost:8083/paypal/userTransactions?month=05&hour=11&year=2020&day=12&user=bansari@gmail.com

- [x] Providing information based on particular transaction type for a particular user (for eg: invoices created by a specific user Jim) 
</br> http://localhost:8083/paypal/userTransactions?user=bansari@gmail.com&transactionType=Invoice

- [x] User should be able to query on information pertaining to that user transactions alone. The system should not provide data of another user when queried.
- [x] Write unit tests for each service
- [x] H2 Database configuration for database simulation
- [x] MySQL database configuration included in the project to display database connectivity
- [x] Swagger for documentation : http://localhost:8083/swagger-ui/index.html


I really enjoyed this test. I am going to keep updating this project and add additional functionalities. 

Thank you so much for giving me this opportunity.

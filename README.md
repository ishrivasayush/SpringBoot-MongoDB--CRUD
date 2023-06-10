# SpringBoot-MongoDB--CRUD
Overview of Spring Boot MongoDB CRUD example
I will build a Spring Boot MongoDB Rest CRUD API for a Tutorial application in that:

Each Tutorial has id, title, description, published status.
Apis help to create, retrieve, update, delete Tutorials.
Apis also support custom finder methods such as find by published status or by title.
These are APIs that we need to provide:

Methods	Urls	Actions
POST	/api/tutorials	create new Tutorial
GET	/api/tutorials	retrieve all Tutorials
GET	/api/tutorials/:id	retrieve a Tutorial by :id
PUT	/api/tutorials/:id	update a Tutorial by :id
DELETE	/api/tutorials/:id	delete a Tutorial by :id
DELETE	/api/tutorials	delete all Tutorials
GET	/api/tutorials/published	find all published Tutorials
GET	/api/tutorials?title=[keyword]	find all Tutorials which title contains keyword
– We make CRUD operations & finder methods using Spring Data MongoDB.
– Rest Controller will be created with the help of Spring Web MVC.

Technology
Java 17 / 11 / 8
Spring Boot 3 / 2 (with Spring Web MVC, Spring Data MongoDB)
MongoDB
Maven

# Sporty-Shoes-Store


This project aims to design and develop an E-commerce Website for Sporty Shoes using Java Spring MVC. It enables users to buy and search the available products and make admin to manage the store within the system. It was developed as a project of Phase-3 for the Implement Frameworks the DevOps way Course.

## Product Backlog:
1.	Create database and tables.
2.	Add all dependencies to the Maven project.
3.	Connect the database to the project.
4.	Create the models’ classes.
5.	Create the data access object classes using Hibernate.
6.	Create login and register pages.
7.	Show all products to the home page.
8.	Add products to the cart.
9.	Show user’s cart.
10.	Create user’s update page.
11.	Enable the admin to add a new product.
12.	Enable the ability to search for a specific product.
13.	Make the admin able to update and remove a product.
14.	Make the admin manage the users.
15.	Make the  admin manage the orders.
16.	Add CSS file and use Bootstrap to format the pages.
17.	Debug and test the project.


## Technologies and tools Used
•	Spring MVC: to build web applications as it follows the Model-View-Controller design pattern. 

•	JSP: to handle the presentation view.

•	Hibernate: to simplify the development and the interaction with the database.

•	CSS: to format the contents.

•	Bootstrap: to use some CSS and JavaScript designs.

•	Maven: to manage the project.

•	Eclipse: to write and run the code.

•	phpMyAdmin: to administrate and manage the database manually.

•	Tomcat: to run and deploy servlet application.

## Core concepts used in the project. 

Object-Oriented Programming (OOP):
Explain the fundamental principles of OOP, such as classes, objects, inheritance, and polymorphism, and how they are applied in your Spring Boot project.

Spring Boot Basics:
Discuss key Spring Boot concepts like Inversion of Control (IoC), Dependency Injection, and the Spring Boot starter projects.

Spring Framework Annotations:
Describe the usage of annotations like @Controller, @Service, @Repository, and @RestController for defining components and handling HTTP requests.

Hibernate and JPA:
Explain how Hibernate is used for object-relational mapping (ORM) in the project, and introduce Java Persistence API (JPA) for managing database entities.

Spring Security:
Discuss the application of Spring Security for implementing user authentication, including admin login and password management.

Admin Panel:
Explain the need for an admin panel, including its role and access control via Spring Security.

Password Management:
Describe how users, including admins, can change their passwords securely.

Product Management:
Detail the use of Hibernate and JPA for managing product data, including categorization.

User Management:
Discuss how user data is stored and retrieved, as well as the ability to search for users.

Purchase Reports:
Explain the data structure for purchase reports and how filtering by date and category is implemented, possibly using Spring Data JPA.


## How to run the program
•	clone project

o	clone git : git clone https://github.com/Boigantso/Sporty-Shoes-Store

•	Import the “main\webapp\resources\database\sporty-shoes.sql” file to your database administration tool.

•	Go to “main\webapp\WEB-INF\sporty-shoes-servlet.xml” file, open it.

•	Edit some values of the database’ properties such as username, password and driverClassName to be suit to your database administration tool.

•	Now run program on a server.

•	To login as an admin, you have to enter admin for both username and password.





# *CS 204: Back-end Development with Spring Framework (Final)*
## Student Management System

Simple and fully responsive Student Management System using Spring Boot, Thymeleaf and PostgresSQL database...

It works with 4 tables: *students, role, users-roles, user-table*.
Only admin can add or delete students;
## - login: **admin**
## - password: **Admin2022**

Students can register and see their marks, if they exist in table.

# Tools and technologies used:
- *Java 11*
- *Spring Boot*
- *Spring Data JPA (Hibernate)*
- *PostgresSQL*
- *Thymeleaf*
- *Bootstrap 4*


## ER Diagram of DB

![image](images/er_diagram.jpg)

## *Some screenshots*

![image](images/screenshot1.JPG)
![image](images/screenshot2.JPG)
![image](images/screenshot3.JPG)
![image](images/screenshot4.JPG)

# Deployment process

 ## We deployed our project to AWS. 

## Firstly we connected our database to RDS.

![rds](https://user-images.githubusercontent.com/95084923/208440811-dd5637e5-898e-46a4-ac14-5fcb0b278370.png)


## Then we created an environment for our web server. While creating the environment Elastic Beanstalk created and launched an instance.

![ebt](https://user-images.githubusercontent.com/95084923/208440856-545b5545-9c6e-46b6-b906-f1d954d1377e.png)


![ec2](https://user-images.githubusercontent.com/95084923/208440910-cd9985ee-518b-4266-9db6-d9fb9ae48a48.png)

## We connected to the instance and deployed our files to Elastic Beanstalk.

## Also we attached the instance to Elastic Load Balancer(ELB) which automatically distributes incoming application traffics.

![lb](https://user-images.githubusercontent.com/95084923/208440983-d8b1f261-a75d-4252-a797-2846b715b2f7.png)


## You can see our web-site

![dns](https://user-images.githubusercontent.com/95084923/208441029-c433533f-fda7-4725-a9f6-154d9f456f9d.png)

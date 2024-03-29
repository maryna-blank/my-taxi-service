# Taxi Service

## Summary
This is a project that simulates taxi service web application. It was implemented using SOLID principles and n-tier architecture. 
It supports functionality such as registration and authentication, filtration, authorization, work with data and logging.
Register as a driver, then get access to creating, deleting and viewing all the cars, manufacturers and drivers within a database.
You can assign a driver to a specific car and view your current cars. 
Driver behaves as a User in here.

## Functionality
- Authorize as a driver to get access
- Create, get and delete one or all of the certain manufacturers/cars/drivers
- Add a driver to a car
- Get the list of your cars
- Keep a log of your actions

## Project Structure
- Controllers for cars, drivers and manufacturers
- Dao level with CRUD operations for a direct work with a database
- Service level containing business logic
- Filtration level for authentication and authorization

## Technologies Used
- Apache Tomcat (to run app locally)
- JDBC
- MySQL
- Tomcat 9.0.50 (local server)
- Servlet
- JSTL
- JSP
- Log4j
- Maven Checkstyle Plugin

## Instructions on Start
Before doing anything, make sure you have all the necessary technologies installed and a database (resources -> init_db.sql).
Set you db connection parameters in ConnectionUtil class.

1. First, you'll need to get registered as a new Driver on /drivers/add page.
2. Then, log in using previously created username and password on page /login.
3. Get access to a full functionality.

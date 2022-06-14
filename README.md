# my-taxi-service

## Summary
This is a simple project that simulates work within taxi service database. 
Driver behaves as a User in here.

## Functionality
- Create, get and delete one or all of the certain manufacturers/cars/drivers
- Add a driver to a car
- Get the list of your cars
- This version is for local usage only

## Project Structure
- Controllers for cars, drivers and manufacturers
- Models of car, driver and manufacturer
- Dao level with CRUD operations
- Service level containing business logic
- Custom exceptions, annotations, web filter and pages

## Technologies Used
- Intellij Idea Ultimate
- Java
- JDBC
- MySQL
- Tomcat 9.0.50 (local server)

## Instructions on Start
Before doing anything, make sure you have all the necessary technologies installed and a database (resources -> init_db.sql). 
Establish connection via ConnectionUtil with your parameters.

1. First, you'll need to get registered as a new Driver on /drivers/add page.
2. Then, log in using previously created username and password on page /login.
3. Get access to a full functionality.

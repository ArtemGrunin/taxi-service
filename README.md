# ![][1] Taxi-service ![][1]

- [Description](#Description)
- [Technologies](#Technologies)
- [How to run app](#How-to-run-app)
- [Author](#Author)

### Description
This web application is a simple taxi service 
with authentication, registration, and CRUD operations. 
It is developed using SOLID 
principles and the Dependency Injection pattern. 
The main features include authentication, 
CRUD operations for cars and drivers, 
logical layer separation, and authentication filtering. 
The application is user-friendly, 
adheres to programming standards, 
and provides a convenient user interface for users.
### Features
- Registration and login
- Create new Driver / Car / Manufacturer
- Display all Drivers / Cars / Manufacturers
- Add Driver to Car
- Display all Cars by Driver
- Soft delete Driver / Car / Manufacturer
### Technologies
| Technology | Version |
|------------|---------|
| JDK        | 17      |
| Maven      | 3.8.7   |
| TomCat     | 9.0.78  |
| MySQL      | 8.0.32  |
| Servlet    | 4.0.1   |
| JSTL       | 1.2     |
### How to run app
- ✅Clone the project from GitHub
- ✅Use /resources/init_db.sql to create a schema and tables
- ✅Configure /util/ConnectionUtil.java with your own URL, username, password and JDBC driver
- ✅Configure Tomcat server (❗it is recommended to use version 9.0.78❗)
- ✅Run and enjoy the program
### Author
Artem Grunin

[1]: (https://st2.depositphotos.com/4969687/7430/i/600/depositphotos_74307523-stock-photo-3d-taxi-logo-yellow-and.jpg)
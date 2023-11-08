Spring Boot MySQL CRUD Application with Basic Authentication
This project is a simple Spring Boot application that demonstrates how to create a basic CRUD (Create, Read, Update, Delete) API using MySQL as the database and Basic Authentication for securing the API endpoints. It is a great starting point for developers who want to build RESTful web services with Spring Boot while leveraging the power of a MySQL database and adding a layer of basic security.

Features
CRUD Operations: The application supports Create, Read, Update, and Delete operations for a User entity. Users can be added, retrieved, updated, and deleted through a set of API endpoints.

MySQL Database: The project is configured to work with a MySQL database. The database schema is automatically updated based on the entity classes.

Basic Authentication: API endpoints are secured with Basic Authentication, ensuring that only authorized users can access and modify the data.

Lombok Integration: The project also demonstrates the use of Lombok to reduce boilerplate code. Lombok annotations are used to generate getter, setter, and other commonly used methods.

Getting Started
To get started with this project, follow these steps:

Clone this repository to your local machine.

Configure the MySQL database by updating the application.yml file with your database credentials and schema details.

Build and run the Spring Boot application using your preferred IDE or the command line.

Access the API at http://localhost:8080/api/users, and use Basic Authentication to secure the endpoints.

Explore and customize the code to fit your specific requirements.

Technologies Used
Spring Boot
Spring Data JPA
Spring Security
MySQL
Lombok
Contributing
Contributions are welcome! If you find any issues or have ideas for improvements, please open an issue or submit a pull request. We appreciate your feedback and contributions to make this project better.

License
This project is licensed under the MIT License. See the LICENSE file for details.

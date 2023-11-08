<!DOCTYPE html>
<html>
<head>
    <title>Spring Boot MySQL CRUD with Basic Authentication</title>
</head>
<body>
    <h1>Spring Boot MySQL CRUD Application with Basic Authentication</h1>

    <p>This project is a simple Spring Boot application that demonstrates how to create a basic CRUD (Create, Read, Update, Delete) API using MySQL as the database and Basic Authentication for securing the API endpoints. It is a great starting point for developers who want to build RESTful web services with Spring Boot while leveraging the power of a MySQL database and adding a layer of basic security.</p>

    <h2>Features</h2>
    <ul>
        <li><strong>CRUD Operations:</strong> The application supports Create, Read, Update, and Delete operations for a <code>User</code> entity. Users can be added, retrieved, updated, and deleted through a set of API endpoints.</li>
        <li><strong>MySQL Database:</strong> The project is configured to work with a MySQL database. The database schema is automatically updated based on the entity classes.</li>
        <li><strong>Basic Authentication:</strong> API endpoints are secured with Basic Authentication, ensuring that only authorized users can access and modify the data.</li>
        <li><strong>Lombok Integration:</strong> The project also demonstrates the use of Lombok to reduce boilerplate code. Lombok annotations are used to generate getter, setter, and other commonly used methods.</li>
    </ul>

    <h2>Getting Started</h2>
    <ol>
        <li>Clone this repository to your local machine.</li>
        <li>Configure the MySQL database by updating the <code>application.yml</code> file with your database credentials and schema details.</li>
        <li>Build and run the Spring Boot application using your preferred IDE or the command line.</li>
        <li>Access the API at <code>http://localhost:8080/api/users</code>, and use Basic Authentication to secure the endpoints.</li>
        <li>Explore and customize the code to fit your specific requirements.</li>
    </ol>

    <h2>Technologies Used</h2>
    <ul>
        <li>Spring Boot</li>
        <li>Spring Data JPA</li>
        <li>Spring Security</li>
        <li>MySQL</li>
        <li>Lombok</li>
    </ul>

    <h2>Contributing</h2>
    <p>Contributions are welcome! If you find any issues or have ideas for improvements, please open an issue or submit a pull request. We appreciate your feedback and contributions to make this project better.</p>

    <h2>License</h2>
    <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.</p>

    <h2>Contact</h2>
    <p>If you have any questions or need further assistance, please feel free to contact <a href="mailto:youremail@example.com">Your Name</a>.</p>
</body>
</html>

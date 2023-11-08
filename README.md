# Spring Boot MySQL CRUD Application with Basic Authentication

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.5.4-brightgreen)
![MySQL](https://img.shields.io/badge/MySQL-8.0.25-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

This project is a simple Spring Boot application that demonstrates how to create a basic CRUD (Create, Read, Update, Delete) API using MySQL as the database and Basic Authentication for securing the API endpoints. It is a great starting point for developers who want to build RESTful web services with Spring Boot while leveraging the power of a MySQL database and adding a layer of basic security.

## Features

- **CRUD Operations**: The application supports Create, Read, Update, and Delete operations for a `User` entity. Users can be added, retrieved, updated, and deleted through a set of API endpoints.

- **MySQL Database**: The project is configured to work with a MySQL database. The database schema is automatically updated based on the entity classes.

- **Basic Authentication**: API endpoints are secured with Basic Authentication, ensuring that only authorized users can access and modify the data.

- **Lombok Integration**: The project also demonstrates the use of Lombok to reduce boilerplate code. Lombok annotations are used to generate getter, setter, and other commonly used methods.

## Table of Contents

- [Getting Started](#getting-started)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Getting Started

To get started with this project, follow these steps:

1. **Clone this repository to your local machine**:

    ```shell
    git clone https://github.com/yourusername/spring-boot-mysql-crud.git
    ```

2. **Configure the MySQL database** by updating the `application.yml` file with your database credentials and schema details.

3. **Build and run the Spring Boot application** using your preferred IDE or the command line.

4. **Access the API** at `http://localhost:8080/api/users`, and use Basic Authentication to secure the endpoints.

5. **Explore and customize the code** to fit your specific requirements.

## Usage

<h1>API Documentation</h1>

    <h2>Create User</h2>
    <p><strong>Endpoint:</strong> <code>POST /api/users</code></p>
    <p><strong>Description:</strong> Create a new user.</p>
    <p><strong>Request Body:</strong></p>
    <pre>
    {
      "name": "John Doe",
      "email": "john.doe@example.com"
    }
    </pre>
    <p><strong>Response:</strong></p>
    <p><strong>Status Code:</strong> <code>201 Created</code></p>
    <p><strong>Response Body:</strong></p>
    <pre>
    {
      "id": 1,
      "name": "John Doe",
      "email": "john.doe@example.com"
    }
    </pre>

    <h2>Get All Users</h2>
    <p><strong>Endpoint:</strong> <code>GET /api/users</code></p>
    <p><strong>Description:</strong> Retrieve a list of all users.</p>
    <p><strong>Response:</strong></p>
    <p><strong>Status Code:</strong> <code>200 OK</code></p>
    <p><strong>Response Body:</strong></p>
    <pre>
    [
      {
        "id": 1,
        "name": "John Doe",
        "email": "john.doe@example.com"
      },
      {
        "id": 2,
        "name": "Alice Johnson",
        "email": "alice.j@example.com"
      }
    ]
    </pre>

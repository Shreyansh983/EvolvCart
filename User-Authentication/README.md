# User and Authentication Service

This service is a part of the EvolvCart platform. It handles user registration, login, authentication, and authorization functionalities for the application. The service ensures secure user management and access control for the entire platform.

## Features

- **User Registration**: Allows new users to create an account.
- **User Login**: Authenticates users and provides access tokens.
- **Password Encryption**: Ensures secure storage and transmission of passwords.
- **JWT Token Authentication**: Implements JWT (JSON Web Token) for session management.
- **Role-Based Access Control (RBAC)**: Grants different access levels based on user roles (e.g., Admin, Customer).

## Technology Stack

- **Spring Boot**: For building the REST API.
- **JWT (JSON Web Tokens)**: For authentication and authorization.
- **Spring Security**: For securing the API endpoints.
- **Spring Data JPA**: For interacting with the database.
- **PostgreSQL**: For database management.
- **Lombok**: For reducing boilerplate code.

## Architecture

The service follows a microservices architecture with the following components:

- **Controller**: Exposes API endpoints for user operations.
- **Service**: Contains business logic for user and authentication management.
- **Repository**: Manages user data persistence and retrieval from the database.
- **Security Config**: Configures Spring Security for user authentication and authorization.
- **DTOs**: Data Transfer Objects for secure data exchange between services.

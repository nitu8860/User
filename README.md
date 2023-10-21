# User Management Application

This is a simple Spring Boot application that demonstrates user management functionalities such as creating, reading, updating, and deleting user records. It also includes basic security configurations.

## Features

- Create users
- Read user data
- Update user data
- Delete specific attributes of user data
- Delete user records completely

## Dependencies

- Spring Boot
- Spring Data JPA
- Spring Security
- Lombok (for boilerplate reduction)

## Endpoints
### Create User
- Endpoint: POST /users
- Request Body: JSON representing user details (username, email, password)

### Read User Data
- Endpoint: GET /users/{id}
- Path Variable: id - The ID of the user

### Update User Data
- Endpoint: PUT /users/{id}
- Path Variable: id - The ID of the user
- Request Body: JSON representing updated user details (username, email)

### Delete User Attribute
- Endpoint: PATCH /users/{id}
- Path Variable: id - The ID of the user
- Request Parameter: attribute - The attribute to delete (e.g., "username" or "email")

### Delete User
- Endpoint: DELETE /users/{id}
- Path Variable: id - The ID of the user

### Security Configuration
The application uses Spring Security for basic authentication. To access the endpoints, we will need to provide valid credentials.


## Summary
The Spring Boot User Management Application is a straightforward yet powerful Spring Boot application designed to showcase user management functionalities. It provides a range of operations, including creating, reading, updating, and deleting user records. The application is fortified with basic security configurations to ensure controlled access.
  

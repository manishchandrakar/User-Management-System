# User Management System

## Overview

This project is a Java Spring Boot application developed for the User Management  company to manage users in the ABC information system. The system provides basic CRUD operations (Create, Read, Update, Delete) for user entities with additional attributes such as Role, Position, and Password.

## Author

- **Author Name:** Manish Chandrakar
- **Email:** manishchandrakar2001@gmail.com

## Preview

[Preview Page](https://drive.google.com/file/d/1DDRoz4IqhzASnIUKS5I_kiGsVnvJ0nOw/view?usp=sharing)

## Technologies Used

- **Backend:** Java Spring Boot
- **Frontend:** React (to be implemented)
- **Database:**  MySQL

## System Architecture

The system follows a modular architecture with separate components for business logic, entities, JPA persistencies, and controllers.

### Flowchart

![System Flowchart]
+-----------------------+
|    Start of System    |
+-----------------------+
          |
          V
+-----------------------+
|   User Selects       |
|   Operation (CRUD)    |
+-----------------------+
          |
          V
+-----------------------+
|   Operation Selected  |
|   (Create, List, Edit, |
|   Delete)              |
+-----------------------+
          |
          V
+-----------------------+
|      Create User      |
|       Operation       |
+-----------------------+
          |
          V
+-----------------------+
|   Collect User Data   |
|   (Username, Password,|
|   Roles, Position)     |
+-----------------------+
          |
          V
+-----------------------+
|   Validate Input Data |
|   (e.g., Password      |
|   Strength, Mandatory  |
|   Fields)              |
+-----------------------+
          |
          V
+-----------------------+
|   Save User to        |
|   Database (JPA)      |
+-----------------------+
          |
          V
+-----------------------+
|     List Users        |
|       Operation       |
+-----------------------+
          |
          V
+-----------------------+
|   Retrieve Users from  |
|   Database (JPA)      |
+-----------------------+
          |
          V
+-----------------------+
|   Display User List   |
|   in UI               |
+-----------------------+
          |
          V
+-----------------------+
|      Edit User        |
|       Operation       |
+-----------------------+
          |
          V
+-----------------------+
|   Retrieve User from  |
|   Database (JPA)      |
+-----------------------+
          |
          V
+-----------------------+
|   Update User Data    |
|   in UI               |
+-----------------------+
          |
          V
+-----------------------+
|   Save Updated User   |
|   to Database (JPA)   |
+-----------------------+
          |
          V
+-----------------------+
|      Delete User      |
|       Operation       |
+-----------------------+
          |
          V
+-----------------------+
|   Confirm Deletion    |
|   in UI               |
+-----------------------+
          |
          V
+-----------------------+
|   Remove User from    |
|   Database (JPA)      |
+-----------------------+
          |
          V
+-----------------------+
|    End of System      |
+-----------------------+


## Requirements

- Create users with attributes: Username, Password, Roles (Administrator, Support, Assistant), Position (Auditor, Administrator, Developer, Manager).
- Passwords must not be visible.
- Basic CRUD operations for users.
- A user can have multiple roles but only one position.

## Deliverables

1. **Source Code:**
   - The complete source code for the Java Spring Boot application.
   - Separate packages for business logic, entities, JPA persistencies, and controllers.

2. **Entity-Relationship Model:**
   - An ER model illustrating the relationships between entities.

3. **Flowchart:**
   - A flowchart representing the flow of the system as described in the README.

4. **Java Classes:**
   - Business logic classes handling user operations.
   - Entity classes representing the data model.

5. **JPA Persistencies and JPQL Queries:**
   - Implementation of JPA persistencies for database interactions.
   - JPQL queries for relevant operations.

6. **Design for the Screen(s):**
   - Screenshots or design mockups for the user interface.

7. **Postman or Swagger Documentation:**
   - Documentation for API endpoints using Postman or Swagger.

## Implementation

- The backend is developed using Java Spring Boot, providing RESTful APIs for user operations.
- The frontend is to be implemented using React or Angular (not included in this repository).
- Database interactions are handled using JPA with support for PostgreSQL or MySQL.

## Improvements

- **Security Enhancement:**
  - Implement password encryption and hashing for improved security.
  
- **Frontend Enhancement:**
  - Enhance the user interface with a responsive design.
  
- **Logging:**
  - Implement logging for tracking system activities and debugging.


# Restful API Project

**Project Overview:** This project is a RESTful API for managing items.

## Technologies Used

- **Technology 1:** Java
- **Technology 2:** Spring Boot
- **Technology 3:** PostgreSQL
- **Technology 4:** Maven

## Key Features

- **Feature 1:** CRUD operations for managing items.
- **Feature 2:** Secure authentication using JWT.
- **Feature 3:** Data storage in a PostgreSQL database.

## Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine.
2. Configure your PostgreSQL database in `application.properties`.
3. Build the project using Maven: `mvn clean install`.
4. Run the application: `java -jar target/api-restful-basica-0.0.1-SNAPSHOT.jar`.

## Usage

To use the API, follow these steps:

1. Register or log in using the provided endpoints.
2. Use the authenticated endpoints to manage items.

Example API Requests:

- Create a new item:
  ```shell
  POST /api/items
  {
    "name": "Sample Item",
    "description": "A sample item for testing"
  }


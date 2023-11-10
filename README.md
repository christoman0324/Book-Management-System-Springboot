# Book Management System

This is a robust RESTful API for managing books and their authors. It includes features such as CRUD operations for both authors and books, searching books by title or author name, JWT authentication, and more.

## Prerequisites

Before you begin, make sure you have the following installed:

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Getting Started

Follow these steps to set up and run the Book Management System using Docker Compose:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/christoman0324/Book-Management-System-Springboot.git
   cd Book-Management-System-Springboot
   ```

2. **Build the Docker images:**

   ```bash
   docker compose build
   ```

3. **Start the services:**

   ```bash
   docker compose up
   ```

This will start the Book Management System, including the API, the H2 database, and other required services.

**Access the API and documentation:**

 - The API will be available at http://localhost:8080.
 - The Swagger documentation will be available at http://localhost:8080/swagger-ui.html.

To stop the services, press Ctrl + C in the terminal where Docker Compose is running, and then run:

   ```bash
   docker compose down
   ```

#CRUD Application

This is a simple CRUD (Create, Read, Update, Delete) application built using Spring Boot framework. It provides RESTful APIs to perform CRUD operations on a collection of books.



Features:

Create Book: Add a new book to the collection.
Read Books: Retrieve all books or get details of a specific book by its ID.
Update Book: Update information of an existing book.
Delete Book: Remove a book from the collection.

Technologies Used:

Java
Spring Boot
Spring Data JPA
H2 Database (in-memory)
Lombok

Getting Started:

Prerequisites
Java Development Kit (JDK) installed on your system
Maven or Gradle installed for dependency management (if not using an IDE with built-in support)
Installation


Maven
mvn clean install

Gradle
gradle clean build
Configuration
The application can be configured via the application.properties file located in the src/main/resources directory. Configuration options include:

Server port
Data source URL, driver class, username, and password
JPA settings
H2 console settings
Usage
Once the application is running, you can use any REST client (e.g., Postman) to interact with the provided endpoints (see Endpoints). You can also access the H2 console for database management.

Endpoints
GET /getAllBooks: Retrieve all books.
GET /getBookById/{id}: Retrieve a book by its ID.
POST /addBook: Add a new book.
POST /updateBookById/{id}: Update a book by its ID.
DELETE /deleteBookById/{id}: Delete a book by its ID.
Database
The application uses an H2 in-memory database for storing book data. You can access the H2 console for database management by navigating to /h2 path.

Contributing
Contributions are welcome! If you have any ideas, suggestions, or improvements, please open an issue or create a pull request.

License
This project is licensed under the MIT License.

Feel free to customize this README according to your project's specific details and requirements. Let me know if you need further assistance!

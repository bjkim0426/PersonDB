Demo Spring Boot CRUD API

This project is a basic CRUD (Create, Read, Update, Delete) API built with Spring Boot. It demonstrates a simple RESTful API for managing a list of "Person" entities, showcasing key features of Spring such as dependency injection, validation, and the use of annotations like @RestController, @Service, @Repository, and @Autowired.

---

Features:

Create: Add a new person to the database via a POST request.
Read: Retrieve all people or fetch individual records by ID with GET requests.
Update: Update details of an existing person with a PUT request.
Delete: Remove a person from the database with a DELETE request.

---

Technologies Used:

Java 17: Programming language.
Spring Boot: Framework for developing the application.
H2 Database (or alternate database): In-memory database used for testing purposes.
Maven: Dependency management.

---

Endpoints:

POST /api/v1/person: Add a new person.
GET /api/v1/person: Get a list of all people.
GET /api/v1/person/{id}: Get details of a person by their ID.
PUT /api/v1/person/{id}: Update a person’s details.
DELETE /api/v1/person/{id}: Delete a person.

---

Validation:

The project uses Java Bean Validation (@NotBlank, @Valid, etc.) to ensure data integrity for the Person entity. Fields like name must not be empty.

---

Setup:

Clone the repository.
Import the project into your IDE (e.g., IntelliJ).
Ensure that Java 17 is installed and configured.
Run the project with Maven (mvn spring-boot:run) or from your IDE.

---

Note:

This project is meant for educational purposes and to demonstrate fundamental concepts in building RESTful APIs with Spring Boot. 

Acknowledgment: This project was created by following the YouTube tutorial from freeCodeCamp.org and Amigoscode.

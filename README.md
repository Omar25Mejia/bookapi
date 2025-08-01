# Book API

A REST API developed with Spring Boot to view the digital catalog of books from the "Letras Vivas" publishing house.

## Features

- List all books  
- Add a new book  
- Search books by title  
- Delete a book by its ID  

## Technologies Used

- Java 17  
- Spring Boot  
- Spring Data JPA  
- H2 (in-memory database)  

## How to Run the Project?

1. Clone this repository  
2. Open it in IntelliJ IDEA  
3. Run the `BookapiApplication.java` class  
4. Use Postman or another REST client to test the endpoints  

## Available Endpoints

| Method | URL                                 | Description             |
|--------|-------------------------------------|-------------------------|
| GET    | `/books`                            | List all books          |
| POST   | `/books`                            | Add a new book          |
| GET    | `/books/search?title=your-title`    | Search books by title   |
| DELETE | `/books/{id}`                       | Delete a book by ID     |

> Only visible if at least one book has already been inserted into the database.

## Author

- Marlon Omar Guzmán Mejía - GM190258

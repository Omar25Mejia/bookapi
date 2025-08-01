# BookAPI

Una API REST  desarrollada con Spring Boot para ver el catálogo digital de libros de la editorial  "Letras Vivas"

##  Funcionalidades

- Listar todos los libros
- Agregar un nuevo libro
- Buscar libros por título
- Eliminar un libro por su ID

## Tecnologías utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- H2 (base de datos en memoria)

## ¿Cómo ejecutar el proyecto?

1. Clonar este repositorio
2. Abrirlo con IntelliJ IDEA
3. Ejecutar la clase `BookapiApplication.java`
4. Utilizar Postman u otro cliente REST para probar los endpoints

##  Endpoints disponibles

| Método | URL                          | Descripción               |
|--------|------------------------------|---------------------------|
| GET    | `/books`                     | Lista todos los libros    |
| POST   | `/books`                     | Agrega un nuevo libro     |
| GET    | `/books/search?title=texto`  | Busca libros por título   |
| DELETE | `/books/{id}`                | Elimina un libro por ID   |


> Solo es visible si ya insertaste al menos un libro en la base de datos.

## Autor

- Marlon Omar Guzman Mejia - GM190258

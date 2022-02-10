# GO REST API

**A simple RESTful API built with GO for basic CRUD operations**

It allows users to view a list of books, create new books, modify and delete existing books.

Operations include:
- GET
- POST
- PUT
- DELETE

-----------

## Endpoints
| Endpoint | HTTP METHOD | Description |
| ----------- | ----------- | ----------- |
| "/api/books" | GET | Get list of books |
| "/api/books/{id}" | GET | Get a book by ID |
| "/api/books/" | POST | Create a new book |
| "/api/books/{id}" | PUT | Update a book by ID |
| "/api/books/{id}" | DELETE | Delete a book by ID |

-----------

## Run the app
To run the app, 
1. first create a go module by runing `go mod init rest-api`.
2. Run `go run main.go`
3. You can now access the API endpoints using the baseURL: `http://localhost:8080`
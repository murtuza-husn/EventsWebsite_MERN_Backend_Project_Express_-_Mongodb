[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MCPQ1ISX)
# CSD-3103 Individual MERN Project

## Project Overview

Briefly describe your application idea. What is it about? What kind of data are you modeling?

Example:
> This project is a basic library management system. Users can manage books and authors, with features for adding new books, updating book information, and deleting authors.

---

## Database Schema

### Models

**EXAMPLE model description**

Model 1: `books`

- `author`: the author's name (String)
- `name`: the name of the book (String)
- `borrowed`: if the book is currently being borrowed or not (Boolean)

Model 2: `borrowers`

- `name`: the user's first and last name (String)
- `phoneNumber`: the user's phone number (String)
- `borrowedBooks`: An array of embedded book documents with the following fields (Array)
  - `name`: the name of the book (String)
  - `author`: the author's name (String)
  - `borrowDate`: the date when the book was borrowed (Date)
  - `returnDate`: an optional field that states when the book was returned (Date)

### Indexes

List the indexes that were created. What kind of index is it and on what field(s)?

---

## CRUD API Endpoints

List all implemented endpoints with brief descriptions and expected inputs/outputs.

### EXAMPLE: Book Endpoints

| Method | Route              | Description        |
|--------|--------------------|--------------------|
| GET    | `/api/books`       | Get all books      |
| GET    | `/api/books/:id`   | Get a book by ID   |
| POST   | `/api/books`       | Create a new book  |
| PUT    | `/api/books/:id`   | Update book by ID  |
| DELETE | `/api/books/:id`   | Delete book by ID  |

(Add the same table for the second model.)


# Steps Performed.

mkdir backend - created a backend folder.
npm init -y -- npm init -y initializes a new project. It updates all dependencies of a Node.js Project

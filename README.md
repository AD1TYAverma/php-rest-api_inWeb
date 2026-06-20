# PHP REST API CRUD Application IN WEBPAGE

A RESTful API built with PHP and MySQL to perform CRUD operations on student records.

## Features

* Create Records
* Read Records
* Update Records
* Delete Records
* Search Records
* JSON Response Format
* MySQL Database Integration

## Technologies Used

* PHP
* MySQL
* REST API
* JSON
* Postman

## Database Structure

| Field | Type              |
| ----- | ----------------- |
| id    | INT (Primary Key) |
| name  | VARCHAR(100)      |
| age   | INT               |
| city  | VARCHAR(100)      |

## API Endpoints

### Get All Records

```http
GET /api-read.php
```

### Create Record

```http
POST /api-create.php
```

Request Body:

```json
{
  "name": "Aditya Verma",
  "age": 22,
  "city": "Lucknow"
}
```

### Update Record

```http
PUT /api-update.php
```

Request Body:

```json
{
  "id": 1,
  "name": "Aditya Verma",
  "age": 23,
  "city": "Prayagraj"
}
```

### Delete Record

```http
DELETE /api-delete.php
```

Request Body:

```json
{
  "id": 1
}
```

### Search Record

```http
POST /api-search.php
```

Request Body:

```json
{
  "search": "Aditya"
}
```

## Testing

Use Postman to test API endpoints and verify JSON responses.

## Learning Outcomes

* REST API Development
* CRUD Operations
* PHP Backend Development
* MySQL Database Management
* JSON Data Handling
* API Testing using Postman

## Author
Aditya Verma.
PHP Laravel Developer.

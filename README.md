# Flask CRUD REST API

A simple CRUD (Create, Read, Update, Delete) REST API built using Python Flask, SQLAlchemy, PostgreSQL, and Docker.

## Project Description

This project demonstrates how to build and run a REST API using Flask.

The API allows users to be created, viewed, updated, and deleted using HTTP requests.

The project uses PostgreSQL as the database and Docker to run the application and database in containers.

## Technologies Used

- Python
- Flask
- Flask-SQLAlchemy
- SQLAlchemy
- PostgreSQL
- Docker
- Docker Compose
- Postman

## CRUD Operations

The project provides the following API operations:

| Method | Endpoint | Description |
|---|---|---|
| POST | `/users` | Create a new user |
| GET | `/users` | Get all users |
| GET | `/users/<id>` | Get a user by ID |
| PUT | `/users/<id>` | Update a user |
| DELETE | `/users/<id>` | Delete a user |

## User Information

Each user contains:

- ID
- Username
- Email

## Example User

```json
{
    "username": "srija",
    "email": "srija@gmail.com"
}
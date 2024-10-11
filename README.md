# Course Management API
This project is a simple REST API built using Django and MySQL. 
It provides basic CRUD (Create, Read, Update, Delete) operations for managing courses, allowing users to create, retrieve, update, and delete courses.

## Features
Add new courses.
1. Retrieve all courses or a specific course by ID.
2. Update a course’s details by ID.
3. Delete a course by ID

## Table of Contents

Technologies Used
Installation and Setup
Prerequisites
Steps to Setup
Database Configuration
API Endpoints
GET /courses/
POST /courses/
GET /courses/{id}/
PUT /courses/{id}/
DELETE /courses/{id}/

## Technologies Used
- Python 3.8+
- Django 3+
- Django REST Framework
-MySQL
- Postman (for API testing)
-cURL (for API testing)

## Installation and Setup
## Prerequisites
- Before running this project, ensure you have the following installed on your system:
- Python (version 3.8 or later)
- MySQL
- Django
- MySQL client library (mysqlclient)

# Steps to Setup
1.Clone the Repository:
    - Clone the repo with `https://github.com/funiex/course_api`

# API Endpoints
## GET /courses/
-Description: Retrieve a list of all courses.
-Response: JSON array containing the list of courses.

## POST /courses/
-Description: Create a new course.
-Request Body: JSON object with course details (title, description, and duration).

## GET /courses/{id}/
-Description: Retrieve details of a specific course by its ID.
-Response: JSON object with course details

## PUT /courses/{id}/
-Description: Update an existing course by its ID.
-Request Body: JSON object with the updated course details.

##DELETE /courses/{id}/
-Description: Delete a specific course by its ID.

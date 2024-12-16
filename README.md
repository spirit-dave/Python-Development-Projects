# Task Management API
A simple RESTful API for managing tasks, built using Python's Flask framework. This API supports full CRUD (Create, Read, Update, Delete) operations, enabling efficient task management.

## Features
Add new tasks: Create tasks with a title and description.

Retrieve tasks: Fetch all tasks or view details of a specific task by ID.

Update tasks: Modify the title, description, or status of tasks.

Delete tasks: Remove tasks by their ID.

## Technologies Used

Python: Core programming language.

Flask: Framework for creating REST APIs.

SQLite: Database for data storage.

SQLAlchemy: ORM for database interactions.

Postman: Recommended tool for API testing.

Project Structure

TaskManagementAPI/

├── app.py             # Main application file
├── tasks.db           # SQLite database (auto-created on first run)
└── requirements.txt   # List of dependencies

## Setup and Installation

1. Clone the Repository
Use a Git client to clone the repository to your local machine.

2. Create a Virtual Environment
Set up a virtual environment to manage dependencies.

3. Install Dependencies
Install the required dependencies using the requirements.txt file.

4. Run the Application
Start the Flask server to host the API locally.

5. Test the API
Use tools like Postman or curl to interact with the endpoints.

## API Endpoints

1. Get All Tasks

Endpoint: GET /tasks

Description: Retrieve all tasks.

2. Get a Task by ID

Endpoint: GET /tasks/<id>

Description: Fetch a specific task using its unique ID.

3. Create a New Task

Endpoint: POST /tasks

Description: Add a new task to the system.
Request Body: Requires title and optional description.

4. Update a Task

Endpoint: PUT /tasks/<id>

Description: Update an existing task.
Request Body: Requires updated fields such as title, description, or status.

5. Delete a Task

Endpoint: DELETE /tasks/<id>

Description: Delete a specific task by its ID.

Database

The API uses SQLite for data storage. The database schema is automatically created when the application is first run.

## Task Model

Field	Type	Description
id	Integer	Primary key
title	String	Title of the task
description	String	Description of the task
status	String	Status of the task (default: pending)
Future Enhancements
Add user authentication for secure task management.
Implement task filtering based on status.
Develop a frontend using a framework like React or Vue.js.
Switch to PostgreSQL for scalability.


- Contact

For questions or suggestions, contact adeyemi.b.david@gmail.com









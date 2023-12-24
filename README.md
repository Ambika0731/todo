ToDo App
The ToDo App is a simple application designed to help users manage their tasks effectively. It allows users to create, update, delete, and view tasks in a convenient manner.

Features
Task Management: Create, edit, and delete tasks.

Technologies Used
Frontend: HTML, CSS
Backend: Python with Flask
Database: SQLite

Setup Instructions:

1.Clone the repository: https://github.com/Ambika0731/todo.git
2.Install the requirements: pip install -r requirements.txt
3.Database Setup: python app.py /create_tables
4.Run the Application: python app.py
5. Endpoints:
  i. Database Model (Todo): Defines a SQLAlchemy model for the ToDo tasks.
  ii. Route /create_tables: A route to create database tables (for initializing the ToDo table).
  iii. Route /: Handles both GET and POST requests. For GET requests, it retrieves all tasks from the database and renders them on the homepage using render_template. For POST requests, it adds a new task to the database.
  iv. Route /show: A route to display all tasks (might be for testing purposes).
  v. Route /update/<int:sno>: Allows updating a specific task identified by its serial number (sno).
  vi. Route /delete/<int:sno>: Deletes a task identified by its serial number (sno).

# Team_Task_Manager_Full_Stack

Team Task Manager is a full-stack web application designed to help teams efficiently manage their work by organizing projects, assigning tasks, and tracking progress. The system provides a structured environment where users can collaborate while maintaining clear responsibilities and visibility over ongoing work.

The application includes a secure authentication system that allows users to sign up and log in. Based on their role, users are granted different levels of access. Admin users have full control over the system, including creating projects, adding team members, assigning tasks, and monitoring overall progress. Member users can view the projects they are part of, access their assigned tasks, and update task statuses as work progresses.

Each project acts as a container for tasks and team members. Tasks can be created with details such as title, description, assigned user, status, and due date. The system supports task status tracking, enabling teams to monitor whether tasks are pending, in progress, or completed. This helps improve accountability and workflow transparency.

A dashboard is provided to give users an overview of their work. It displays task summaries, progress indicators, and highlights overdue tasks, helping users prioritize their responsibilities effectively.

The backend is built using RESTful APIs, ensuring smooth communication between the frontend and the database. Proper validations are implemented to maintain data integrity, and relationships between users, projects, and tasks are well-structured. The system can be implemented using either SQL or NoSQL databases depending on design preference.

Overall, this project demonstrates core full-stack development concepts, including authentication, role-based access control, API design, database management, and user interface integration, making it a practical solution for collaborative task management.

# Features

## Authentication

User signup and login functionality
Secure password handling

## Role-Based Access

Admin can create projects, assign tasks, and manage team members
Members can view and update their assigned tasks

## Project Management

Create, update, and delete projects
Add members to projects

## Task Management

Create and assign tasks
Track task status (Pending, In Progress, Completed)
Set due dates

## Dashboard

View all tasks
Track task progress
Identify overdue tasks

## Tech Stack

### Frontend

React.js / HTML / CSS / JavaScript

### Backend

Node.js with Express.js

### Database

MySQL

### Authentication

JWT (JSON Web Token)

# Acknowledgement

This project was built as a full-stack assignment to demonstrate knowledge of frontend, backend, database integration, and role-based access control.



# My Simple TODO Application

## Overview

My Simple TODO is a full-stack web application built with Node.js, Express, Pug, and MySQL. The application allows users to create, edit, and delete tasks while tracking whether each task has been completed.

This project demonstrates basic CRUD (Create, Read, Update, Delete) functionality, database integration, server-side validation, and user interface styling.

## Technologies Used

* Node.js
* Express.js
* Pug Template Engine
* MySQL
* HTML
* CSS
* JavaScript

## Features

### Task Management

* Create new tasks
* Edit existing tasks
* Delete tasks
* Mark tasks as completed or not completed

### Validation

* Prevents users from creating blank tasks
* Prevents users from editing a task to contain only blank spaces

### User Interface

* Dark mode themed design
* Centered application layout
* Color-coded action buttons
* Inline task editing
* Responsive task list styling

## Database Structure

The application stores tasks in a MySQL database table named `todos`.

### Fields

| Field     | Description                                          |
| --------- | ---------------------------------------------------- |
| id        | Unique identifier for each task                      |
| task      | Task description                                     |
| completed | Completion status (0 = Not Completed, 1 = Completed) |

## How to Run

1. Install project dependencies:

```bash
npm install
```

2. Start the application:

```bash
npm start
```

3. Open the application in a browser using the URL provided by the development server.

## Learning Objectives

This project provided practice with:

* Express routing
* Database queries
* CRUD operations
* Form handling
* Server-side validation
* Pug templates
* CSS styling and layout techniques
* Full-stack web application development

## Author

Hannah Weakley

## Sources

* OpenAI. *ChatGPT (GPT-5.5)*. Used for assistance with JavaScript, Express.js routing, Pug templates, CSS styling, debugging, and README development during the implementation of this project. Available at: https://chatgpt.com/

# DEPTask2

Blog Management System

Overview

This repository contains a blog management system built using Sequelize ORM package. The system consists of three tables: Users, Blogs, and Comments, with relationships between them.

Features

Users

- Display details of all users along with their posts and comments on each blog
- Search for a user with their details of blog and comments
- Delete, update, and create new users by providing their ID

Blogs

- Display details of all blogs along with their comments by providing user ID
- Search for a user's blog with its details of blog and comments by providing user and blog ID
- Delete, update, and create new blogs by providing user and blog ID


Comments

- Display details of all comments by providing user ID and blog ID
- Search for a comment on a user's blog by providing user, blog, and comment ID
- Delete, update, and create new comments by providing user, blog, and comment ID

Relationships

- Users have many Blogs (one-to-many)
- Blogs belong to one User (one-to-one)
- Comments belong to one Blog and one User (one-to-one)

Sequelize ORM

This system uses Sequelize ORM package to create and manage the relationships between the tables.

Usage

- Clone the repository and run npm install to install the dependencies.
- Run npm start to start the server.
- Use the API endpoints to perform CRUD operations on users, blogs, and comments.

API Endpoints

Users

- GET /users: Display details of all users along with their posts and comments.
- GET /users/:id: Display details of a specific user with their posts and comments.
- POST /users: Create a new user.
- PUT /users/:id: Update an existing user.
- DELETE /users/:id: Delete a user.

Blogs

- GET /blogs: Display details of all blogs along with their comments.
- GET /blogs/:id: Display details of a specific blog with its comments.
- POST /blogs: Create a new blog.
- PUT /blogs/:id: Update an existing blog.
- DELETE /blogs/:id: Delete a blog.

Comments

- GET /comments: Display details of all comments.
- GET /comments/:id: Display details of a specific comment.
- POST /comments: Create a new comment.
- PUT /comments/:id: Update an existing comment.
- DELETE /comments/:id: Delete a comment.



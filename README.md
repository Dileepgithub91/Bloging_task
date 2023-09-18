# blogging platform (Social Media)

## Introduction

Welcome to our Forum Website! This platform enables users to engage in discussions by creating topics, posting comments, and connecting with others. It is built using Node.js and MySQL, allowing users to register, log in, create topics, post comments, and delete their own topics.

## Features

- **User Authentication**: Secure registration, login, and logout functionality.
- **Topic Management**: Create, view, update, and delete discussion topics.
- **Comment System**: Post comments on topics and delete your own comments.
- **User Profiles**: Customize your profile with avatars and bio information.
- **Email Verification**: Verify your email for added security.

## Prerequisites

Before you begin, make sure you have the following prerequisites:

- **Node.js**: The JavaScript runtime for server-side development.
- **MySQL**: A relational database management system.
- **Git** (optional but recommended): A version control tool.

## Usage

1. **Start the Application**:

   To run the application, follow these steps:

   ```bash
   npm start
   ```

   The application should be accessible at `http://localhost:8800`.

2. **Register and Log In**:

   - Create a new account to access all features.
   - Log in using your credentials to start using the forum.

## API Endpoints

Here are the available API endpoints:

### User

- `POST /registerUser`: Register a new user.
- `GET /verify-email`: Verify the user's email address.
- `POST /loginUser`: Log in a user.
- `GET /getUser`: Get user details (authentication required).
- `DELETE /logoutUser`: Log out a user.


### Topic

- `POST /createTopic`: Create a new topic (authentication required).
- `DELETE /deleteTopic`: Delete a topic (authentication required).

### Comment

- `POST /addComment`: Add a new comment (authentication required).
- `DELETE /deleteComment`: Delete a comment (authentication required).

## Database

1. **Database Setup**:

   To set up the MySQL database, execute the SQL script provided in `database.sql`.

//

# File-sharing-App

# File Sharing App

A simple file-sharing application built using the MERN stack.

## Overview

This web application allows users to securely upload and share files with others. It leverages the MERN stack for the backend and frontend development, ensuring a robust and efficient file-sharing experience.

## Features

- **User Authentication:** Secure user authentication and authorization.
- **File Upload:** Easily upload files with a straightforward interface.
- **File Sharing:** Share files with others via generated links.
- **File Management:** Organize and manage your uploaded files.

## Technologies Used

- **Frontend:**
  - React: A JavaScript library for building user interfaces.
  - Axios: A promise-based HTTP client for making requests to the backend.
  - (Include any additional frontend technologies)

- **Backend:**
  - Node.js: JavaScript runtime for server-side development.
  - Express.js: Web application framework for Node.js.
  - MongoDB: NoSQL database for storing file metadata.
  - GridFS: MongoDB's specification for storing and retrieving large files.
  - (Include any additional backend technologies)

## Getting Started

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/DanishAbdullahPy/File-sharing-App.git
    cd File-sharing-App
    ```

2. **Install Dependencies:**
    ```bash
    # Install backend dependencies
    cd backend
    npm install

    # Install frontend dependencies
    cd ../frontend
    npm install
    ```

3. **Set Up MongoDB:**
    - Set up a MongoDB database and update the connection string in `backend/config/db.js`.

4. **Run the Application:**
    ```bash
    # Start the backend server
    cd backend
    npm start

    # Start the frontend development server
    cd ../frontend
    npm start
    ```

5. **Open Your Browser:**
    - Navigate to [http://localhost:3000](http://localhost:3000) to access the application.

## Folder Structure

```plaintext
|-- backend        # Backend server using Express.js
|-- frontend       # Frontend application using React
|-- public         # Public assets
|-- README.md      # Project documentation
|-- .gitignore     # Git ignore file
|-- package.json   # Project configuration and dependencies

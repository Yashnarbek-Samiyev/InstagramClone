
# InstagramAPI & InstagramClone Project

Welcome to the InstagramAPI and InstagramClone project, a clone of the Instagram platform implemented using FastAPI for the backend and ReactJS for the frontend.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [InstagramAPI (FastAPI)](#instagramapi-fastapi)
  - [InstagramClone (ReactJS)](#instagramclone-reactjs)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview

This project aims to replicate the core functionalities of Instagram, providing a RESTful API backend using FastAPI and a user-friendly frontend using ReactJS. Users can perform common actions such as uploading images, following other users, liking posts, and more.

## Features

- **User Authentication:** Secure user authentication and authorization.
- **Post Management:** Upload images, view posts, and interact with them.
- **User Interaction:** Follow other users, like posts, and comment on them.
- **Profile Management:** View and update user profiles.

## Tech Stack

- **Backend (InstagramAPI - FastAPI):**
  - FastAPI: A modern, fast (high-performance), web framework for building APIs.
  - SQLAlchemy: SQL toolkit and Object-Relational Mapping (ORM) for Python.
  - JWT: JSON Web Token for user authentication.

- **Frontend (InstagramClone - ReactJS):**
  - ReactJS: A JavaScript library for building user interfaces.
  - Redux: State management for React applications.
  - Axios: HTTP client for making requests to the InstagramAPI backend.
  - React Router: Navigation for React single-page applications.

## Getting Started

### InstagramAPI (FastAPI)

1. **Clone the Backend Repository:**

   ```bash
   git clone https://github.com/Yashnarbek-Samiyev/InstagramAPI.git
   cd InstagramAPI
   ```

2. **Create and Activate Virtual Environment:**

   ```bash
   python -m venv venv
   .\venv\Scripts\activate (on Windows)
   source venv/bin/activate (on macOS/Linux)
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the FastAPI server:**

   ```bash
   uvicorn main:app --reload
   ```

   The API will be accessible at `http://127.0.0.1:8000/docs` for Swagger documentation.

### InstagramClone (ReactJS)

1. **Clone the Frontend Repository:**

   ```bash
   git clone https://github.com/Yashnarbek-Samiyev/InstagramClone.git
   cd InstagramClone
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Configure Backend Endpoint:**

   Open the `src/config.js` file and update the `backendEndpoint` variable with the URL of your running FastAPI server.

4. **Run the React development server:**

   ```bash
   npm start
   ```

   The frontend will be accessible at `http://localhost:3000`.

## Usage

[Provide information on how users can interact with the InstagramClone frontend and use the InstagramAPI backend.]

## Contributing

If you would like to contribute to the project, please follow our [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [UIC group] - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgements

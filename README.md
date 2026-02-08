# Book Management System

A full-stack application developed using **Django** and **React** for managing books in a library setting, allowing for standard **CRUD** (Create, Read, Update, Delete) operations.

## Table of Contents

*   [Features](#features)
*   [Technologies Used](#technologies-used)
*   [Getting Started](#getting-started)
    *   [Prerequisites](#prerequisites)
    *   [Installation](#installation)
    *   [Running the Application](#running-the-application)
*   [Usage](#usage)
*   [Project Structure](#project-structure)
*   [Contributing](#contributing)
*   [License](#license)

## Features

*   **Create:** Add new book records to the system.
*   **Read:** View a list of all books with their details.
*   **Update:** Modify existing book information.
*   **Delete:** Remove books from the database.
*   **Cross-Origin Resource Sharing (CORS):** Seamless communication between the React frontend and Django backend using `django-cors-headers`.
*   **API:** Robust API endpoints built with **Django REST Framework**.

## Technologies Used

*   **Frontend:** React, JavaScript, Vite
*   **Backend:** Python, Django, Django REST Framework, `django-cors-headers`
*   **Database:** SQLite3

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have the following installed:

*   **Python 3.x**
*   **Node.js & npm**
*   `pip` (Python package installer)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Rana-Tek/Library-Management-CRUD.git
    cd Library-Management-CRUD
    ```

2.  **Backend Setup (Django):**
    *   Navigate to the server directory:
        ```bash
        cd server/newproject
        ```
    *   Create and activate a virtual environment:
        ```bash
        # For Windows
        python -m venv venv
        .\venv\Scripts\activate

        # For macOS/Linux
        python3 -m venv venv
        source venv/bin/activate
        ```
    *   Install backend dependencies:
        ```bash
        pip install -r requirements.txt
        ```
    *   Run database migrations:
        ```bash
        python manage.py migrate
        ```

3.  **Frontend Setup (React):**
    *   Navigate back to the root and into the client directory:
        ```bash
        cd ../../client/app
        ```
    *   Install frontend dependencies:
        ```bash
        npm install
        ```

### Running the Application

*   **Run the Backend Server (in `server/newproject` directory):**
    ```bash
    python manage.py runserver
    ```
    The API will be available at `http://localhost:8000/`.

*   **Run the Frontend Development Server (in `client/app` directory):**
    ```bash
    npm run dev
    ```
    The application will be accessible at `http://localhost:5173/` (or another port specified by Vite).

## Usage

[DEMO GIF] (assets/demo1.gif, assets/demo2.gif)

## Project Structure

The project uses a monorepo structure:

*   `/client/app`: Contains the React frontend code.
*   `/server/newproject`: Contains the Django backend API and manage.py file.

## Contributing

Contributions are welcome! Please follow these steps:
1.  Fork the repository.
2.  Create a new feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

## License




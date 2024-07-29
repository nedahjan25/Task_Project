# Task Management

# Description of project.

The web application is a task management system designed to help users organize and track their tasks efficiently. Users can register and log in to access personalized task management features. The application supports the creation, viewing, updating, and deletion of tasks, allowing users to set details such as task title, description, due date, and priority. A dedicated page displays all tasks, categorized as completed, not completed, or in progress, providing a comprehensive overview. The user interface is designed to be intuitive and visually appealing, with a responsive design for seamless use across different devices. The system also features a logout mechanism to securely end user sessions. Built on Node.js, Express, EJS, and SQLite3, the application leverages these technologies to deliver a reliable and scalable task management solution.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Routes](#routes)
- [Database](#database)
- [Styling](#styling)
- [Logout](#logout)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

- Node.js and npm installed.
- SQLite3 installed (for database usage).

## Installation

1. Clone the repository.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install dependencies.

## Usage

1. Start the application using `npm start` or `node index.js`.
2. Access the application in your browser at `http://localhost:3000`.

## Routes

- **Main Page:** `/main`
- **Login Page:** `/login`
- **Register Page:** `/register`
- **New Task:** `/tasks`
- **All Tasks Page:** `/all-tasks`
- **Logout Route:** `/logout`

## Database

- The application uses SQLite3 as its database.
- Database file: `database.db`.
- The database structure is defined in `index.js`.


## Logout

- To log out, click the "Logout" link in the navigation bar.
- After logout, you will be redirected to the login page.

## Troubleshooting

If you encounter any issues or errors, consider the following steps:

- Check the console logs for error messages.
- Verify the correctness of your routes and file paths.
- Clear your browser cache.

## Contributing

Feel free to contribute by opening issues or pull requests.


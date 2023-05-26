# First API - JStack Course

Welcome to First API, a project developed as part of the JStack - Full Stack Web Development course. This is a simple API for managing users, allowing you to list, create, view, and update user information.

## Prerequisites

Make sure you have the following dependencies installed on your machine:

- Node.js (version 20.1.0)
- npm (Node.js package manager, usually installed with Node.js)

## Installation

Follow the steps below to install and run the project locally:

1. Clone the repository to your local environment:
   ```
   git clone https://github.com/oleonardodeandrade/jstack_firstapi.git
   ```

2. Navigate to the project directory:
   ```
   cd jstack_firstapi
   ```

3. Install project dependencies using npm:
   ```
   npm install
   ```

## Configuration

Before starting the API, you need to configure the mock users file.

1. Open the `mocks/users.js` file in a text editor.

2. Add, remove, or edit the users as per your requirements. The file already contains some sample users.

## Usage

To start the API server, run the following command:
   ```
   node .\src\index.js
   ```

The API will be available at `http://localhost:3000`.

## Routes

The API has the following routes:

- `GET /users` - List all users.
- `GET /users/:id` - Get details of a specific user based on ID.
- `POST /users` - Create a new user.
- `PUT /users/:id` - Update the information of an existing user based on ID.

Make sure to provide the necessary parameters in routes that require a user ID.

## Contributing

Contributions are welcome! If you find any issues, have suggestions, or want to add new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


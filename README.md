---

# REST Server with Node and Express

This is a Node.js and Express.js-based REST server project that provides an API for managing users. The server is started at the "localhost:8080/api/user" route and offers the following endpoints to interact with the user collection:

## Prerequisites

Ensure you have Node.js and npm (Node Package Manager) installed on your system before running this project. You can download and install them from [nodejs.org](https://nodejs.org/).

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/ErickGBR/REST-Server.git
   ```

2. Navigate to the project directory:

   ```bash
   cd REST-Server
   ```

3. Install the dependencies using npm:

   ```bash
   npm i
   ```

## Start the Server

To start the server, use the following command:

```bash
npm start
```

The server will run at `http://localhost:8080/api/user`.

## Endpoints

Below are the available endpoints and corresponding HTTP verbs to interact with the user collection:

### 1. Create a New User

- **URL**: `/api/user`
- **HTTP Verb**: POST
- **Description**: Create a new user and add them to the user collection.
- **Request Parameters**:
  - `name`: User's name (string).
  - `age`: User's age (integer).

### 2. Get All Users

- **URL**: `/api/user`
- **HTTP Verb**: GET
- **Description**: Retrieve the complete list of users.


### 3. Update a User by ID

- **URL**: `/api/user/:id`
- **HTTP Verb**: PUT
- **Description**: Update a specific user by their ID.
- **Request Parameters**:
  - `id`: User ID (string).
- **Request Parameters** (any combination of the following):
  - `name`: New user name (string).
  - `age`: New user age (integer).

### 4. Delete a User by ID

- **URL**: `/api/user/:id`
- **HTTP Verb**: DELETE
- **Description**: Delete a specific user by their ID.
- **Request Parameters**:
  - `id`: User ID (string).

### 6. Partially Update a User by ID

- **URL**: `/api/user/:id`
- **HTTP Verb**: PATCH
- **Description**: Partially update a specific user by their ID.
- **Request Parameters**:
  - `id`: User ID (string).
- **Request Parameters** (any combination of the following):
  - `name`: New user name (string).
  - `email`: New user email (string).
  - `age`: New user age (integer).

## Contributions

If you would like to contribute to this project, please follow these contribution guidelines:

1. Fork the repository.
2. Create a branch for your contribution.
3. Make your changes and ensure that the tests pass.
4. Submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Thank you for using this Node and Express REST server! If you have any questions or suggestions, please feel free to contact us.

**Author:** Erick Burgos
**Email:** erickburgos1519@gmail.com

---
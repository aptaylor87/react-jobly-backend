# Jobly Backend

View a deployed version of the application [here](https://react-jobly-backend-nuj6.onrender.com)

## Overview

Jobly Backend is the server-side component of the Jobly application, responsible for handling data storage, authentication, and API endpoints.

## Technologies Used

- **Express**: Web framework for Node.js.
- **Cors**: Cross-Origin Resource Sharing middleware for Express.
- **Jsonwebtoken**: JSON Web Token implementation for Node.js.
- **Bcrypt**: Library for hashing passwords.
- **Pg**: PostgreSQL client for Node.js.
- **Morgan**: HTTP request logger middleware for Node.js.
- **Jsonschema**: JSON schema validator.

## Setup

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Create a `.env` file in the root directory and add necessary environment variables (e.g., database connection details, JWT secret).
4. Start the server with `npm start`.
5. The server will be running at the specified port (default: 3001).
6. Query endpoints with Insomnia or any other tool.
7. To interact with the API on a client please visit the frontend repo [here](https://github.com/aptaylor87/react-jobly-frontend)




## Contributing

Contributions are welcome! Please fork the repository and submit pull requests with any improvements, bug fixes, or new features.
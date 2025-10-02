# Express Server Project

This project is a simple Express server that listens on port 8001. It is set up to use Nodemon for automatic code reloading during development.

## Project Structure

```
express-server
├── src
│   └── server.js        # Entry point of the application
├── package.json         # Configuration file for npm
├── yarn.lock            # Dependency versions for consistency
├── Dockerfile           # Instructions to build the Docker image
├── nodemon.json         # Configuration for Nodemon
└── README.md            # Project documentation
```

## Installation

To install the dependencies, run:

```
yarn install
```

## Running the Server

To start the server with automatic reloading, use:

```
yarn start
```

The server will be available at `http://localhost:8001`.

## Docker

To build and run the Docker container, use the following commands:

```
docker build -t express-server .
docker run -p 8001:8001 express-server
```

This will expose the server on port 8001 of your host machine.
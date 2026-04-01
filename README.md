# Rasim

## Overview

Rasim is a comprehensive monorepo project that serves as a workspace for various applications and services. It features an Express API server, integrates a Telegram bot for image generation, and uses PostgreSQL with Drizzle ORM for database management. This project also includes an OpenAPI specification using Orval code generation, ensuring a well-structured and documented API.

## Project Structure

This project is organized into several key components:

- **/api**: Contains the Express API server.
- **/bot**: Implements the Telegram bot integration for generating images.
- **/db**: Manages database interactions using PostgreSQL and Drizzle ORM.
- **/openapi**: Holds the OpenAPI specifications and generated client code.

### Each folder contains:
- **index.ts**: The entry point for each respective service.
- **routes.js**: API endpoints and route handling for the Express server.
- **service.js**: Contains the business logic for each service.
- **model.js**: Defines the data models used in the application.

## Features
- **Pnpm Workspace**: Uses pnpm for package management and workspace handling, allowing for efficient dependency management across the monorepo.
- **Express API Server**: A robust server setup to handle HTTP requests and responses seamlessly.
- **Telegram Bot Integration**: Connects with Telegram for direct interaction with users, allowing for image generation on demand.
- **PostgreSQL with Drizzle ORM**: A powerful relational database solution, enabling efficient data storage and retrieval.
- **OpenAPI Specification**: Provides a clear and concise specification of the API's capabilities, which can be consumed by various clients.
- **Orval Codegen**: Automatically generates TypeScript API clients based on the OpenAPI specs, ensuring consistency across front-end and back-end development.

## Installation

To install the necessary dependencies, run:
```bash
pnpm install
```

## Running the Project

To start the server and bot, use:
```bash
pnpm start
```

## Contribution

Contributions are welcome! Please submit a pull request or raise an issue if you find any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

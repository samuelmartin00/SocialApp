# SocialApp
SocialApp is a microservices-based social media platform crafted with FastAPI, React, and MongoDB. Featuring secure authentication, post creation, and user interactions, it offers a modern and scalable solution for building vibrant online communities. Connect, share, and engage seamlessly with SocialApp.

# SocialApp Documentation

## Introduction

SocialApp is a microservices-based social media platform designed to foster online communities. Built with FastAPI, React, and MongoDB, it provides a scalable and modern solution for users to connect and engage.

## Features

- **User Authentication:** Secure user authentication and authorization system.
- **Post Interaction:** Create, like, and comment on posts for active engagement.
- **User Profiles:** Robust user profiles with customizable settings.
- **Scalable Architecture:** Microservices architecture for scalability and maintainability.

## Architecture

SocialApp follows a microservices architecture, dividing functionality into separate services:

- **User Service:** Manages user-related operations.
- **Post Service:** Handles post creation, likes, and comments.
- **API Gateway:** Routes requests to the appropriate services.

## Prerequisites

Ensure you have the following dependencies installed:

- [Node.js](https://nodejs.org/)
- [Python](https://www.python.org/) (>=3.8)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/SocialApp.git
    cd SocialApp
    ```

2. Set up the User and Post services:

    ```bash
    cd services/user_service
    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

    Repeat the same process for the `services/post_service` directory.

3. Set up the API Gateway:

    ```bash
    cd api-gateway
    npm install
    ```

4. Set up the frontend:

    ```bash
    cd frontend
    npm install
    ```

## Configuration

Customize SocialApp by configuring the environment variables in each service. Refer to [Configuration Documentation](./docs/configuration.md) for details.

## Running the Application

1. Start the MongoDB database (adjust connection details in services if needed):

    ```bash
    mongod
    ```

2. Run the User and Post services:

    ```bash
    cd services/user_service
    python main.py
    ```

    Repeat the same process for the `services/post_service` directory.

3. Run the API Gateway:

    ```bash
    cd api-gateway
    npm start
    ```

4. Run the frontend:

    ```bash
    cd frontend
    npm start
    ```

Access the application at [http://localhost:3000](http://localhost:3000).

## API Endpoints

Explore the available API endpoints by referring to the [API Documentation](./docs/api-endpoints.md).

## Frontend Components

Understand the frontend components and their interactions by referring to the [Frontend Documentation](./docs/frontend-components.md).

## Authentication

Learn about the authentication process in SocialApp from the [Authentication Guide](./docs/authentication.md).

## Deployment

Deploy SocialApp to production by following the steps in the [Deployment Guide](./docs/deployment.md).

## Contributing

Contribute to SocialApp by following the guidelines in the [Contribution Documentation](./docs/contributing.md).

## License

SocialApp is licensed under the [MIT License](./LICENSE).

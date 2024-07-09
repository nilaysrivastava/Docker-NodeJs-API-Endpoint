# Docker-NodeJs-API-Endpoint

This repository contains a simple Node.js API endpoint Dockerized with Express.

## Overview

This project demonstrates setting up an Express-based API endpoint within a Docker container. It includes a basic Node.js application that responds with a JSON message to requests.

## Features

- **Express Framework**: Utilizes Express, a fast, unopinionated, minimalist web framework for Node.js.
- **Dockerized**: The application is containerized using Docker for easy deployment and scalability.
- **API Endpoint**: Provides a basic API endpoint `/` that responds with a JSON message.

## Requirements

- Docker
- Node.js (Optional for local development)

## Setup

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   ```

2. **Build the Docker image**:
   ```bash
   docker build -t docker-nodejs-api .
   ```

3. **Run the Docker container**:
   ```bash
   docker run -p 3000:3000 docker-nodejs-api
   ```

4. **Access the API endpoint**:
   Open a web browser or use a tool like `curl` to access the API endpoint:
   ```bash
   curl http://localhost:3000
   ```

5. **Stop the container**:
   To stop the running container, press `Ctrl + C`.

## API Endpoint

- **URL**: `http://localhost:3000`
- **Method**: `GET`
- **Response**: JSON object

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements.

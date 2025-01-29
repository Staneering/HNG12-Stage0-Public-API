

# Public API Task

This is a public API that returns basic information in JSON format.

## Project Description

### Public API for Basic Information Retrieval

This project is a simple public API built with Node.js and Express that returns basic information in JSON format. The API is designed to handle GET requests and provides the following details:

- **Email Address**: The registered email address used to register on the HNG12 Slack workspace.
- **Current Datetime**: The current datetime in ISO 8601 format (UTC).
- **GitHub URL**: The URL of the project's codebase on GitHub.

### Features

- **Cross-Origin Resource Sharing (CORS)**: The API includes middleware to handle CORS, allowing it to be accessed from different origins.
- **Dynamic Datetime**: The `current_datetime` field is dynamically generated to always provide the current date and time in ISO 8601 format.
- **JSON Response**: All responses are formatted in JSON, making it easy to integrate with various applications and services.

### Technology Stack

- **Programming Language**: JavaScript (Node.js)
- **Framework**: Express
- **Deployment**: The API is deployed on Vercel.

### Usage

This API is intended for educational purposes and as a demonstration of how to build and deploy a simple Node.js application. It can be used as a starting point for more complex projects or as a reference for learning how to create RESTful APIs with Node.js and Express.

### How to Access

The API is deployed and publicly accessible at: [My Vercel Url](https://public-api-task-staneering-ogochukwu-stanley-ikegbos-projects.vercel.app/)

### Example Response

```json
{
  "email": "stacymacbrains@gmail.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/Staneering/HNG12Stage0"
}
```

### Project Structure

- **index.js**: The main entry point of the application, containing the server setup and endpoint definition.
- **vercel.json**: Configuration file for deploying the project on Vercel.

### Getting Started

To get started with this project, follow the setup instructions provided below to run the API locally or deploy it to your preferred platform.

## Setup Instructions

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Staneering/HNG12ApiProjectRepo.git
   cd HNG12ApiProjectRepo
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Running the Server Locally

1. Start the server:
   ```bash
   node index.js
   ```

2. Access the API at:
   ```
   http://localhost:3000
   ```

## Deployment

The API is deployed at: [My Vercel Url](https://public-api-task-staneering-ogochukwu-stanley-ikegbos-projects.vercel.app/)

### Deploying to Vercel

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Log in to Vercel:
   ```bash
   vercel login
   ```

3. Deploy the project:
   ```bash
   vercel
   ```

4. Follow the prompts:
   - **Set up and deploy “public-api-task”?**: Press `Y` to confirm.
   - **Which scope do you want to deploy to?**: Select your Vercel account or team.
   - **Link to existing project?**: Press `N` to create a new project.
   - **What’s your project’s name?**: You can accept the default name or provide a custom name.
   - **In which directory is your code located?**: Press `Enter` to accept the default (`.`).
   - **Want to override the settings?**: Press `N` to use the default settings.

5. Wait for the deployment to complete. Vercel will provide a URL where your API is hosted.

## API Documentation

### Endpoint URL

- **GET** `/`

### Request Format

This API does not require any request body or parameters. Simply send a GET request to the endpoint.

### Response Format

The API responds with a JSON object containing the following fields:

- **email**: The registered email address used to register on the HNG12 Slack workspace.
- **current_datetime**: The current datetime in ISO 8601 format (UTC).
- **github_url**: The URL of the project's codebase on GitHub.

### Example Response

```json
{
  "email": "stacymacbrains@gmail.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/Staneering/HNG12Stage0"
}
```

### Usage Example

You can test the API using a web browser, curl, or a tool like Postman.

#### Using curl

```bash
curl https://public-api-task-staneering-ogochukwu-stanley-ikegbos-projects.vercel.app/
```

#### Using Postman

1. Open Postman.
2. Create a new GET request.
3. Enter the URL: `https://public-api-task-staneering-ogochukwu-stanley-ikegbos-projects.vercel.app/`.
4. Send the request.
5. You should see a response similar to the example response above.

### Error Handling

The API is designed to handle errors gracefully and will return appropriate HTTP status codes in case of errors. Here are some possible error responses:

- **500 Internal Server Error**: If there is an issue with the server, the API will respond with a 500 status code.

## Backlinks

- [Hire Node.js Developers](https://hng.tech/hire/nodejs-developers)



# task-manager-api

## Introduction
`task-manager-api` is a task management REST API complete with user accounts and authentication. This API allows users to manage tasks efficiently and securely. Built with Node.js and Express, and utilizing MongoDB for data storage, it's designed for robust and scalable task management.

## Key Features
- User account creation and management.
- Secure user authentication.
- Task creation, updating, and deletion.
- File upload capability for tasks.

### Prerequisites
- Node.js
- MongoDB

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/task-manager-api.git
   ```
2. **Navigate to the project directory and install npm independecies.**

### Configuration
1. **Create dev.env and test.env files in the config directory.**
   
2. **Add the following environment variables in the dev.env file:**
   ```bash
   PORT=3000
   MONGODB_URL=mongodb: your-mongodb-url
   JWT_SECRET=your-secret-message
   ```
3. **Configure MongoDB and ensure it's running on your local machine.**

### Running the Application

#### For development:
   ```bash
   npm run dev
   ```
#### For productions:
   ```bash
   npm start
   ```

### Running Tests

#### Execute tests using jest:
   ```bash
   npm test
   ```

# Student Management REST API

## About the Project
The Student Management REST API is a backend project developed using Node.js and Express.js. It allows users to manage student records through REST APIs and perform CRUD operations.

## Features
- View all student records
- Get student details by ID
- Add new students
- Update existing student information
- Delete student records
- Custom logger middleware
- Error handling with appropriate HTTP status codes
- Modular routing for clean code organization

## Technologies Used
- Node.js
- Express.js
- Postman
- JavaScript
- JSON

## Project Structure

```text
student-API-ASSignment/
├── data/
│   └── students.js
├── middleware/
│   └── logger.js
├── routes/
│   └── studentRoutes.js
├── app.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/students` | Get all students |
| GET | `/students/:id` | Get a student by ID |
| POST | `/students` | Add a new student |
| PUT | `/students/:id` | Update student details |
| DELETE | `/students/:id` | Delete a student |

## Installation and Setup

### 1. Clone the Repository
```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project Folder
```bash
cd student-management-api
```

### 3. Install Dependencies
```bash
npm install
```

### 4. Start the Server
```bash
node app.js
```

The server runs at:

`http://localhost:3000`

## Testing
All API endpoints can be tested using Postman by sending GET, POST, PUT, and DELETE requests.

## Data Storage
This project uses a JavaScript array to store student records. No database, MongoDB, MySQL, or Mongoose is used.

## Learning Outcomes
This project helped me understand:
- Express server setup
- REST API development
- CRUD operations
- Middleware implementation
- Modular routing
- HTTP status codes and error handling
- API testing using Postman

## Assignment Details
**Course:** Web Development III  
**Assignment:** Lab Assignment 2 – Student Management REST API 
**Unit:** 2

## Author
Student Project – Web Development III

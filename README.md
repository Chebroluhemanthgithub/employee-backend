<h1>Employee Management System — Backend</h1>

<h3>Node.js + Express + MySQL  API for managing employees.</h3>

<h3>⭐ Features</h3>

Add employees

Get all employees

Update employee details

Delete employees

Uses Express REST API

CORS enabled



<h3>Tech Stack</h3>

<ol>Node.js

Express.js

MySQL2

dotenv

CORS</ol>


🔑 Environment Variables

Create a .env file:

PORT=5000

DB_HOST=your_mysql_host
DB_USER=your_mysql_user
DB_PASSWORD=your_mysql_password
DB_NAME=your_mysql_database

<h3>Run Locally</h3>
Install dependencies
npm install

Start server
npm start


Server runs at:
👉 http://localhost:5000

🛠 API Endpoints
➕ Add Employee

POST /api/employees

Body:

{
  "name": "Ram",
  "role": "Developer",
  "salary": 45000
}

📄 Get All Employees

GET /api/employees

✏ Update Employee

PUT /api/employees/:id

❌ Delete Employee

DELETE /api/employees/:id

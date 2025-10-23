🎓 Student Management System (AngularJS + SQL)
📘 Project Description

The Student Management System is a simple, web-based CRUD application built using AngularJS and SQL.
It enables users to add, view, update, and delete student details such as Name, Age, Department, Email, and Phone Number.

The main goal of this project is to demonstrate how AngularJS interacts with a SQL database through a lightweight backend using Node.js/Express or PHP.
This makes it a great beginner-friendly full-stack project for learning CRUD operations and database connectivity.

🧰 Technologies Used

Frontend: HTML, CSS, AngularJS

Backend: Node.js / PHP (for SQL connectivity)

Database: MySQL / SQLite

Programming Language: JavaScript

🚀 Features

Add new student records

View all students in a dynamic table

Update and delete existing records

Client-side form validation using AngularJS

Stores data securely in SQL database

Clean, responsive, and user-friendly UI

⚙️ How It Works

The frontend (AngularJS) manages all user interactions and form validations.

The backend (Node.js or PHP) connects to the SQL database and handles requests.

The database stores all student details.

The frontend communicates with the backend using HTTP requests (GET, POST, PUT, DELETE).

The backend executes SQL queries and returns responses to AngularJS for display on the UI.

🧩 API Endpoints

POST /addStudent → Add a new student

GET /getStudents → Retrieve all student records

PUT /updateStudent/:id → Update an existing student record

DELETE /deleteStudent/:id → Delete a student record

💡 Challenges and Solutions

Challenge: Connecting AngularJS to SQL database
Solution: Used a lightweight backend (Node.js or PHP) to handle SQL queries safely.

Challenge: Data not updating instantly on UI
Solution: Implemented $scope and $apply() to refresh data dynamically.

Challenge: Form validation errors
Solution: Used AngularJS directives like ng-model, ng-required, and real-time validation messages.

🏁 Conclusion

The Student Management System project successfully demonstrates how AngularJS can integrate with SQL databases through a simple backend to perform all CRUD operations.
It provides a clear understanding of how frontend and backend communicate, making it an excellent learning project for full-stack development.

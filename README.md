🏢 Hostel Management System – Multi-Login Portal
🔍 Overview
This web-based application provides a role-based login system for managing hostel operations. It includes three main roles:

Student

Admin

Security

Each role has a dedicated dashboard and access controls. The Admin Dashboard includes powerful features like Room Management and Leave Request Management.

📁 Project Modules
Copy
Edit
Login_page/
Admin_dashboard1/
Manage_rooms/
Request_leave/
🚀 Features
🔐 Login Page
Common login portal for all roles

Dynamic navigation based on role

Input validation and authentication

🛠 Admin Dashboard
Role-based access to admin functionalities

Intuitive UI to manage rooms and requests

🏘 Manage Rooms
Add/Edit/Delete room details

View current occupancy and room status

📩 Request Leave
View leave requests submitted by students

Approve, reject, or mark as pending

🛣️ Navigation Flow
pgsql
Copy
Edit
Login Page
├── Login as Admin
│   └── Admin Dashboard
│       ├── Manage Rooms
│       │   └── Room Management Interface
│       └── Request Leave
│           └── Leave Request List & Actions
├── Login as Student
│   └── [Student Dashboard - To Be Developed]
└── Login as Security
    └── [Security Dashboard - To Be Developed]
🧰 Technologies Used
Frontend: react+typescript html,css,javascript

Backend: [Add if applicable: PHP, Node.js, etc.]

Database: [Add if applicable: MySQL, MongoDB, etc.]

Libraries/Tools: Bootstrap (if used), jQuery (if used)

# student-report-management-system
The Student Record Management System (SRMS) is a console-based application developed in C that manages student records efficiently using file handling.
The system supports role-based access control, allowing different users to perform actions based on their permissions.

This project demonstrates practical use of:

Structures

File handling

Role-based authentication

Menu-driven programs

🛠 Technologies Used

Programming Language: C

Compiler: GCC / Turbo C / VS Code C Compiler

Files Used:

students.txt – stores student records

credentials.txt – stores login credentials

👥 User Roles & Permissions
Role	Permissions
ADMIN	Add, Display, Search, Update, Delete
STAFF	Display, Search, Update
GUEST	Display, Search
USER	Display only
🔐 Login System

Users must log in using a username and password

Credentials are verified from credentials.txt

Maximum 3 login attempts allowed

Role is automatically detected after login


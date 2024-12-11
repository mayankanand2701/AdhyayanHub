# AdhyayanHub
AdhyayanHub is a web-based application designed to facilitate efficient management of educational data and processes. It supports three distinct user roles: Admin, Teacher, and Student. The platform ensures secure access, role-based functionalities, and an intuitive interface for managing students, courses, and associated details.

## Features
- Role-Based Access Control
  - Secure login and tailored functionalities based on user roles.
- Admin Features
  - Add, edit, and delete students.
  - Manage teachers and their assigned courses.
  - Full control over the database.
- Teacher Features
  - Add students and courses.
  - Manage course details.
  - View and update student information.
- Student Features
  - View personal profiles.
  - Access course details.
  - View teacher information.
- Additional Features
  - Secure password storage with encryption.
  - Responsive and user-friendly interface using Thymeleaf.
  - Relational database integration for efficient data handling.

## User Roles and Permissions

- Admin
  - Full access to all system functionalities.
  - Manage teachers, students, and courses.
- Teacher
  - Add and update course details.
  - Manage assigned student information.
- Student
  - View personal details, enrolled courses, and teacher information.

## Tech Stack

- Backend : Spring Boot
- Frontend : Thymeleaf
- Database : MySQL
- Security : Spring Security with BCrypt encryption
- Build Tool : Maven

## Getting Started
### Prerequisites
- Java 8 or higher
- Maven
- MySQL Server
- An IDE like IntelliJ IDEA or Eclipse

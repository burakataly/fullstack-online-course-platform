Online Course Platform
This repository contains a full-stack online course platform developed to simulate a typical e-learning environment similar to platforms like Coursera. The project features a secure frontend and backend, providing functionalities expected from an online course platform, including course enrollment, payment processing, instructor profiles, and progress tracking.

Table of Contents
Features
Technologies Used
Getting Started
Prerequisites
Installation
Features
User Authentication: Secure login and registration using JWT-based authentication.
Role-Based Access Control: Different access levels for Students, Instructors, and Admins.
Course Management: Instructors can create, update, and manage their courses.
Enrollment System: Students can enroll in courses by paying and access course content.
Payment Processing: Integrated payment system for course enrollment.
Instructor Profiles: Students can view profiles of instructors, including their courses and credentials.
Progress Tracking: Students can see their progress within enrolled courses.
Course Content Access: Students can access course materials after enrollment.
RESTful APIs: Layered APIs for managing instructors, students, courses, enrollments, and progress tracking.
Secure APIs: All APIs are secured with JWT-based authentication and role-based access control.
Technologies Used
Frontend: Next.js
Backend: Spring Boot
Database: MySQL
Authentication: JSON Web Tokens (JWT)

Getting Started
Prerequisites
Node.js and npm installed on your machine.
Java Development Kit (JDK) 8 or higher.
MySQL database installed and running.
Maven for building the Spring Boot application.
Installation
Backend Setup
Clone the repository:

git clone https://github.com/burakataly/fullstack-online-course-platform.git
cd fullstack-online-course-platform/backend
Configure the Database:

Update the application.properties file with your MySQL database credentials:

properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=your_username
spring.datasource.password=your_password
Build and Run the Backend:

mvn spring-boot:run
The backend server will start on http://localhost:8080.

Frontend Setup
Navigate to the frontend directory:

cd ../frontend
Install Dependencies:

npm install
Configure Environment Variables:

Create a .env file and set the necessary environment variables.

Run the Frontend:

npm run dev
The frontend application will be available at http://localhost:3000.

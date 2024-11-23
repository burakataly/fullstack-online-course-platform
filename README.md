
# Online Course Platform

This repository contains a full-stack online course platform developed to simulate a typical e-learning environment, similar to platforms like Coursera. The project features a secure frontend and backend, providing functionalities expected from an online course platform, including course enrollment, payment processing, instructor profiles, and progress tracking.

---

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
    - [Backend Setup](#backend-setup)
    - [Frontend Setup](#frontend-setup)

---

## Features
- **User Authentication**: Secure login and registration using JWT-based authentication.
- **Role-Based Access Control**: Different access levels for Students, Instructors, and Admins.
- **Course Management**: Instructors can create, update, and manage their courses.
- **Enrollment System**: Students can enroll in courses by paying and accessing course content.
- **Payment Processing**: Integrated payment system for course enrollment.
- **Instructor Profiles**: Students can view profiles of instructors, including their courses and credentials.
- **Progress Tracking**: Students can see their progress within enrolled courses.
- **Course Content Access**: Students can access course materials after enrollment.
- **RESTful APIs**: Layered APIs for managing instructors, students, courses, enrollments, and progress tracking.
- **Secure APIs**: All APIs are secured with JWT-based authentication and role-based access control.

---

## Technologies Used
- **Frontend**: Next.js
- **Backend**: Spring Boot
- **Database**: MySQL
- **Authentication**: JSON Web Tokens (JWT)

---

## Getting Started

### Prerequisites
Make sure the following are installed on your machine:
- **Node.js** and **npm**
- **Java Development Kit (JDK)** 8 or higher
- **MySQL** database
- **Maven** for building the Spring Boot application

---

### Installation

#### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/burakataly/fullstack-online-course-platform.git
   cd fullstack-online-course-platform/backend
   ```

2. Configure the database:
   Update the `application.properties` file with your MySQL database credentials:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/your_database
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```

3. Build and run the backend:
   ```bash
   mvn spring-boot:run
   ```
   The backend server will start on `http://localhost:8080`.

#### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   Create a `.env` file and set the necessary environment variables.

4. Run the frontend:
   ```bash
   npm run dev
   ```
   The frontend application will be available at `http://localhost:3000`.

---

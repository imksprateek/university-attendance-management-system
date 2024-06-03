# University Attendance Management System

## Overview

The University Attendance Management System is a robust, scalable, and efficient system built using Spring Boot, MongoDB, and Swagger UI. This application follows the Model-View-Controller (MVC) architecture pattern to ensure a clear separation of concerns, making the application easier to manage and extend.

## Features

- **User Authentication**: Secure login and registration for students, teachers, and administrators.
- **Attendance Recording**: Mark and view attendance for classes.
- **Reports Generation**: Generate attendance reports for students and classes.
- **Role Management**: Different functionalities for students, teachers, and administrators.
- **API Documentation**: Interactive API documentation with Swagger UI.

## Technologies Used

- **Spring Boot**: Backend framework for creating standalone, production-grade Spring-based applications.
- **MongoDB**: NoSQL database for storing application data.
- **Swagger UI**: Framework for documenting APIs.
- **MVC Architecture**: Ensures separation of concerns in the application.

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven
- MongoDB

### Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/imksprateek/university-attendance-management-system.git
   cd university-attendance-management-system
   ```
2. **Configure MongoDB**

- Ensure MongoDB is running on your local machine or on MongoDB Atlas and configure the connection string in `src/main/resources/.env` file.
- Read `.env.example` file for instructions

3. **Build and Run the Application**
  ```
mvn clean install
mvn spring-boot:run
```

4. **Access the Application**
- Swagger UI can be accessed at `http://localhost:8080/swagger-ui/index.html`


## Project Structure

- **Model**: Contains the entity classes (e.g., Student, Teacher, Attendance).
- **View**: Handles the user interface (integrated with Thymeleaf or any other front-end framework if used).
- **Controller**: Contains the RESTful API endpoints and handles HTTP requests.
- **Repository**: Interfaces for data access and interaction with MongoDB.
- **Service**: Contains the business logic of the application.


## Contribution
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.



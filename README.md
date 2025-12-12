# BestDoctor - Hospital Management System

A full-stack hospital management system with patient-doctor matching, consultation scheduling, and an AI symptom chatbot.

## Features

- Patient registration and problem submission
- Doctor registration and specialization management
- Automatic doctor assignment based on symptoms
- Consultation scheduling
- Prescription management
- AI-powered symptom chatbot

## Tech Stack

- **Frontend**: HTML, CSS (Bootstrap), JavaScript (React)
- **Backend**: Java Spring Boot
- **Database**: MySQL
- **AI Integration**: Rule-based chatbot with keyword matching

## Project Structure

```
BestDoctor/
├── frontend/              # React frontend application
├── backend/               # Spring Boot backend application
└── docs/                  # Documentation files
```

## Setup Instructions

### Prerequisites

- Java 17+
- Node.js 16+
- MySQL 8+
- Maven

### Backend Setup

1. Navigate to the backend directory:
   ```
   cd backend
   ```

2. Configure your database in `src/main/resources/application.properties`

3. Build and run the Spring Boot application:
   ```
   ./mvnw spring-boot:run
   ```

4. The backend will be available at `http://localhost:8080`

### Frontend Setup

1. Navigate to the frontend directory:
   ```
   cd frontend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm start
   ```

4. The frontend will be available at `http://localhost:3000`

## API Documentation

API documentation is available at `http://localhost:8080/swagger-ui.html` when the backend is running. 
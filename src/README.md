# Mergington High School Activities Management System

A comprehensive web application built with FastAPI and MongoDB that enables students to discover and register for extracurricular activities, while providing teachers and administrators with powerful management tools.

## Features

### For Students
- **Browse Activities**: View all available extracurricular activities with detailed descriptions and schedules
- **Advanced Search & Filtering**: 
  - Search activities by name or description
  - Filter by category (Sports, Arts, Academic, Community, Technology)
  - Filter by day of the week (Monday through Sunday)
  - Filter by time period (Before School, After School, Weekend)
- **Real-time Updates**: Dynamic filtering and search with instant results
- **Activity Details**: View complete information including schedules, participant limits, and current enrollment

### For Teachers & Administrators
- **Secure Authentication**: Role-based login system with encrypted password storage
- **Student Management**: 
  - Register students for activities
  - Remove students from activities
  - View participant lists
- **Activity Oversight**: Monitor enrollment and manage activity participation

### Technical Features
- **RESTful API**: Built with FastAPI for robust backend functionality
- **Database Integration**: MongoDB for efficient data storage and retrieval
- **Responsive Design**: Modern, mobile-friendly user interface
- **Session Management**: Secure authentication with session handling
- **Data Validation**: Comprehensive input validation and error handling

## Architecture

- **Backend**: FastAPI with Python
- **Database**: MongoDB for data persistence
- **Frontend**: Vanilla HTML, CSS, and JavaScript
- **Authentication**: Argon2 password hashing with session-based auth

## API Endpoints

### Activities
- `GET /activities/` - Retrieve all activities with optional filtering
- `GET /activities/days` - Get available activity days
- `POST /activities/{activity_name}/signup` - Register student for activity (teacher auth required)
- `POST /activities/{activity_name}/unregister` - Remove student from activity (teacher auth required)

### Authentication
- `POST /auth/login` - Teacher/admin login
- `GET /auth/check-session` - Validate user session

## Development Guide

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).

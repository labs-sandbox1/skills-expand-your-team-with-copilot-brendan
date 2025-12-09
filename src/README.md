# Mergington High School Activities

A web application that allows teachers to manage student extracurricular activities at Mergington High School. The application features a FastAPI backend with MongoDB database and an interactive frontend for browsing and managing activity registrations.

## Features

### For Students and Visitors
- **View activities**: Browse all available extracurricular activities with detailed information including schedules, descriptions, and participant counts
- **Search**: Find activities by name or description
- **Filter by category**: View activities by type (Sports, Arts, Academic, Community, Technology)
- **Filter by day**: See activities scheduled on specific days of the week (Monday through Sunday)
- **Filter by time**: Browse activities by time slot (Before School, After School, Weekend)

### For Teachers (Authentication Required)
- **Teacher login**: Secure authentication system for school staff
- **Register students**: Sign up students for activities using their school email
- **Unregister students**: Remove students from activities when needed
- **Activity management**: Full control over student participation in all activities

## Technology Stack

- **Backend**: FastAPI (Python web framework)
- **Database**: MongoDB (for storing activities and teacher accounts)
- **Frontend**: HTML, CSS, and JavaScript
- **Authentication**: Teacher login with password hashing

## Development Guide

For detailed setup and development instructions, please refer to our [Development Guide](../docs/how-to-develop.md).

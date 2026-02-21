# Dependency Report

This document provides a detailed overview of the dependencies used in the project.

---

## Backend Dependencies

| Library           | Version    | Purpose                                      |
|-------------------|------------|----------------------------------------------|
| Flask             | 3.0.2      | Web framework for building the backend.      |
| Flask-Cors        | 4.0.0      | Enables Cross-Origin Resource Sharing (CORS).|
| Flask-SQLAlchemy  | 3.1.1      | ORM for database interactions.               |
| Flask-Login       | 0.6.3      | Manages user sessions.                       |
| Flask-WTF         | 1.2.1      | Simplifies form handling.                    |
| Flask-Bcrypt      | 1.0.1      | Provides password hashing utilities.         |
| Flask-Mail        | 0.9.1      | Sends emails from the application.           |
| Flask-SocketIO    | 5.3.6      | Enables WebSocket communication.             |
| Mediapipe         | 0.10.9     | Hand tracking and gesture recognition.       |
| OpenCV            | 4.8.0.74   | Image and video processing.                  |
| Scikit-learn      | 1.3.0      | Machine learning library.                    |
| Matplotlib        | 3.7.2      | Data visualization.                          |
| WTForms           | 3.0.1      | Form validation and rendering.               |
| Itsdangerous      | 2.1.2      | Provides cryptographic signing utilities.    |

---

## Frontend Dependencies
- No `package.json` detected. Static assets are used.

---

## ML Dependencies

| Library           | Version    | Purpose                                      |
|-------------------|------------|----------------------------------------------|
| Mediapipe         | 0.10.9     | Hand tracking and gesture recognition.       |
| OpenCV            | 4.8.0.74   | Image and video processing.                  |
| Scikit-learn      | 1.3.0      | Machine learning library.                    |
| Matplotlib        | 3.7.2      | Data visualization.                          |

---

## Notes
- All dependencies are compatible with Python 3.13.3.
- No version conflicts detected.
- Ensure CUDA compatibility if using GPU acceleration.
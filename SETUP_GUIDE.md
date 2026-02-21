# Setup Guide

This document provides step-by-step instructions to set up and run the project.

---

## Prerequisites

1. **Python**:
   - Version: 3.13.3
   - Ensure Python is installed and added to your system PATH.

2. **Node.js**:
   - Not required (no `package.json` detected).

3. **Virtual Environment**:
   - A virtual environment is recommended for Python dependency management.

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone <repository-url>
cd final-year-project-07
```

### 2. Create and Activate Virtual Environment
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file in the root directory with the following variables:
```env
# Example
SECRET_KEY=your_secret_key
DATABASE_URL=sqlite:///site.db
MAIL_SERVER=smtp.gmail.com
MAIL_PORT=587
MAIL_USE_TLS=True
MAIL_USERNAME=your_email@example.com
MAIL_PASSWORD=your_password
```

---

## Running the Application

### 1. Start the Backend Server
```bash
python app.py
```

### 2. Access the Application
- Open your browser and navigate to `http://127.0.0.1:5000`.

---

## Testing

### 1. Run Unit Tests
```bash
python -m unittest discover
```

---

## Notes
- Ensure all dependencies are installed in the virtual environment.
- Use the provided `.gitignore` to avoid committing sensitive files.
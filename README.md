# API Documentation

## Project Overview
This project provides a simple API that returns the current date and time in UTC format, along with the developer's email and GitHub repository URL.
Check out [HNG PYTHON REPO HERE](https://hng.tech/hire/python-developers)

## Features
- Accepts **GET** requests.
- Returns a JSON response containing:
  - Developer's email.
  - Current UTC datetime in ISO 8601 format.
  - GitHub repository URL.
- Provides an appropriate HTTP status code.
- Fast response time (< 500ms).

## API Endpoint

### **GET /api**

#### **Response (200 OK)**
```json
{
  "email": "<your-email@example.com>",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/codeWithGodstime/hng-stage-0"
}
```

## Setup Instructions

### **1. Clone the Repository**
```bash
git clone https://github.com/codeWithGodstime/hng-stage-0
cd hng-stage-0
```

### **2. Install Dependencies**
If using Python and FastAPI:
```bash
pip install fastapi uvicorn
```

### **3. Run the Server**
For FastAPI:
```bash
uvicorn main:app --host 0.0.0.0 --port 8000
```

## Deployment
The API is deployed at:
```
<your-deployed-url>
```

---
Developed by Godstime 🚀


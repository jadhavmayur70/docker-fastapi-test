Here's your enhanced `README.md` with logos and improved visual presentation:

```markdown
# 🚀 FastAPI Dockerization Project

<div align="center">
  <img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" width="200" alt="FastAPI">
  <img src="https://www.docker.com/wp-content/uploads/2022/03/vertical-logo-monochromatic.png" width="150" alt="Docker">
</div>

## 📋 Overview
This project demonstrates containerization of a FastAPI application with data persistence, completed as part of a DevOps machine test.

## ✨ Features
- 🐳 Dockerized FastAPI application
- 💾 Data persistence using Docker volumes
- 🔌 Three working API endpoints:
  - `📡 GET /` - Hello message
  - `📥 GET /users` - List all users
  - `📤 POST /users` - Add new user

## ⚙️ Prerequisites
- <img src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png" width="20"> Docker
- <img src="https://www.docker.com/wp-content/uploads/2022/03/docker-compose-logo.png" width="20"> Docker Compose

## 🛠️ Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/your-username/docker-fastapi-test.git
cd docker-fastapi-test

# 2. Build and run the containers
docker-compose up --build
```

🌐 Access the application:
- **API Docs (Swagger UI)**: http://localhost:8000/docs
- **Raw API**: http://localhost:8000

## 🔍 Testing Data Persistence
```bash
# 1. Add users via POST /users endpoint
# 2. Stop containers
docker-compose down

# 3. Restart
docker-compose up

# 4. Verify users still exist via GET /users
```

## 📂 Project Structure
```
docker-fastapi-test/
├── app/
│   ├── __init__.py
│   └── main.py         # FastAPI application code
├── data/               # Auto-created for persistent storage
├── Dockerfile          # Container configuration
├── docker-compose.yml  # Service definition
└── requirements.txt    # Python dependencies
```

## ✅ Verification
To confirm all requirements are met:
1. All endpoints work (check `/docs`)
2. Data persists after container recreation
3. No errors in logs (`docker-compose logs`)

## ⏰ Deadline
📅 Submitted by: **13-April-2025 (6 PM IST)**

<div align="center">
  <img src="https://img.shields.io/badge/Status-Completed-success" alt="Status">
  <img src="https://img.shields.io/badge/FastAPI-0.68.0-green" alt="FastAPI Version">
  <img src="https://img.shields.io/badge/Python-3.9-blue" alt="Python Version">
</div>
```


# 🚀 FastAPI Dockerization Project

<p align="center">
  <img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" width="200" alt="FastAPI">
  <img src="https://www.docker.com/wp-content/uploads/2022/03/vertical-logo-monochromatic.png" width="150" alt="Docker">
</p>

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
- <img src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png" width="20" alt="Docker"> Docker  
- <img src="https://www.docker.com/wp-content/uploads/2022/03/docker-compose-logo.png" width="20" alt="Docker Compose"> Docker Compose  

## 🛠️ Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/your-username/docker-fastapi-test.git
cd docker-fastapi-test

# 2. Build and run the containers
docker-compose up --build



```markdown
# Dockerized FastAPI Application

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/your-username/docker-fastapi-test.git
cd docker-fastapi-test
```

2. Start the application:
```bash
docker-compose up --build
```

3. Access the API:
- Interactive docs: http://localhost:8000/docs
- Base endpoint: http://localhost:8000

## ✅ Features
- Persistent data storage (users.json)
- Three working API endpoints
- Simple Docker setup

## 🛠️ Project Structure
```
.
├── app/
│   ├── __init__.py
│   └── main.py
├── data/
├── Dockerfile
├── docker-compose.yml
└── requirements.txt
```

## 📝 Verification
1. Add users via POST /users
2. Stop containers: `docker-compose down`
3. Restart: `docker-compose up`
4. Confirm data persists

📅 Submitted for DevOps evaluation - April 2025
```


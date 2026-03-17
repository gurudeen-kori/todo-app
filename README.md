# 📝 Todo App (Flask + PostgreSQL + Docker)

A full-stack Todo application built using **Flask**, **PostgreSQL**, and **Docker Compose**.

---

## 🚀 Features

- ➕ Add Todo
- ❌ Delete Todo
- ✔️ Mark as Complete / Undo
- ✏️ Edit Todo
- 📊 Total Tasks Counter
- 💾 Persistent storage using PostgreSQL
- 🐳 Fully Dockerized

---

## 🏗️ Tech Stack

- Backend: Flask (Python)
- Database: PostgreSQL
- Frontend: HTML, CSS, JavaScript
- Containerization: Docker & Docker Compose

---

## 📂 Project Structure


todo-app/

│── Dockerfile

│── docker-compose.yml

│── app/

│ ├── app.py

│ ├── models.py

│ ├── requirements.txt

│ └── templates/

│ └── index.html


---

## ⚙️ Setup & Run (Step-by-Step)

### 1️⃣ Clone Repository

```bash
git clone https://github.com/gurudeen-kori/todo-app.git
cd todo-app
2️⃣ Start Application
docker compose up --build
3️⃣ Stop Application
docker compose down
4️⃣ Restart Application
docker compose restart
5️⃣ Check Running Containers
docker compose ps
6️⃣ View Logs
docker logs todo-app
7️⃣ Enter App Container
docker exec -it todo-app sh
8️⃣ Enter Database (PostgreSQL)
docker exec -it todo-db psql -U todo_user -d todo_db
9️⃣ Check Database Tables
SELECT * FROM todo;
🌐 Access Application
```
Open browser:

http://localhost:5000
![alt text](todo.png)
🔗 API Endpoints
Get Todos
GET /todos
Add Todo
POST /todos
Update Todo
PUT /todos/<id>
Delete Todo
DELETE /todos/<id>
🐳 Docker Commands (Quick Reference)
# Build & start
docker compose up --build

# Stop
docker compose down

# Restart
docker compose restart

# Logs
docker logs todo-app

# Check containers
docker compose ps
🚀 Future Improvements

🔐 Authentication (Login/Signup)

📅 Due Dates

⚡ Redis Caching

☸️ Kubernetes Deployment

👨‍💻 Author
**Gurudeen Kori**

⭐ Support

If you like this project, give it a ⭐ on GitHub!

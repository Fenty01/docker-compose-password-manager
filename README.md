# Password Manager - Docker Compose Project

A secure, containerized password management application built with Docker Compose, featuring a multi-service architecture.

-----

## 🎯 What I Learned

- Docker Compose for multi-container orchestration
- Connecting frontend, backend, and database services
- Environment variables and secrets management
- Container networking and port mapping
- Volume persistence for databases

-----

## 🛠️ Technologies Used

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

-----

## 🏗️ Architecture

```
┌─────────────────┐     ┌─────────────────┐     ┌─────────────────┐
│    Frontend     │────▶│    Backend      │────▶│    MongoDB      │
│   (Vite/React)  │     │  (Node/Express) │     │   (Database)    │
│    Port 5173    │     │    Port 5000    │     │    Port 27017   │
└─────────────────┘     └─────────────────┘     └─────────────────┘
```

-----

## 📁 Project Structure

```
├── docker-compose.yml    # Multi-service configuration
├── frontend/             # React frontend application
├── backend/              # Node.js/Express API
├── .env                  # Environment variables
└── README.md
```

-----

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/Fenty01/Password-Manager.git

# Navigate to the project
cd Password-Manager

# Start all services
docker-compose up -d

# View running containers
docker-compose ps

# Stop all services
docker-compose down
```

-----

## 🌐 Access the Application

- **Frontend:** http://localhost:5173
- **Backend API:** http://localhost:5000

-----

## 📚 Resources

This project was built as part of my training at **CoderTech Africa**.

-----

*Part of my DevOps learning journey* ☁️

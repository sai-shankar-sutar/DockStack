# 🚀 Three-Tier Application Deployment with Docker Compose  
 

This repository demonstrates the deployment of a **three-tier MERN stack application** using **Docker Compose**.  
The stack includes:  
- 🖥 **React.js frontend**  
- ⚙️ **Node.js backend**  
- 🗄 **MySQL database**  

All services run inside **isolated Docker containers**, with **data persistence** ensured through Docker volumes.  

---

## 📦 Prerequisites  

Before running the project, install:  
- [Docker](https://www.docker.com/get-started)  
- [Docker Compose](https://docs.docker.com/compose/install/)  

---

## 📂 Project Structure  

.
├── frontend/ # React.js frontend (Dockerfile + code)
├── backend/ # Node.js backend (Dockerfile + code)
├── student-teacher-app/ # React app source code
├── docker-compose.yml # Service orchestration config


---

## ⚡ How to Run  

1. **Clone the repository**  
   ```bash
   git clone <repository-url>
   cd <repository-directory>


Start containers

docker-compose up -d


Open the app
Visit 👉 http://localhost:80
 in your browser.

## 💾 Data Persistence

MySQL data is stored in Docker volumes

Data is preserved even if the container is removed

Restarting with the same volume automatically restores the database


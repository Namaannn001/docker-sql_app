
# 🚀 SQL App — Full Stack Web App

![Docker](https://img.shields.io/badge/docker-ready-blue)   
![License](https://img.shields.io/badge/license-MIT-green)

---

A full-stack web application built with:

- 🖥️ **Frontend:** Static HTML, CSS, and JavaScript (`public/`)
- 🧠 **Backend:** Python Flask API (`src/`)
- 🗄️ **Database:** SQLite
- 🐳 **Deployment:** Dockerized for easy setup

---

## 📁 Project Structure

```
public/
  ├── index.html
  ├── styles.css
  └── script.js

src/
  ├── app.js
  ├── database.js
  └── routes.js

Dockerfile
package.json
package-lock.json
```

---

## 🌐 Live Application

Once deployed, the app will be accessible at:

```
http://localhost:3000
```

You can interact with the frontend and backend APIs easily.

---

## 🐳 Running with Docker

### 1. Pull the Image

```bash
docker pull namaannn/sql-app:latest
```
---

### 2. Run the Container

```bash
docker run -d -p 3000:3000 namaannn/sql-app
```

### 3. Access the App

Navigate to:

```
http://localhost:3000
```

---

## 🧰 Local Development Setup

If you want to run the app **without Docker**, follow these steps:

Here’s a clean and professional `README.md` file you can use for your project (`docker-sql_app-main`). It includes both **Docker** and **local (non-Docker)** usage instructions:

---


# SQL-Based Full Stack Node.js App

This is a full-stack Node.js application built with Express.js, which serves a simple frontend and connects to a backend database (SQL-based). The app can run both locally and inside a Docker container.

## 📁 Project Structure

```

docker-sql\_app-main/
│
├── src/               # Application source code
│   ├── app.js         # Main server file
│   ├── routes.js      # Routes definitions
│   └── database.js    # Database connection logic
│
├── public/            # Static frontend files (HTML/CSS/JS)
├── package.json       # Node.js dependencies and scripts
├── Dockerfile         # Docker setup file
└── README.md          # Project documentation

````

---

## 🚀 Features

- Node.js & Express-based backend
- SQL database integration
- Static frontend served from `/public`
- Docker support for containerized deployment

---

## 🔧 Prerequisites

To run locally:
- Node.js & npm
- (Optional) MySQL or any SQL DB running if connected

To run with Docker:
- Docker installed on your system

---

## 🛠️ Setup Instructions

### ▶️ Run Locally (Without Docker)

```bash
# 1. Clone or download this repository
cd docker-sql_app-main

# 2. Install dependencies
npm install

# 3. Start the server
node src/app.js

# 4. Visit the app
http://localhost:3000
````

> Make sure your database (if used) is running and connected in `src/database.js`.

---

### 🐳 Run With Docker

```bash
# 1. Build the Docker image
docker build -t namaannn/sql-app .

# 2. Run the container on port 3000
docker run -d -p 3000:3000 namaannn/sql-app

# 3. Visit the app
http://localhost:3000
```

---

## 🔍 Debugging Tips

* Check logs:

  ```bash
  docker logs <container_id>
  ```

* Check if container is running:

  ```bash
  docker ps
  ```

---

## 🧹 Docker Cleanup Commands

Stop and remove the container:

```bash
docker ps
docker stop <container_id>
docker rm <container_id>
```

---

## 🤝 Contributing

Contributions are welcome!  
If you'd like to improve the app, please fork the repository and create a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

# 🙌 Thank you for checking out SQL App!
Feel free to ⭐️ the repo if you find it helpful!

---

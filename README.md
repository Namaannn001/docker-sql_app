
# 🚀 SQL App — Full Stack Web App

![Docker](https://img.shields.io/badge/docker-ready-blue)  
![Python](https://img.shields.io/badge/python-3.8%2B-blue)  
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
  ├── app.py
  ├── database.py
  └── routes.py

Dockerfile
package.json
package-lock.json
```

---

## 🌐 Live Application

Once deployed, the app will be accessible at:

```
http://localhost:5000
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
docker run -d -p 5000:5000 namaannn/sql-app
```

### 3. Access the App

Navigate to:

```
http://localhost:5000
```

---

## 🧰 Local Development Setup

If you want to run the app **without Docker**, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/namaannn001/sql-app.git
cd sql-app
```

---

### 2. Create a Python Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate  # (Linux/Mac)
venv\Scripts\activate     # (Windows)
```

---

### 3. Install Python Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Run the Flask Server

```bash
cd src
python app.py
```

The app should now be available at [http://localhost:5000](http://localhost:5000).

---

## 📜 API Overview

Example routes (based on `routes.py`):

| Method | Endpoint        | Description            |
|:-------|:-----------------|:------------------------|
| GET    | `/api/data`      | Fetch records            |
| POST   | `/api/data`      | Insert new record         |

*(You can expand this section based on your exact routes.)*

---

## 📋 Requirements

- Python 3.8+
- Flask
- SQLite (comes built-in)
- Node.js (optional, only if you modify frontend tools)

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

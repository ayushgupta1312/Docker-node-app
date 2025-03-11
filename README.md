# 🐳 Node.js and MongoDB Application with Docker

A Dockerized Node.js application integrated with MongoDB for efficient development and deployment.

## 📌 Overview

This project demonstrates a **Node.js** application connected to a **MongoDB** database, both running in **Docker** containers orchestrated by **Docker Compose**. This setup ensures a consistent and reproducible development environment.

## 🚀 Features

- **Containerized Application**: Utilizes Docker for both Node.js and MongoDB services.
- **Efficient Orchestration**: Employs Docker Compose for simplified multi-container management.
- **Scalable Architecture**: Facilitates easy scaling of services.
- **Isolated Environment**: Ensures dependencies are encapsulated within containers.

## 🛠️ Prerequisites

Before setting up the project, ensure you have the following installed:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)


## 🏗️ Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/ayushgupta1312/Docker-node-app.git
cd Docker-node-app
```

### 2️⃣ Build and Run the Docker Container
```docker-compose up --build -d```

### 3️⃣ Access the App: 
Open your web browser and navigate to ```http://localhost:5050```.

### 4️⃣ Access the Database: 
Open your web browser and navigate to ```http://localhost:27017```.

### 5️⃣ Stop the Container
```docker-compose down```

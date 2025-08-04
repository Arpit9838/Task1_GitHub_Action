# 🟢 Node.js Welcome Web Server + GitHub Actions CI/CD

This project is a beginner-friendly Node.js web server using the `http` core module. It serves a welcome page and is containerized with Docker. GitHub Actions automatically builds and pushes the image to DockerHub.

## 🚀 Features

- Node.js server with HTTP module
- HTML + CSS Welcome page
- Dockerized
- CI/CD with GitHub Actions

## 📦 Run Locally

```bash
# Start server
node server.js

# OR with Docker
docker build -t nodejs-welcome-server .
docker run -p 3000:3000 nodejs-welcome-server

# CI/CD Node.js Demo App

This is a simple Node.js Express app used to demonstrate Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions and Docker.

## 🚀 How it works

- On every push to the `main` branch:
  - The code is checked out by GitHub Actions
  - Node.js dependencies are installed
  - A Docker image is built from the code
  - The image is pushed to DockerHub automatically

## 📦 Files included

- `app.js` — Main Express server
- `package.json` — Node.js dependencies
- `Dockerfile` — For containerizing the app
- `.github/workflows/main.yml` — GitHub Actions CI/CD workflow

## 🧑‍💻 Author

**Nagesh B R**  
DockerHub: [nageshbr7122003@gmail.com](https://hub.docker.com/u/nageshbr7122003@gmail.com)  
GitHub: [https://github.com/N-a-g-e/day1_task](https://github.com/N-a-g-e/day1_task)

## 🗓 Last updated

August 4, 2025

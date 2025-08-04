# CI/CD Node.js Demo App

This is a simple Node.js Express app for demonstrating CI/CD with GitHub Actions and Docker.

## How it works
- On push to `main` branch:
  - App is built inside a Docker container
  - Image is pushed to DockerHub

## Files included
- `app.js` - Main app
- `Dockerfile`
- `.github/workflows/main.yml`

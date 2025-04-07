# Node.js Demo App with CI/CD

This is a simple Node.js app deployed using a CI/CD pipeline powered by GitHub Actions and Docker.

## Features
- Express.js Web App
- Dockerized
- GitHub Actions CI/CD Workflow
- DockerHub Image Push

## Usage

### Run Locally
```bash
npm install
npm start
```

### CI/CD Pipeline
- Triggered on push to `main`
- Runs tests
- Builds Docker image
- Pushes image to DockerHub

## Secrets Needed
- `DOCKER_USERNAME`
- `DOCKER_PASSWORD`

Add them in your GitHub repository → Settings → Secrets → Actions.

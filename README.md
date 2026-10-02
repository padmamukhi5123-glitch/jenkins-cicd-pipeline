# Jenkins CI/CD Pipeline

This project demonstrates a basic CI/CD pipeline using Jenkins, GitHub, Node.js, and Docker.

## Technologies Used

- GitHub
- Jenkins
- Node.js
- Docker
- Linux

## Pipeline Stages

1. **Build** - Installs Node.js dependencies using npm.
2. **Test** - Checks the application file and verifies Node.js and npm.
3. **Docker Build** - Creates a Docker image for the application.
4. **Deploy** - Completes the deployment stage.

## Pipeline Flow

GitHub → Jenkins → Build → Test → Docker Build → Deploy

## Docker Image

Docker image name:

`jenkins-node-app:latest`

## Result

The Jenkins pipeline successfully completed with:

`Finished: SUCCESS`

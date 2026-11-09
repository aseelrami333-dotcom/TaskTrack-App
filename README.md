# TaskTrack App

## About the Project

TaskTrack is a simple web application that helps users manage their daily tasks. Users can add tasks, mark them as completed, and delete tasks.

I built this project using Python and Flask, and used Docker to run the application inside a container.

## Technologies Used

- Python
- Flask
- HTML and CSS
- Docker
- Git and GitHub

## Project Structure

```text
TaskTrack-App/
|-- src/
|   |-- app.py
|   |-- templates/
|       |-- index.html
|-- docs/
|   |-- screenshots/
|-- Dockerfile
|-- .dockerignore
|-- .gitignore
|-- requirements.txt
|-- README.md
```

## How to Run the Project

Make sure Docker Desktop is running before starting the application.

Build the Docker image:

```bash
docker build -t tasktrack-app .
```

Run the container:

```bash
docker run -d -p 5000:5000 --name tasktrack-container tasktrack-app
```

Open the application in your browser:

http://localhost:5000

## Screenshots

The following screenshots show the application and Docker setup:

- Project working: docs/screenshots/project-working.png
- Docker build: docs/screenshots/docker-build-success.png
- Docker container running: docs/screenshots/container-running.png
- Docker project: docs/screenshots/docker-project-working.png
- GitHub commits: docs/screenshots/github-commits.png
- GitHub commits history: docs/screenshots/github-commits-history.png

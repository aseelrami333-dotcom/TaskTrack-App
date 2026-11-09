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

```powershell
docker run -d -p 5000:5000 `
  --name tasktrack-container `
  tasktrack-app
```

Open the application in your browser:

http://localhost:5000

## Screenshots

The following screenshots show the application and Docker setup.

### 1. Project Working

![Project Working](docs/screenshots/project-working.png)

### 2. Docker Build

![Docker Build](docs/screenshots/docker-build-success.png)

### 3. Docker Container Running

![Docker Container Running](docs/screenshots/container-running.png)

### 4. Docker Project

![Docker Project](docs/screenshots/docker-project-working.png)

### 5. GitHub Commits

![GitHub Commits](docs/screenshots/github-commits.png)

### 6. GitHub Commits History

![GitHub Commits History](docs/screenshots/github-commits-history.png)

## How to Stop the Container

To stop the running container, use:

```bash
docker stop tasktrack-container
```

## How to Clean Up

To remove the stopped container, use:

```bash
docker rm tasktrack-container
```

To remove the Docker image, use:

```bash
docker rmi tasktrack-app
```

## Application Testing

After starting the container, open the following URL in your browser:

http://localhost:5000

The application can be tested by performing the following actions:

- Add a new task.
- Mark a task as completed.
- Delete a task.

These tests help verify that the main application features are working correctly.

## Configuration

- Application port: 5000
- Docker port mapping: 5000:5000
- Container name: tasktrack-container
- Docker image name: tasktrack-app

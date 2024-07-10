Full-Stack FastAPI and React Application Setup Guide

Introduction
Welcome to the Full-Stack FastAPI and React template repository! In this guide, we’ll cover everything you need to know to set up and run your own full-stack application. By the end, you’ll have a working application with a FastAPI backend and a ReactJS frontend.

Prerequisites
Before we dive into the setup, make sure you have the following installed on your system:

Docker: We’ll use Docker to manage our containers.
Docker Compose: This tool simplifies managing multi-container applications.
Step 1: Clone the Repository
Start by cloning the repository:

git clone <repository_url>.git
cd Full-Stack-Web-App

Replace <repository_url> with the actual URL of your repository.

Step 2: Build and Start the Services
Inside the project directory, run the following commands:

docker-compose build
docker-compose up -d

This will build the necessary images and start the services in detached mode.

Step 3: Verify Services
Make sure everything is up and running:

FastAPI Backend: Visit http://localhost/api.
Node.js Frontend: Open http://localhost in your browser.
Azure PostgreSQL Database: Accessible on port 5432 (no direct browser access).
Adminer: Visit http://localhost:8080 or http://db.localhost to manage the database.

Step 4: Custom Domain
If you have a custom domain, you can set it up to connect to the application using Nginx Proxy Manager. Adjust the configuration as needed.

Conclusion:

Congratulations! You’ve successfully set up your Full-Stack FastAPI and React application. Feel free to explore the code, customize it, and build amazing features on top of this foundation.

- [Frontend README](./frontend/README.md)
- [Backend README](./backend/README.md)


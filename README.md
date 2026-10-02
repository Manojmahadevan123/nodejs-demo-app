# Node.js CI/CD Pipeline

## Project Overview

This project demonstrates a CI/CD pipeline for a Node.js web application using GitHub Actions and Docker.

## Technologies Used

- Node.js
- GitHub
- GitHub Actions
- Docker
- Docker Hub

## Application

The Node.js application runs on port 3000 and displays:

Hello! CI/CD Pipeline is working.

## CI/CD Pipeline

The GitHub Actions workflow automatically runs when code is pushed to the `main` branch.

Pipeline steps:

1. Checkout the source code
2. Setup Node.js
3. Install dependencies
4. Run tests
5. Login to Docker Hub
6. Build the Docker image
7. Push the Docker image to Docker Hub

## Docker Image

Docker Hub repository:

manojmahadevan/nodejs-demo-app

## How to Run Locally

Install dependencies:

```bash
npm install

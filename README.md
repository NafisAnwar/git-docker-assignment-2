# Git and Docker Starter Application

This repository contains a small Python web application used to practice Git, GitHub, and Docker workflows.

## Application

The application listens on port 8000, returns a health status response, and can be accessed from Docker containers over HTTP.

## Verification

The running application should be verified using an HTTP request to port 8000.

## Usage

Build the Docker image:

```bash
docker build -t git-docker-app:test .
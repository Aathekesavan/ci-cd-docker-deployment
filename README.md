# End-to-End CI/CD Pipeline with GitHub Actions & Docker

This project demonstrates a production-style CI/CD pipeline using Docker and GitHub Actions.

## Tech Stack
Python Flask
Docker
GitHub Actions
DockerHub
AWS EC2

## Project Structure

ci-cd-docker-deployment
│
├── app
├── tests
├── Dockerfile
├── docker-compose.yml
└── README.md

## Pipeline Flow

Developer Push → GitHub Actions → Build Docker Image → Push to DockerHub → Deploy to EC2
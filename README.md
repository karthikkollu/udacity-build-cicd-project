# Movie Picture - Full Stack CI/CD Project

## Project Overview

This project is a full-stack Movie Picture application developed using React and Python Flask and deployed using Docker, Kubernetes, Amazon Web Services (AWS), Amazon Elastic Kubernetes Service (EKS), and GitHub Actions.

The application displays a list of movies through a React frontend. The frontend communicates with a Flask backend REST API to retrieve movie information.

The project demonstrates a complete Continuous Integration and Continuous Deployment (CI/CD) workflow using GitHub Actions.

---

## Project Objectives

The main objectives of this project are:

- Develop a full-stack web application.
- Create a REST API using Python Flask.
- Create a frontend application using React.
- Containerize applications using Docker.
- Deploy applications using Kubernetes.
- Use Amazon EKS for Kubernetes deployment.
- Use Amazon ECR for Docker images.
- Implement Continuous Integration using GitHub Actions.
- Implement Continuous Deployment using GitHub Actions.
- Test and verify both frontend and backend applications.
- Provide deployment and workflow evidence through screenshots.

---

## Application Features

The application provides the following features:

- Display a list of movies.
- Select a movie from the movie list.
- Display details of the selected movie.
- React-based frontend.
- Flask-based backend REST API.
- Dockerized frontend.
- Dockerized backend.
- Kubernetes deployment.
- AWS EKS deployment.
- LoadBalancer services.
- Automated CI workflows.
- Automated CD workflows.

---

# Technologies Used

## Frontend

- React
- JavaScript
- Axios
- HTML
- CSS
- Node.js
- npm

## Backend

- Python
- Flask
- REST API

## Containerization

- Docker
- Amazon Elastic Container Registry (ECR)

## Cloud

- Amazon Web Services (AWS)
- Amazon Elastic Kubernetes Service (EKS)
- Amazon EC2
- Elastic Load Balancer

## DevOps

- GitHub Actions
- Kubernetes
- kubectl
- CI/CD

## Infrastructure

- Terraform
- AWS infrastructure

---

# Project Architecture

The application follows the architecture below:

```text
                         USER
                           |
                           v
                Frontend LoadBalancer
                           |
                           v
                    React Frontend
                           |
                           | HTTP Request
                           v
                Backend LoadBalancer
                           |
                           v
                    Flask Backend
                           |
                           v
                       Movie API

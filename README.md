# Go Web Application

This is a simple web application built with Golang. It serves HTTP requests using the `net/http` package and provides a basic API.

## Features

- Built using Golang with the `net/http` package.
- Serves a REST API for retrieving course information.
- Dockerized for easy deployment.
- Kubernetes manifests and Helm charts for scalable deployment.
- CI/CD automation using GitHub Actions and ArgoCD.

## Running the Server

To start the server locally, run:

```bash
go run main.go
```

The server will start on port `8080`. You can access the API at:  

```bash
http://localhost:8080/courses
```
## Running with Docker  

To build and run the Docker container:  

```bash
docker build -t yourusername/go-web-app:v1 .
docker run -p 8080:8080 -it yourusername/go-web-app:v1
```
## Looks like this

![Website](static/images/golang-website.png)

## 🏗️ Key Highlights  

- **CI/CD Automation:** Implemented using GitHub Actions for Continuous Integration and ArgoCD for Continuous Deployment.  
- **Containerized Deployment:** The application runs in a Docker container for easy portability.  
- **Kubernetes Orchestration:** Uses Kubernetes manifests and Helm for automated deployments.  
- **Security & Code Quality:** Includes static analysis and testing in the CI pipeline.  


## 🛠️ Tools & Technologies Used  

- **Programming Language:** Golang  
- **Containerization:** Docker  
- **Orchestration:** Kubernetes  
- **CI/CD:** GitHub Actions & ArgoCD  
- **Infrastructure as Code:** Helm  

## 📖 Read the Full Blog  

For a detailed walkthrough of this project, check out my blog post:  
[**Mastering DevOps: Transforming a Go Web App with End-to-End Automation**](https://itspraduman.hashnode.dev/mastering-devops-transforming-a-go-web-app-with-end-to-end-automation) 🚀  

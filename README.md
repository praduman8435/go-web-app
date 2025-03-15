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



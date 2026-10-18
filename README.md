
# Charan's Cloud DevOps Project

## Project Overview
A simple static website hosted using Docker and Nginx. This project demonstrates basic containerization and web hosting skills.

## Technologies Used
- Docker
- Nginx
- HTML and CSS
- Git and GitHub

## Project Files
- `Dockerfile` - Builds the Docker image using Nginx.
- `index.html` - Contains the website content and styling.
- `README.md` - Project documentation.

## How to Run

### 1. Build the Docker image
```bash
docker build -t charan-website:v2 .
```

### 2. Run the container
```bash
docker run -d --name charan-website-web -p 8080:80 charan-website:v2
```

### 3. Open the website
Visit this URL in your browser:

http://localhost:8080

### 4. Stop the container
```bash
docker stop charan-website-web
```

## Skills Demonstrated
- Creating a Docker image with a Dockerfile
- Running an Nginx web server in a container
- Mapping container ports to the host machine
- Using Git and GitHub for version control

## Author
Charan H C


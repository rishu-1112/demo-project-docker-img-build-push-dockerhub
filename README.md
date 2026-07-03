# Age Calculator

A modern, responsive web application for calculating age. Built with HTML/CSS and containerized with Docker for easy deployment.

## Features

- **Simple & Fast**: Calculate age instantly with a clean, intuitive interface
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful gradient background with frosted glass effect
- **Containerized**: Docker-ready for quick deployment anywhere

## Prerequisites

- Docker installed on your system

## Installation & Usage

### Build the Docker Image

```bash
docker build -t age-calculator .
```

### Run the Container

```bash
docker run -p 8080:80 age-calculator
```

Then open your browser and navigate to:
```
http://localhost:8080
```

## Project Structure

- `Dockerfile` - Docker configuration using Nginx Alpine
- `index.html` - Single-page application with age calculation logic

## How It Works

1. Enter your date of birth
2. Click the calculate button
3. View your age instantly

## Technology Stack

- **Frontend**: HTML5, CSS3
- **Server**: Nginx (Alpine Linux)
- **Container**: Docker

## License

Open source project

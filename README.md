# Automate Application Deployment with GitHub Actions

## Description

This project sets up a CI/CD pipeline using GitHub Actions to automate the deployment of a simple web application. The app is containerized with Docker.

## Technologies

- **GitHub Actions**: CI/CD automation
- **Docker**: Containerization

## Setup

1. **Clone the Repo**:

   ```bash
   git clone https://github.com/OtowoSamuel/simple-web-app.git
   cd simple-web-app
   
2. **Create Dockerfile**
   
3. **Create package.json**

4. **Build and Run Docker Container:**
   ```bash
   docker build -t your-image-name .
   docker run -p 3000:3000 your-image-name
   
5. **Set Up GitHub Actions:**
   Create .github/workflows/main.yml
   
6. ** Configure Secrets:**
   Go to Settings > Secrets and variables > Actions and add:
   DOCKER_USERNAME
   DOCKER_PASSWORD

## Testing
Push changes to the master branch to trigger the pipeline. Monitor in the Actions tab of the GitHub repository.

    

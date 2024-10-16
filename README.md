# Automated Deployment Pipeline with Jenkins and Docker

This project demonstrates the automation of the CI/CD process for a Python web application using Jenkins and Docker.

## Prerequisites

- Docker installed
- Jenkins installed
- Git installed

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/automated-deployment-pipeline.git
   ```
2. Navigate to the project directory:

   ```bash
   cd automated-deployment-pipeline
   ```
3. Build the Docker image:
   ```bash
   docker build -t myapp:latest .
   ```

4. Run the Docker container:
   ```bash
   docker run -p 5000:5000 myapp:latest
   ```
5. Open your browser and go to http://localhost:5000 to see the running application.


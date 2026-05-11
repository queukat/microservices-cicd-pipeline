# Automated Deployment Pipeline with Jenkins and Docker

<!-- public-repo-status -->
> Status: Legacy/reference. This repository is kept public as a DevOps example, but it is not actively supported. Issues and pull requests are disabled unless support is reopened.


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
## License

<!-- commercial-license-policy -->
This project is licensed for non-commercial use under the [PolyForm Noncommercial License 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0/).
Commercial use, resale, paid distribution, marketplace publication, SaaS hosting, or bundling into a paid product requires separate written permission from the author.
Project names, logos, package identifiers, store listings, screenshots, and other branding assets are not licensed for use in forks or redistributed builds.

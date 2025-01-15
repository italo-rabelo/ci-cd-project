## In this project, a simple Python service was developed in order to define and create a CI/CD pipeline.
A service called "counter-service" will maintain a web page with a counter for the number os POST requests it has served and return it for every GET requests it gets.
Some tools was used, as GitHub Actions, Docker, Sonar Cloud, Snyk and AWS services.

## Project goals and instructions:
- A service named "counter-service" to count POST requests and return the count in every GET request.
- The counter-service needs to be exposed on port 80.
- Build the service into a Docker image, save it on Elastic Container Registry(ECR) and deploy it as a container to the EC2 instance.
- Upon commit and push, the code should pass CI/CD and end up as a running Docker container in the EC2 instance.

## Implementation steps:
1. Create a GitHub repo and clone it locally.
2. Develop the counter-service app in Python, run it, and test it locally.
3. Create a Dockerfile for the counter-service app, build an image, run and test it locally.
4. On AWS, create an EC2 Ubuntu instance and install Docker and Docker Compose on it.
5. Push your code to GitHub.
6. Create an ECR Repository.
7. Write GitHub Actions for **CI** (build the image and push it to ECR).
8. Add the Sonar Cloud and Snyk tests for **CI**.
9. Write GitHub Actions for **CD** (pull the image from ECR to EC2 instance and run it using Docker Compose).

### Objectives and References
I implemented this project to learn and apply Devops and CI/CD concepts and tools.
This project isn't of my authority. It is defined on <a href="https://medium.com/devops-technical-notes-and-manuals/devops-example-project-for-your-resume-198e34d874b4">Andrey Byhalenko's Medium page<a/>.

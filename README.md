# Node.js CI/CD Pipeline with GitHub Actions

This repository contains a simple Node.js application and a fully automated CI/CD pipeline built using GitHub Actions.

The purpose of this project was to demonstrate the ability to build, test, and deploy a containerized application automatically upon code changes.

---

### CI/CD Pipeline Overview

The pipeline is configured to run on every push to the main branch. The automated workflow performs the following steps:

1.  *Build:* The workflow builds a Docker image of the Node.js application.
2.  *Deploy:* The newly built Docker image is then deployed.

The entire process is automated, ensuring that any code changes are quickly and reliably deployed.

---

### Technologies Used

* *Node.js:* The core programming language for the web application.
* *Docker:* Used to containerize the application for consistent builds and deployments.
* *GitHub Actions:* The CI/CD platform used to automate the entire pipeline workflow.

---

### How to Run Locally

You can easily run this application on your local machine using Docker.

1.  Clone the repository:
    git clone https://github.com/poojayenugula/nodejs-demo-app.git

2.  Navigate to the project directory:
    cd nodejs-demo-app

3.  Build and run the Docker container:
    docker-compose up --build
    
The application should now be running at http://localhost:3000.

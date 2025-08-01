# imbula-web-app
# Java Web App Deployment with AWS CI/CD

Welcome to this project combining Java web app development and AWS CI/CD tools!

<br>

## Intorduction to the project
This project is used for an introduction to creating and deploying a Java-based web app using AWS, especially their CI/CD tools.

The deployment pipeline I'm building arroung the Java web app in this repo is invisible to the end-user , but makes a big impact by automating the software release processes.

<br>

## Technologies

- **Amazon EC2**: I'm developing my web app on amazon ec2 instance.
- **VSCode**: For my IDE, I chose visual studion code, it connect to the ec2 instance and help me to edit the code and manage files in the cloud.
- **GitHub**: All my web app code is stored and virsioned in this GitHub repo.
- **AWS CodeArtifact**: Store the artifacts and the dependencies.
- **AWS CodeBuild**: CodeBuild will take over the build process. It will compile, run test cases, and make the software package.
- **AWS CodeDeploy**: codeDeploy will automate the deployment process across EC2 instance.
- **AWS CodePipeline**: Automate the process from GitHub to CodeDeploy, integrating build, test, and deployment steps into the one workflow.

<br>

## Setup
To get this project up and running on your local machine, folow these steps:

1. Clone the repo:
   ```bash
   git clone https://github.com/GayanS22/imbula-web-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd imbula-web-app
   ```
3. Install dependencies:
   ```bash
   mvn install
   ```

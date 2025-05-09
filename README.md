# Java Web App Deployment with AWS CI/CD

Welcome to this project combining Java web app development and AWS CI/CD tools!

<br>

## Table of Contents
- [Introduction](#introduction)
- [Technologies](##technologies)
- [Setup](#setup)
- [Documentation](#documentation)
- [Contact](#contact)
- [Conclusion](#conclusion)

<br>

## Introduction
This project is used for an introduction to creating and deploying a Java-based web app using AWS, especially their CI/CD tools. 

The deployment pipeline I'm building around the Java web app in this repository is invisible to the end-user, but makes a big impact by automating the software release processes.

- I'm doing this project to learn more about CI/CD and get hands on experience in automating the flow from developing code to deployed web app.
- This fits into my career goals as I have an ambition to become a DevOps/Cloud Engineer this year! 

<br>

## Technologies
Here's what I'm using for this project:

- **Amazon EC2**: I'm developing a web app on Amazon EC2 virtual servers, so that software development and deployment happens entirely on the cloud.
- **VSCode**: For my IDE, I chose Visual Studio Code. It connects directly to my development EC2 instance, making it easy to edit code and manage files in the cloud.
- **GitHub**: All my web app code is stored and versioned in this GitHub repository. 
- **AWS CodeArtifact**: Once it's rolled out, CodeArtifact will store my artifacts and dependencies, which is great for high availability and speeding up my project's build process.
- **AWS CodeBuild**: Once it's rolled out, CodeBuild will take over my build process. It'll compile the source code, run tests, and produce ready-to-deploy software packages automatically.
- **AWS CodeDeploy**: Once it's rolled out, CodeDeploy will automate my deployment process across EC2 instances.
- **AWS CodePipeline**: Once it's rolled out, CodePipeline will automate the entire process from GitHub to CodeDeploy, integrating build, test, and deployment steps into one efficient workflow.
- **AWS CloudFormation**: Using Infrastructure as Code (IaC) to deploy my resources instead of clicking around in the AWS console.

<br>

## Setup
To get this project up and running on your local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/feaq-collab/nextwork-web-project.git
    ```

2. Navigate to the project directory:
    ```bash
    cd nextwork-web-project
    ```

3. Install dependancies:
    ```bash
    mvn install
    ```

<br>

## Documentation
Documenting my hands-on journey through the 7-Day DevOps Challenge by NextWork. This **[Google Doc](https://docs.google.com/document/d/1O8xRkWVV1aKhy026ufu6eLHr_4xl5a8dcH3rJVMKfEY/edit?usp=sharing)** captures my daily progress, technical hurdles, and how I overcame them — from launching my first EC2 instance to connecting CI/CD pipelines. A raw and real behind-the-scenes look into learning cloud and DevOps from scratch.

<br>

## Contact
If you have any questions or comments about this project, you can contact me via my email:
Syafiq - [syafiq_ahmad@outlook.com](mailto:syafiq_ahmad@outlook.com)

- [LinkedIn](https://www.linkedin.com/in/feaq/)

<br>

## Conclusion
Thank you for exploring this project! I'll continue to build this pipeline and apply my learnings to future projects

A big shoutout to **[NextWork](https://learn.nextwork.org/)** for their project guide and support. [You can get started with this DevOps series project too by clicking here!](https://learn.nextwork.org/projects/aws-devops-vscode?track=high)

<br>

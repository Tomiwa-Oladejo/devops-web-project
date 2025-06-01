# Java Web App Development with AWS CI/CD

Welcome to this project combining Java web app development and CI/CD tools

<br>

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)
- [Contact](#contact)

<br>

## Introduction
This project includes the creation and deployment of a Java-based web app using AWS, with a focus on the CI/CD tools. The deveoplment pipeline that has been built around the Java web app within this repository is invisible to the end-user, but makes a big impact through the automation of the software release processes.

I have an interest in DevSecOps and cloud security which acted as the spark for the venture into this project. As a result, I was able to learn more about CI/CD pipelines, in addition to gaining hands on experience in automating the flow from developing code to deployomg web apps.

<br>

## Technologies
Here's what I am using for this project:

- **Amazon EC2**:  The web app is developed on Amazon EC2 virtual servers, so that software development and deployment takes place entirely on the cloud.
- **Key Pairs**: Used for SSH (Secure Shell) authentication to Linux instances.
- **SSH Connections**: An SSH connection starts a secure shell connection to your EC2 instance.
- **VSCode**: The chosen IDE is Visual Studio Code. It connects directly to the development EC2 instance, streamlining the process of editing code and managing files in the cloud.
- **Maven**: Apache Maven is a build automation and project management tool primarily used for Java projects.
- **Java - Amazon Correto 8**: Java is a programming language which Maven requires to operate. Amazon Corretto 8 is a version of Java that was used for this project.
- **Git**: A distributed version control system used to track changes in source code during software development. It helps teams and individuals collaborate, manage changes, and maintain a history of a project's evolution.
- **Github**: All the web app code is stored and versioned in this Github repository.
- **[COMING SOON] AWS CodeArtifact**: CodeArtifact stores the artifacts and dependencies, which is beneficial for high availability and speeding up the project's build process.
- **[COMING SOON] AWS CodeBuild**: Takes over the build process by compliing the source code, runtests, and producing ready-to-deploy software packages automatically.
- **[COMING SOON] AWS CodeDelploy**: Used to automate the deployment process across EC2 instances.
- **[COMING SOON] AWS CodePipeline**: CodePipeline automates the entire process from Github to CodeDeploy, integrating build, test and deployment steps into one efficient workflow.

<br>

## Setup
To get this project up and running on your local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Tomiwa-Oladejo/devops-web-project
    ```

2. Navigate to the project directory:
    ```bash
    cd devops-web-project
    ```

3. Install dependencies:
    ```bash
    mvn install
    ```

<br>

## Contact
If you have any questions or comments about the project, please contact here:

- [tommdej@gmail.com](mailto:tommdej@gmail.com)

- [LinkedIn](https://www.linkedin.com/in/tomiwa-oladejo/)

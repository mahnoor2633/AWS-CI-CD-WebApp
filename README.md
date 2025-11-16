# AWS-CI-CD-WebApp
A complete CI/CD pipeline automation that takes code from commit to production. 

In this project, I designed and implemented a complete end-to-end CI/CD pipeline on AWS to automate the build, packaging, and deployment of a Java-based application.

I began by provisioning a development EC2 environment, installing all build and deployment dependencies, and connecting it to GitHub for version-controlled source management. I then configured an AWS CodeArtifact repository to store build materials and artifacts, and linked it to the development server for seamless dependency retrieval. After compiling the application and generating artifacts, I created an AWS CodeBuild project capable of simultaneously pulling source code from GitHub and dependencies from CodeArtifact to automatically produce versioned .WAR files.

To ensure reliable and reproducible infrastructure, I developed an AWS CloudFormation template that provisions a fully configured production EC2 instance, including Apache as the web server and Tomcat as the Java application server. I then configured an AWS CodeDeploy application to take the compiled .WAR file and deploy it onto the production environment.

Finally, I orchestrated all components using AWS CodePipeline, enabling an automated workflow that triggers on every commit to the GitHub repository. The pipeline performs source retrieval, builds artifacts, stores them, and deploys to production without manual intervention.

This project demonstrates practical experience with DevOps automation, CI/CD orchestration, infrastructure as code, artifact management, cloud-native deployment pipelines, and environment segregation, culminating in a fully automated and repeatable delivery process.

This project demonstrates the following DevOps concepts:

Continuous Integration (CI) using AWS CodeBuild
Continuous Deployment (CD) using AWS CodeDeploy
Infrastructure as Code (IaC) using AWS CloudFormation
Artifact Management using AWS CodeArtifact
Version Control Integration using GitHub & Git
Build Automation, Deployment Automation, and Pipeline Orchestration using AWS CodePipeline
Security Best Practices through IAM roles, service permissions, and least-privilege access control
Environment Segregation using separate development and production EC2 instances

Following documentation can be viewed for a complete guide to the project:
https://docs.google.com/document/d/1seSUfsipcPQwsLLR5NMI1C2FdWmpSlAWKa-u4pDIjFg/edit?usp=sharing

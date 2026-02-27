This project demonstrates how to build a fully automated CI/CD pipeline on AWS that takes a Java web application from source code to production deployment without manual intervention. The pipeline integrates AWS DevOps services to enable continuous integration, artifact management, infrastructure provisioning, and automated deployment.

🚀 **PROJECT OVERVIEW**

The pipeline automates:

- Source code integration from GitHub

- Application build and artifact generation

- Secure artifact storage

- Infrastructure provisioning using Infrastructure-as-Code

- Automated deployment to a production EC2 instance

- The result is a streamlined, zero-touch deployment workflow.

🏗 **ARCHITECTURE OVERVIEW**

- GitHub → CodePipeline → CodeBuild → CodeArtifact → CodeDeploy → EC2 (Apache Tomcat)
- Infrastructure is provisioned using CloudFormation templates.

🛠 **TECHNOLOGIES USED**

- AWS EC2

- AWS CodePipeline

- AWS CodeBuild

- AWS CodeDeploy

- AWS CodeArtifact

- AWS CodeConnection

- AWS CloudFormation

- AWS IAM

- Java & Maven

- Apache Tomcat

- Apache Http

- GitHub

📌 **IMPLEMENTATION STEPS**
https://docs.google.com/document/d/1Z0pCfgYJX48suYgwiMHfhrMsDWzuILwcafePoTpZT9E/edit?usp=sharing

🔐 **KEY DEVOPS CONCEPTS DEMONSTRATED**

- Continuous Integration (CI)

- Continuous Deployment (CD)

- Infrastructure as Code (IaC)

- Artifact Repository Management

- Immutable Build Artifacts

- Zero-Touch Deployment

- AWS IAM-based secure access

- Environment Standardization

📈 **OUTCOME**

- Eliminated manual build & deployment steps

- Reduced deployment time significantly

- Standardized infrastructure provisioning

- Enabled scalable and repeatable release cycles

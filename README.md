# AWS CI/CD Pipeline Project 🚀

## Project Overview

This project demonstrates a complete AWS CI/CD pipeline implementation using modern DevOps tools and AWS services. The pipeline automates building, testing, and deploying a Java web application.

This project was implemented by following concepts learned from the Udemy course:

- 🎓 Decoding DevOps – AWS CI/CD Pipeline Project

## Tech Stack 🛠️

- AWS EC2
- AWS Elastic Beanstalk
- AWS CodePipeline
- AWS CodeBuild
- AWS RDS (MySQL)
- Bitbucket Repository
- Maven
- Java
- Tomcat
- Jenkins
- Git & Git Bash

## Architecture Flow 📌

Developer Push Code → Bitbucket Repository → AWS CodePipeline → AWS CodeBuild → Artifact Generation → Elastic Beanstalk Deployment → Application Hosted on AWS

## AWS Services Used ☁️

| Service           | Purpose                   |
| ----------------- | ------------------------- |
| EC2               | Virtual server hosting    |
| Elastic Beanstalk | Application deployment    |
| CodePipeline      | CI/CD automation          |
| CodeBuild         | Build automation          |
| RDS MySQL         | Database service          |
| Bitbucket         | Source code management    |
| IAM               | Security & access control |

## Features ✨

- Automated CI/CD deployment
- Continuous Integration
- Continuous Delivery
- AWS Cloud Deployment
- Database integration with RDS
- Elastic Beanstalk hosting
- Source code version control
- Pipeline automation

## Deploy to AWS

Upload the generated WAR file to Elastic Beanstalk or configure deployment through AWS CodePipeline.

## Pipeline Stages 🔄

- Source Stage
  - Bitbucket repository integration
- Build Stage
  - Maven build
  - Artifact packaging
- Deploy Stage
  - Elastic Beanstalk deployment

## Learning Outcomes 📚

Through this project, I learned:

- AWS CI/CD concepts
- Deployment automation
- Infrastructure management
- Cloud application hosting
- Continuous integration workflow
- Build and deployment pipelines
- DevOps best practices

## Future Enhancements 🚀

- Docker integration
- Kubernetes deployment
- Terraform infrastructure
- Monitoring using CloudWatch
- Automated testing
- Blue-green deployment

## Author 👨‍💻

Poornesh Gowda

DevOps | Cloud | Full Stack Developer

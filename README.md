# Multi-Environment CI/CD Pipeline using GitHub Actions

This project demonstrates a complete CI/CD pipeline for a Java web application using GitHub Actions. The pipeline automatically builds a WAR file using Maven and deploys the same artifact across multiple environments: DEV, TEST, PREPROD, and PROD.

## Features
- Automated build and packaging using Maven
- Artifact upload and reuse across environments
- Separate deployments for DEV, TEST, PREPROD, and PROD
- Environment-specific secrets for secure credentials
- Manual approval gate before PROD deployment using GitHub Environments
- Deployment to Apache Tomcat using Tomcat Manager API

## Tools & Technologies
- GitHub Actions
- Apache Tomcat
- Maven
- Java
- Linux
- GitHub Secrets & Environments

## Deployment Flow
Build → DEV → TEST → PREPROD → PROD (with manual approval)

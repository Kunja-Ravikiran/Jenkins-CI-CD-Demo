# Jenkins CI/CD Demo

This repository demonstrates a Jenkins-based CI pipeline using a Jenkinsfile and Docker.

The project is designed to showcase:
- Jenkins Pipeline as Code
- CI pipeline execution using GitHub as SCM
- Docker-based build workflow
- Automated builds triggered via GitHub Webhooks
- Common CI/CD failure scenarios and their resolution

## Project Overview

- Jenkins is used to orchestrate the CI pipeline
- The pipeline definition is maintained using a Jenkinsfile
- Docker is used to build application artifacts
- GitHub Webhooks trigger the pipeline automatically on code push

## Tools & Technologies

- Jenkins
- GitHub
- Docker
- Linux (Ubuntu)
- Jenkins Pipeline (Declarative)

## CI Workflow

1. Code is pushed to the GitHub repository
2. GitHub sends a webhook event to Jenkins
3. Jenkins automatically triggers the pipeline
4. The pipeline builds a Docker image and runs defined stages

## Notes

This repository is intended for learning and demonstration purposes and accompanies a detailed Jenkins CI/CD walkthrough.

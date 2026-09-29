# ci-cd-final-project

## Project Name

ci-cd-final-project

## Description

This project demonstrates a complete CI/CD pipeline using GitHub Actions and OpenShift Pipelines.

The project automates the process of testing, linting, building, and deploying an application.

## Technologies Used

- GitHub
- GitHub Actions
- ESLint
- Jest
- Tekton
- OpenShift
- Buildah
- Node.js

## CI/CD Pipeline

The pipeline consists of the following stages:

1. Cleanup
2. Git Clone
3. Lint with ESLint
4. Run unit tests with Jest
5. Build container image using Buildah
6. Deploy application using OpenShift

## Project Workflow

Code is pushed to GitHub, which triggers the GitHub Actions workflow. The application is linted and tested before the OpenShift/Tekton pipeline builds and deploys the application.

## Project Name

ci-cd-final-project

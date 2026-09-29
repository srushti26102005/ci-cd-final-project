# ci-cd-final-project

## Project Name

ci-cd-final-project

## Description

This project demonstrates a complete CI/CD workflow using GitHub Actions and OpenShift Pipelines.

The project includes:
- GitHub Actions for continuous integration
- ESLint for code quality checking
- Jest for unit testing
- Tekton/OpenShift Pipelines for CI/CD automation
- Buildah for container image building
- OpenShift for application deployment

## CI/CD Pipeline

The pipeline performs the following steps:

1. Cleanup
2. Git Clone
3. Lint with ESLint
4. Run unit tests with Jest
5. Build container image using Buildah
6. Deploy application using OpenShift

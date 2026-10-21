# CI/CD Final Project

## Project Name
**CI/CD Pipeline Automation using GitHub Actions and OpenShift Pipelines**

## Project Description
This project demonstrates Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions and OpenShift Pipelines (Tekton). The pipeline automates code validation, linting, unit testing, container image building, and application deployment.

## Technologies Used
- GitHub and Git
- GitHub Actions
- Python
- flake8 for code linting
- nose for unit testing
- OpenShift Pipelines (Tekton)
- Buildah for container image building
- OpenShift CLI (`oc`) for deployment

## Project Objectives
1. Automate code quality checks using linting.
2. Execute unit tests to validate application functionality.
3. Define reusable tasks using Tekton.
4. Build a container image using Buildah.
5. Deploy the application to OpenShift.
6. Verify deployment through application logs.

## Repository Structure

```text
ci-cd-final-project/
├── README.md
├── .github/
│   └── workflows/
│       └── workflow.yml
├── .tekton/
│   └── tasks.yml
├── tests/
└── application files
```

## CI/CD Workflow
The intended workflow consists of:
1. Clean up the workspace.
2. Clone the source repository.
3. Run code linting with flake8.
4. Execute unit tests with nose.
5. Build the container image with Buildah.
6. Deploy the application to OpenShift.
7. Verify application status and logs.

## Expected Outcome
The project aims to provide an automated CI/CD workflow with code validation, testing, container image creation, deployment, and application verification.

**Note:** The workflow and deployment steps must be configured and executed successfully in the target environments before they can be considered complete.

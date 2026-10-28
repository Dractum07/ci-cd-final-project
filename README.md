# ci-cd-final-project

**Project name:** ci-cd-final-project - CI/CD Tools and Practices Final Project

## Project Description

This project demonstrates Continuous Integration (CI) and Continuous Delivery (CD) for a Python microservice using GitHub Actions, Flake8, Nose, Tekton, and OpenShift.

The objective is to automate code linting and unit testing, then define a pipeline for building and deploying the application.

## Technologies Used

- **Python** — application and unit tests
- **GitHub Actions** — continuous integration workflow
- **Flake8** — Python code linting
- **Nose** — unit testing
- **Tekton** — CI/CD pipeline tasks
- **OpenShift** — application deployment environment
- **Buildah** — container image building

## Project Tasks

1. Create a GitHub Actions workflow for continuous integration.
2. Run code linting with Flake8.
3. Run unit tests with Nose.
4. Define Tekton tasks for workspace cleanup and unit testing.
5. Build a container image using Buildah.
6. Deploy the application to OpenShift.

## Setup

Run the setup script in the provided lab environment:

```bash
bash bin/setup.sh
```

After the setup completes, exit the shell and start a new one so that the Python virtual environment can be activated:

```bash
exit
```

## Repository Structure

- `.github/workflows/` — GitHub Actions workflow
- `.tekton/` — Tekton task definitions
- `service/` — application source code
- `tests/` — unit tests
- `requirements.txt` — Python dependencies
- `Dockerfile` — container image instructions

## License

Licensed under the Apache License 2.0. See [LICENSE](LICENSE).

---

Based on the IBM Skills Network CI/CD Tools and Practices Final Project Template.

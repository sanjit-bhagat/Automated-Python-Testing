# Day 5 - Python Test Pipeline

## Objective
Learn how to create a GitHub Actions workflow for a basic Python testing pipeline.

## Scenario
Automatically run a workflow whenever code is pushed to the `main` branch.

## Tasks Performed
- Checked out the GitHub repository.
- Printed a Python testing message.
- Checked the Python version.
- Printed a test success message.

## Tools Used
- Git
- GitHub
- GitHub Actions
- YAML
- Python

## Workflow File
`.github/workflows/day1.yml`

## What I Learned
- How to configure a push trigger.
- How to define jobs and steps.
- How to use a GitHub-hosted Ubuntu runner.
- How to use `actions/checkout@v4`.
- How to execute shell commands using `run:`.

## Result
The workflow runs automatically when code is pushed to the `main` branch.

**Note:** The current test command prints a success message; it does not run actual Python unit tests.


# Day 6 - GitHub Actions Practice

## Objective
Learn GitHub Actions and CI/CD fundamentals.

## Project
Automated application health-check validation.

## Topics
- Git workflow
- YAML
- GitHub Actions
- Continuous Integration
- Workflow logs and troubleshooting


YAML file understand
YAML File - Understand the workflow
YAML-keyword	       Purpose
name	               Name displayed in GitHub Actions.
on	                   Events that trigger the workflow.
push	               Run when changes are pushed to main.
pull_request	       Run for pull requests targeting main.
workflow_dispatch	   Allows you to start a run manually from GitHub.
jobs	               Defines the work GitHub should perform.
runs-on	               Selects the runner machine.
steps	               Lists tasks executed in order.
uses	               Runs a reusable action, here to check out the source code.
run	                   Executes shell commands.
permissions	           Limits the workflow token to reading repository contents.

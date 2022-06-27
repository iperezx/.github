# Workflow Templates

This directory contains common Github action workflows which can be used by other repos.

To get started, see [Github's docs](https://docs.github.com/en/actions/using-workflows/creating-starter-workflows-for-your-organization) on writing a starter workflow.

For the case that a user forks from any of the waggle-sensors repositories, the following files require the user to create extra secrets for the forked repository:
- `build-and-push-docker-image.yml`: secrets.DOCKER_ORG

Reference how to create secrets for actions: [Github's secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets)
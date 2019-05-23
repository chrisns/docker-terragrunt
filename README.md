# Docker Terragrunt
[Terragrunt](https://github.com/gruntwork-io/terragrunt/) running with Terraform version 0.11.14

## Structure

- *app/Dockerfile* describe the applications and dependencies installed
- *LICENSE* describe usage terms and conditions
- *.drone.yml* builds an image using DroneCI and upload data to Quay public repo
- *README.md* the file you are reading now

## Usage

Drone will build a new image and push it to Quay at each push to a branch.


Infrastructure as Code with Terraform

## Objective
Provision a Docker container using Terraform to deploy an Nginx server.

## Tools Used
- Terraform
- Docker Desktop (Windows)

## Steps Performed
1. Installed and configured Terraform and Docker
2. Wrote main.tf to pull the nginx:latest image and create a container
3. Ran:
   - terraform init
   - terraform apply
4. Verified the container on [http://localhost:8080](http://localhost:8080)
5. Cleaned up using terraform destroy

## Files Included
- main.tf
- Screenshots of init, apply, and nginx page

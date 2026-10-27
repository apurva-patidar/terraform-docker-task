# Terraform Docker Infrastructure

## Objective
Provision an Nginx Docker container using Terraform.

## Tools Used
- Terraform
- Docker
- Nginx

## Project Details
Terraform uses the Docker provider to download the Nginx image and create a container named `terraform-nginx`.

- Container Name: `terraform-nginx`
- Internal Port: `80`
- External Port: `8081`

## Commands Executed
- `terraform init`
- `terraform fmt`
- `terraform validate`
- `terraform plan`
- `terraform apply`
- `terraform state list`
- `docker ps`

## Verification
Open http://localhost:8081 in a browser to verify the Nginx welcome page.

## Cleanup
Run `terraform destroy` when the container is no longer needed.

## Learning Outcome
Learned the basics of Infrastructure as Code (IaC), Terraform providers, resource management, execution plans, and Terraform state.<<<<<<< HEAD

# Terraform Docker Infrastructure

## Objective
Provision an Nginx Docker container using Terraform.

## Tools Used
- Terraform
- Docker
- Nginx

## Project Details
Terraform uses the Docker provider to download the Nginx image and create a container named `terraform-nginx`.

- Container Name: `terraform-nginx`
- Internal Port: `80`
- External Port: `8081`

## Commands Executed
```bash
terraform init
terraform fmt
terraform validate
terraform plan
terraform apply
terraform state list
docker ps
```

## Verification
Open http://localhost:8081 in a browser to verify the Nginx welcome page.

## Cl

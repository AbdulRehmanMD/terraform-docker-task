# Terraform Docker Provisioning

## Task 3: Infrastructure as Code (IaC) with Terraform

### Objective
Provision a local Docker container using Terraform.

### Tools Used
- Terraform
- Docker Desktop
- Docker Provider

### What I Did

1. Installed and verified Terraform.
2. Created a Terraform configuration using the Docker provider.
3. Ran `terraform init`.
4. Ran `terraform plan`.
5. Ran `terraform apply` to create the Docker image and container.
6. Verified the container using `docker ps`.
7. Checked Terraform state using `terraform state list`.
8. Verified the Nginx web server at `http://localhost:8081`.
9. Ran `terraform destroy` to remove the infrastructure.

### Terraform Resources

- Docker image: `nginx:latest`
- Docker container: `terraform-nginx`
- Port mapping: `8081:80`

### Commands Used

```text
terraform init
terraform plan
terraform apply
terraform state list
terraform destroy

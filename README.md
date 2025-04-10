# Terraform Docker NGINX Setup

This project uses **Terraform** to provision an **NGINX Docker container** locally.

## 📦 What's Inside?

- Terraform configuration to:
  - Pull the latest NGINX image
  - Run an NGINX container
  - Expose port `8080` on the host machine

## 🔧 Prerequisites

- [Terraform](https://developer.hashicorp.com/terraform/downloads)
- [Docker](https://docs.docker.com/get-docker/)
- Docker daemon should be running

## 🚀 How to Use

### 1. Clone the Repo
```bash
git clone https://github.com/faisaliqbal-dev/iac-nginx-container.git
cd terraform-docker-nginx

2. Initialize Terraform
terraform init

3. Apply the Configuration
terraform apply

Type yes when prompted.

4. Access NGINX
http://localhost:8080

🧹 Clean Up
terraform destroy

📁 Files Overview
 File          	Purpose
main.tf  	    Main Terraform config
README.md    	Project info and usage guide
.gitignore	  Ignore Terraform local files

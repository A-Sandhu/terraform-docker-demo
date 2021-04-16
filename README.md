# Quick Exercise to provision an NGINX server in less than a miniute using Docker/terraform on Mac. 
 Here are the steps to follow:
 - open -a Docker (To verify that Docker has installed on your local machine)
 - terraform -version ( To check the TF version installed)
 - mkdir terraform-docker-demo ( To create a directory named terraform-docker-demo)
 - touch main.tf file ( To create main.tf file)
 - terraform init ( To Initialize the project and download the required plugins to allow TF to interact with docker)
 - terraform validate ( To check whether the configuration is valid)
 - terraform plan (To show changes required by the current configuration)
 - terraform apply ( To create defined infrastructure in main.tf file)
 - docker ps (To view the docker container in running state)
 - Curl local.host:8000 or browser local.host:8000
 - terraform destroy (To destroy an NGINX webserver provision with Terraform)

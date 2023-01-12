
This folder contains example Terraform configuration that define a module for deploying a cluster using EC2,VPC, Security Groups, Auto Scaling and a load balancer (using ELB) in an Amazon Web Services (AWS) account in US region us-east-1. 

**Pre-requiste**

  - AWS Account creds
  - Terrform for IAC

**Commands to be used**

  - rm -Rf .terraform
  - terraform init 
  - terraform plan 
  - terraform apply 
  - terraform destroy
  
 **For Dev/test Stage Commands to be used**
 
 Dev stage
  
  - terraform plan -var-file="dev.tfvars"
  - terraform apply -var-file="dev.tfvars"
 Test stage
 
  - terraform plan -var-file="test.tfvars"
  - terraform apply -var-file="test.tfvars"
 


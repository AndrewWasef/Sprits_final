# DevOps-Bootcamp-Capstone-Project Created By Andrew Wasef #

<!-- Project OverView
The Purpose of the project is to deploy python-app 
with database on a AWS cluster using Terraform  
to create the environment and ansible for configuration -->

< To run Terraform script must install Terraform and anisble first on your machine >

# 1) Building the Environment using Terraform and install jenkins by ansibly on EC2 running by terraform
# Apply the code using :
```
terraform plan 
terraform init
terraform apply
```
# 2) Using Jenkins to build&push images
# Add the following script in the jenkins file to jenkins manually to build the docker file then push it to ecr and  apply the kubernetes files

# 3) Using the load balancer dns to access the web-app
<img src=https://user-images.githubusercontent.com/116598689/226450798-8e6c0d5c-5f6c-489d-8053-458c62c77578.jpg>

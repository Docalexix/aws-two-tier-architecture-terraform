# Project Title: aws 2 tier architure Terraform
A two-tier architecture in AWS, deployed using Terraform, typically consists of a presentation/web tier and a data/database tier. Terraform, as an Infrastructure as Code (IaC) tool, automates the provisioning and management of the AWS resources required for this architecture.

<img width="568" height="757" alt="Image" src="https://github.com/user-attachments/assets/fd962af5-01d3-4daa-a253-8871941b130b" />



### Projecr overview
Github: Create the project in github and clone to your root directory in your local terminal 
Create terraform files - create terraform files neccessary for the provisioning of our resources
#.gitignore
#backend.tf files to configure and store terraform statefiles.
#main.tf
#provider.tf
#securitygroup.tf
#vpc.tf
#terraform.tvars
#varriables.tf
#jerkins.sh
#nginx.sh


### Project output
#### output of the nginx webserver on the first server after copying the IP address fron aws Ec2 instances and launching on a new browser tab
<img width="1234" height="379" alt="Image" src="https://github.com/user-attachments/assets/6812d844-5c7d-45f9-9b1a-ff8431b9dbb6" />

#### output of the jerkins webserver on the second server after copying the IP address fron aws Ec2 instances and launching the IP address on a new browser tab adding :8080
<img width="1369" height="689" alt="Image" src="https://github.com/user-attachments/assets/6eaa775f-b459-4d92-8ffb-0e93d0b0cc0e" />


============
#### STAGE 2: CLEAN UP
==============

#### step1 : Destroy the resources created

#### run terraform destroy --auto-approve

##### Now check the ec2 instances in aws they are all terminated

##### also check the vpc, route table, internet gateway in aws they are all terminated



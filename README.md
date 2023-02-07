# Launch ec2 instance and build it using Terraform.

Pre-requisites:

Basic understanding of Terraform.

Terraform installed on our system.

AWS Account.

access_key & secret_key of an AWS IAM User

(1)Create the main.tf file. Open your text/code editor and create a new directory. ...

(2)Create the variables.tf file. Once the main.tf file is created, it's time to set up the necessary variables. ...

(3)Create the EC2 environment. ...
   terraform init - Initializes the environment and pulls down the AWS provider.
   terraform plan - Creates an execution plan for the environment and confirm no bugs are found.
   terraform apply - Creates and automatically approves the environment.

(4)Clean up the environment.

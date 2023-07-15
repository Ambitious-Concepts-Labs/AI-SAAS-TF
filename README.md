# AI-SAAS Terraform
This repository contains a Terraform project that utilizes artificial intelligence (AI) to create an Amazon Web Services (AWS) Simple Notification Service (SNS) topic. The project aims to automate the provisioning and configuration of the SNS topic using infrastructure as code principles.

## Prerequisites
Before running this Terraform project, ensure that you have the following prerequisites installed:

- Terraform: The latest version of Terraform must be installed on your machine.
- AWS Account: You should have an active AWS account with appropriate permissions to create SNS topics.
- AWS CLI: The AWS CLI should be installed and configured on your local machine.
- IAM Credentials: Ensure that you have valid AWS IAM credentials to interact with your AWS account.

## Getting Started
To get started with this AI Terraform AWS SNS topic creation project, follow these steps:

1. Clone the repository: git clone https://github.com/Ambitious-Concepts-Labs/AI-SAAS-TF.git

1. Navigate to the project directory: ```bash cd AI-SAAS-TFE```

1. Initialize the Terraform project:  ```bash terraform init```
   
1. Modify the variables.tf file to provide values for the required variables.
   
1. Review the main.tf file to understand the AWS resources being created and their configurations.

    *Optionally, modify any other files as needed, such as sns.tf for advanced topic configurations.*

1. Run  ```bash terraform plan``` to preview the changes that will be made in your AWS account.
   
1. If the plan looks good, apply the changes:  ```bash terraform apply```


Terraform will create the AWS SNS topic based on the provided configuration.

## Configuration
The Terraform project includes the following files and directories:

main.tf: This file contains the main configuration for creating the AWS SNS topic.

variables.tf: Here, you can define the variables required for the project.

sns.tf: Optional file for advanced configuration of the SNS topic.

.terraform/: The directory where Terraform stores its internal files.

## Maintainers
This project is maintained and supported by Dominique Hosea. If you encounter any issues or have questions, please feel free to open an issue.

## License
The AI Terraform AWS SNS Topic Creation project is licensed under the MIT License.

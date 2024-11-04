# Two-Tier AWS Architecture using Terraform

## Project Description 
This project aims to create a robust highily available web application infrastructure using a two-tier architecture on Amazon Web Services (AWS). The architecture comprises a web tier that handles user requests and a database tier for data storage. I leveraged Terraform for Infrastructure as Code (IaC) to provision and manage AWS resources efficiently.

## Architectural Diagram 

![architectural-diagram](https://github.com/kotgire58/2-tier-infra/blob/main/image.png)


## Key Features

- **Infrastructure as Code (IaC):** Leveraging Terraform for defining and provisioning the entire infrastructure, ensuring consistency and repeatability.
- **High Availability:** Utilized multiple Availability Zones (AZs), the application is designed for high availability, minimizing downtime in case of failures.
- **Security:** Implementing security best practices, such as network ACLs, security groups, and encryption, to protect data and resources.
- **Database Management:** A managed database service  Amazon RDS is used to store and manage application data, providing reliability and data durability.
- **Load Balancing:** Employing Elastic Load Balancers (ELBs) to distribute incoming traffic across multiple web servers, optimizing resource utilization.



## Terraform Configuration

The Terraform configuration files with(`*.tf`) in this repository define the AWS resources and settings required to create the two-tier architecture AWS infrastructure.

## Steps:

| Step | Description                                   |
|------|-----------------------------------------------|
| 1    | Setting Up the Environment                    |
| 2    | Installing the Necessary Plugins              |
| 3    | Creating a Separate VPC Infrastructure        |
| 4    | Creating Security Group                       |
| 5    | Creating the Load Balancer                    |
| 6    | Creating Database in Private Subnet           |
| 7    | Providing Values for Variables                |
| 8    | Getting DNS as Output                         |
| 9    | Final Output                                  |




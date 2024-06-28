# AWS VPC Terraform Project

This project demonstrates how to create an AWS VPC and its components using Terraform. It sets up a VPC with an Internet Gateway, route table, and subnets across all available Availability Zones in the us-east-1 region.

## Prerequisites

- AWS Account
- Terraform installed
- Visual Studio Code (or any preferred code editor)


## Project Structure

- `main.tf`: Contains the main Terraform configuration for creating the VPC and its components.
- `variables.tf`: Defines the input variables used in the configuration.
- `terraform.tfvars`: Contains the values for the defined variables (not tracked in version control).

## Resources Created

- VPC with CIDR block 10.0.0.0/16
- Internet Gateway attached to the VPC
- Route table with a route to the Internet Gateway
- Subnets in all available Availability Zones

  ## Notes

- This project is designed for learning purposes and may need additional security considerations for production use.
- Always review and understand the resources being created before applying the configuration in your AWS account.

## License

[MIT License](LICENSE)

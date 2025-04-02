# Terraform Linting & Validation

## Objective
Ensure all Terraform code passes basic security linting.

## Guidelines
- Use `terraform validate` and `tflint`.
- Require `required_providers` block in each module.
- Avoid hardcoded secrets.

## Example
```hcl
terraform {
  required_providers {
    aws = {
      source  = "hashicorp/aws"
      version = "~> 4.0"
    }
  }
}
```
# VPC Secure Networking

## Objective
Use secure defaults and architecture for VPC.

## Recommendations
- Use **private subnets** for EC2.
- Restrict **NAT gateways**.
- Log **VPC Flow Logs**.

## Example
```hcl
resource "aws_vpc" "main" {
  cidr_block           = "10.0.0.0/16"
  enable_dns_hostnames = true
  enable_dns_support   = true
}

resource "aws_flow_log" "vpc_flow" {
  log_destination      = "arn:aws:logs:us-east-1:123456789012:log-group:vpc-flow"
  traffic_type         = "ALL"
  vpc_id               = aws_vpc.main.id
}
```
# EC2 Security Best Practices

## Objective
Deploy EC2 instances using hardened settings.

## Recommendations
- Use **latest AMIs** with automatic patching.
- Enable **detailed monitoring**.
- Restrict **inbound rules** using security groups.
- Avoid using **default VPC**.

## Example
```hcl
resource "aws_instance" "secure_ec2" {
  ami                    = "ami-0abcdef1234567890"
  instance_type          = "t3.micro"
  monitoring             = true
  associate_public_ip_address = false

  vpc_security_group_ids = [aws_security_group.secure_sg.id]
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```

# Network ACL Configuration

## Objective
Control inbound and outbound traffic at the subnet level.

## Recommendations
- Use NACLs for stateless traffic filtering.
- Deny all unused ports by default.
- Monitor changes using CloudTrail.

## Example
```hcl
resource "aws_network_acl" "example" {
  vpc_id = aws_vpc.main.id
}

resource "aws_network_acl_rule" "inbound" {
  network_acl_id = aws_network_acl.example.id
  rule_number    = 100
  egress         = false
  protocol       = "tcp"
  rule_action    = "allow"
  cidr_block     = "0.0.0.0/0"
  from_port      = 22
  to_port        = 22
}
```
# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```

# IAM Least Privilege

## Objective
Ensure IAM policies grant only the permissions required.

## Recommendations
- Avoid wildcard `*` permissions.
- Use IAM roles for applications and services.
- Regularly audit IAM users and permissions.

## Example
```hcl
resource "aws_iam_policy" "read_only" {
  name        = "ReadOnlyPolicy"
  description = "IAM policy for read-only access"

  policy = jsonencode({
    Version = "2012-10-17"
    Statement = [
      {
        Action = [
          "s3:Get*",
          "ec2:Describe*"
        ]
        Effect   = "Allow"
        Resource = "*"
      }
    ]
  })
}
```
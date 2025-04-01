# IAM Policy Best Practices

## Objective
Create least-privilege IAM policies.

## Recommendations
- Avoid `*` in actions or resources.
- Use conditions to restrict access.
- Use managed policies only when audited.

## Example
```hcl
resource "aws_iam_policy" "readonly_policy" {
  name        = "readonly-policy"
  description = "Read-only access to S3"

  policy = jsonencode({
    Version = "2012-10-17",
    Statement = [
      {
        Action = [
          "s3:Get*",
          "s3:List*"
        ],
        Effect   = "Allow",
        Resource = "*"
      }
    ]
  })
}
```

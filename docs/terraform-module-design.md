# Designing Secure Terraform Modules

## Guidelines
- Use input validation via `validation` blocks
- Avoid hardcoding ARNs or credentials
- Output only necessary values

## Example
```hcl
variable "bucket_name" {
  type        = string
  description = "The name of the S3 bucket"

  validation {
    condition     = length(var.bucket_name) > 3
    error_message = "Bucket name must be at least 4 characters."
  }
}
```
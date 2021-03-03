# AWS API Status Terraform module

Terraform module which creates a Lambda with a ready-to-use NodeJS source code to handle
status on AWS.

## Usage

```hcl
module "lambda-api-status" {
  source = "genstackio/layer-api-redirect/aws//modules/lambda"

  name   = "my-lambda-api-status"
}
```

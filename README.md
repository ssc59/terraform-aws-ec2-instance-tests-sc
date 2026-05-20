# terraform-aws-ec2-instance-tests-sc

A Terraform module for creating EC2 instances with integration tests.

## Usage

```hcl
module "ec2_instances" {
  source = "app.terraform.io/sudo-cloud-org/ec2-instance-tests-sc/aws"

  instance_count = 2
  instance_type  = "t2.micro"
}

Testing integration workflow.
Retry after adding AWS credentials.

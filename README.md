# Terraform AWS Instance

## Steps:

1. Install AWS CLI `brew install awscli`
   https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html#getting-started-install-instructions

2. Configure AWS
   `aws configure`
   <br>

   > AWS Access Key ID [None]: **\*\***\***\*\***
   > AWS Secret Access Key [None]: **\*\***\*\*\***\*\***
   > Default region name [None]: us-east-1
   > Default output format [None]: none

3. Create repo and add `main.tf` file

```
terraform init
terraform fmt
terraform validate
terraform apply
terraform show
terraform state list
```

4. Update `ami` value
   `terraform plan` - see all changes you made
   `terraform apply` - apply all changes
   `terraform destroy` - get rid of all our infrastructure

Go to AWS check EC2 instances

5. Create variables and outputs files
   `terraform output` - list of all outputs

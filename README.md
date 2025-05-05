# Publish Terraform module to Terraform Regitry

## Need to follow the following Nomeclature to get identified by the terraform registry in git repos

terraform-<PROVIDER>-<NAME>

terraform-aws-s3-bucket
terraform-google-gke
terraform-azurerm-vm

### example
terraform-aws-s3-bucket

## Folder struture inside the git repo
```text
terraform-aws-s3-bucket/
├── main.tf
├── variables.tf
├── outputs.tf
└── README.md

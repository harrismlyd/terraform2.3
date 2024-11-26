# terraform2.3
Terraform 2.3

# apply using cli arguments
terraform apply -var="name=harris" -var="vpc_id=vpc-067f3ab097282bc4d" -var="subnet_id=subnet-0021081c508245985"

# apply using tfvars file
terraform apply -var-file=dev.tfvars

# show outputs
terraform apply at least once
terraform output
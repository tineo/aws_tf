terraform init

terraform validate

terraform import aws_key_pair.makinap makinap.pem

terraform plan -var 'owner=tineo'

terraform apply -var 'owner=tineo'
**To get terraform upgrade latest version**
wget https://releases.hashicorp.com/terraform/1.14.3/terraform_1.14.3_linux_amd64.zip
unzip terraform_1.14.3_linux_amd64.zip
sudo mv terraform /usr/local/bin/
terraform version

**Here are the essential Terraform commands to manage your infrastructure:**

terraform init – Initialize your Terraform workspace.
terraform plan – Preview the changes Terraform will make.
terraform apply – Create or update resources based on your config.
terraform destroy – Tear down all resources Terraform manages.
terraform validate – Check your configuration for syntax errors.
terraform fmt – Format your code consistently.
terraform state list – List resources in the current state.
 

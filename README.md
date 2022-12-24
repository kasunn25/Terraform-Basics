# Terraform Command Lines

| Command | Description |
| --- | --- |
| `terraform validate` | Validate code for syntax |
| `terraform validate -backend=false` | Validate code skip backend validation |
|	|	|
| `terraform init` | Initialize directory, pull down providers |
| `terraform init -get-plugins=false` | initialize directory, do not download plugins |
| `terraform init -verify-plugins=false` | Initialize directory, do not verify plugins for Hashicorp signature |
|	|	|
| `terraform apply --auto-approve` | Apply changes without being prompted to enter “yes” |
| `terraform destroy --auto-approve` | Destroy/cleanup deployment without being prompted for “yes” |
| `terraform plan -out plan.out` | Output the deployment plan to plan.out |
| `terraform apply plan.out` | Use the plan.out plan file to deploy infrastructure |
| `terraform plan -destroy` | Outputs a destroy plan |
| `terraform refresh` | Reconcile the state in Terraform state file with real-world resources | 
| `terraform providers` | Get information about providers used in current configuration |
|	|	|           
| `terraform workspace new mynewworkspace` | Create a new workspace |
| `terraform workspace select default` | Change to the selected workspace |
| `terraform workspace list` | List out all workspaces |      
|	|	|           
| `terraform version` | Display Terraform binary version, also warns if version is old |
| `terraform get -update=true` | Download and update modules in the “root” module |   

![Introduction to Terraform on Azure][lil-thumbnail-url] 

[lil-thumbnail-url]: https://res.cloudinary.com/acloud-guru/image/fetch/c_thumb,f_auto,q_auto,w_1053/https://acg-wordpress-content-production.s3.us-west-2.amazonaws.com/app/uploads/2020/11/terraform-cheatsheet-scaled.jpg

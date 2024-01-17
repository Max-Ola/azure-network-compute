# azure-network-compute

We will use VPC with CIDR `10.0.0.0/16` with 1 subnet with CIDR `10.0.2.0/24`. We are putting our VM instance in the network security group that allows SSH inbound connections and all outbound connections.

Install the Azure CLI on MacOS
- `brew update && brew install azure-cli`

Sign in interactively with Azure CLI

- Run the `az login` command.
- `az login --user --password ` Sign in with credentials on the command line
  

Create Infrastructure 🛠
Run these commands after you've  cloned the code in your local machine to create the environment on the cloud.

- `terraform init`
- `terraform plan`
- `terraform apply`


If you do not want to incur extra charges just run `terraform destroy` after you're done.



![image-7](https://github.com/Max-Ola/azure-network-compute/assets/106966289/7052ea83-ebae-41eb-8140-2fc0534c7362)

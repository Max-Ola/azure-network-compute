# azure-network-compute

We will be using VPC with CIDR 10.0.0.0/16 with 1 subnet with CIDR 10.0.2.0/24. We are putting our VM instance in the network security group which allows SSH inbound connections and all outbound connections.

Sign in interactively with Azure CLI

- Run the 'az login' command.
- az login --user <username> --password <password> #Sign in with credentials on the command line
  

Create Infrastructure 🛠
Run these commands after you've  cloned the code in your local machine.

- terraform init
- terraform plan
- terraform apply



![image-7](https://github.com/Max-Ola/azure-network-compute/assets/106966289/7052ea83-ebae-41eb-8140-2fc0534c7362)

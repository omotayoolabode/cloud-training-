# Lab 1: Create a Linux virtual machine with the Azure CLI

1. Launch Azure Cloud Shell: To do this, i created a microsoft azure account, once the azure account is set up, Launching azure cloud shell is easy.
2. Create a resource group: This is done on the azure Cloud Shell. I did it using az group create tayo.
3. Open port 80 for web traffic: This is done by running az vm open --port 80 --resource group tayo 
5. Connect to virtual machine
6. Install web server: This is done using Sudo apt-get -y install nginx
7. View the web server in action

### Notes:

Quickstart: Create a Linux VM
* https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-cli

Quickstart for Bash in Azure Cloud Shell
* https://docs.microsoft.com/en-us/azure/cloud-shell/quickstart
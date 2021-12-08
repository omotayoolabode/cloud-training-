# Lab 4: Create and use an SSH public-private key pair for Linux VMs in Azure

1. Supported SSH key formats: Azure currently supports SSH protocol 2 (SSH-2) RSA public-private key pairs with a minimum length of 2048 bits. key formats such as ED25519 and ECDSA are not supported.
2. Create an SSH key pair: This was done using the ssh-keygen -m PEM -t rsa -b 4096 bash script
3. Provide an SSH public key when deploying a VM: to display my public key i ran the cat ~/.ssh/id_rsa.pub code and then procedded to paste the code in my azure portal
4. SSH into your VM

### Notes:

Quickstart: SSH for Linux VMs
* https://docs.microsoft.com/en-us/azure/virtual-machines/linux/mac-create-ssh-keys

Quickstart for Bash in Azure Cloud Shell
* https://docs.microsoft.com/en-us/azure/cloud-shell/quickstart
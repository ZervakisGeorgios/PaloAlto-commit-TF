# PaloAlto-commit-TF
Terraform does not have a native function to commit changes on a Palo Alto firewall. The script stored in this repository reads the terraform.tfvars file from the TF folder in where the FW IP, username, password are stored and SSHes into the firewall to commit the changes

Regexs patterns are used to identify the FW IP, username and password
Paramiko is used for SSH

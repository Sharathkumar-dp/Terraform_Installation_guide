# Terraform_Installation_guide

Terraform Installation methods

1. Manual installation

2. Linux Installation 

3. Windows Installation


**Linux Installation method**

Install necessory packages

add Hashicorp Key

Update and install Terraform CLI

verify the installation and Enable


Commands to install Terraform

sudo yum install yum-utils -y

sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo

sudo yum install terraform -y

terraform --help

-------------------------------------------------------------------------------------------------------------------------------------------

**Windows Installation method**

Download and install Chacolatey package manager and verify it

Run below commands in powershell with admin 

Get-ExecutionPolicy

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

chaco


Install terraform

chaco install terraform


verify installation

terraform -help

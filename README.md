End-to end automation to create a ubuntu 20.04 virtual machine in vSphere
-------------------------------------------------------------------------
The goal is to create a ubuntu 20.04 virtual machine and 3 main softwares (docker, docker-compose and homebrew). This can exemplify the advanced nature of configurations that can be rendered via IaC automation

Pre-requisites
--------------
* A local windows machine with 3 main utilities
**  ubuntu Windows SubSystem for Linux (WSL2)
**  Packer., to create base templates for ubuntu machines from ISO files hosted on ubuntu official sites
**  Terraform., to create the virtual machine and configure various packages from the base template created by packer

Access to vSphere environment with adequate permissions to create resources


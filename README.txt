The Project concentrates on the understanding of the way Terraform works with AWS. 

In this project I tried to automate a service architectureon Amazon Web Services (AWS)

Terraform was used to automate the creation and deconstruction of the service. 

The following assumptions were made in order to complete the project:
  1. Only local network access is required for all resources.
  2. The VPC and subnet already exists

The core network resources were duplicated in atleast 2 regions, network traffic routed to the appropriate region based on the user location, subnetworks appropriately sized, all devices existing in such a way that they can connect to the internet as well as with one another. Networks are designed to be highly available and auto-scaling is done so as to prevent downtime.

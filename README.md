# AWS Deployment
The goal behind this project was just to deploy out the required infrastructure. There are several areas where things could be coded different to allow for more flexibility, re-usability and resiliance. 

### Compute Module
* [will deploy an autoscaling group with Apache instances]

### File Storage Module
* [will cdeploy an EFS file system and a mount point]

### Networking Module
* deploys the required secuity group
* deploys a VPC and a singular subnet
* deploys hard coded subnets 
* this module can be cleaned up later to be more dynamic and flexible 

# Deploy Tyk on AWS
This repo provides a starting point to quickly deploy one of various types of Tyk archiectures on AWS. 
Each CloudFormation (.yaml) file deploys a single type of architecture.
Under the '/deployments' directory, select an architecture relevant for your usecase. 

## Available Architectures
1. development environment


<!---
This repo deploys the following components.

| AWS Resource  | Tyk Stack Component | Security Group |
|---------------|---------------------|----------------| 
| EC2 Instance  | Redis Database      | DatabaseSG     |
| EC2 Instance  | MongoDB Database    | DatabaseSG     |
| EC2 Instance  | Tyk Dashboard       | ApplicationSG  |
| EC2 Instance  | Tyk Pump            | DatabaseSG     |
| EC2 Instance  | Tyk Gateway         | ApplicationSG  |
--->

## Operating System
AmazonLinux 

## AWS Architecture Diagram
<img src="zimages/SingleTykGatewayDeployment.png" width="800" height="600">


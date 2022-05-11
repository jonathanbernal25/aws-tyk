# Deploy Tyk on AWS
This repo provides a starting point to quickly deploy various types of Tyk archiectures on AWS. 
Each CloudFormation (.yaml) file deploys a single type of architecture. 
Each individual deployment is under the /deployments folder.

This repo deploys the following components.

| AWS Resource  | Tyk Stack Component | Security Group |
|---------------|---------------------|----------------| 
| EC2 Instance  | Redis Database      | DatabaseSG     |
| EC2 Instance  | MongoDB Database    | DatabaseSG     |
| EC2 Instance  | Tyk Dashboard       | ApplicationSG  |
| EC2 Instance  | Tyk Pump            | DatabaseSG     |
| EC2 Instance  | Tyk Gateway         | ApplicationSG  |

## Operating System
AmazonLinux 

## AWS Architecture Diagram
<img src="zimages/SingleTykGatewayDeployment.png" width="800" height="600">


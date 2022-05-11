# Deploy Tyk on AWS
This repo provides a starting point to quickly deploy one of various types of Tyk archiectures on AWS. 
Each CloudFormation (.yaml) file deploys a single type of architecture.
Under the '/deployments' directory, select an architecture relevant for your usecase. 


## Operating System
AmazonLinux2

## Available Architectures
[development environment](https://github.com/jonathanbernal25/aws-tyk/blob/main/deployments/dev.yaml)


<!---
This repo deploys the following components.

| AWS Resource  | Tyk Stack Component | Security Group |
|---------------|---------------------|----------------| 
| EC2 Instance  | Redis Database      | DatabaseSG     |
| EC2 Instance  | MongoDB Database    | DatabaseSG     |
| EC2 Instance  | Tyk Dashboard       | ApplicationSG  |
| EC2 Instance  | Tyk Pump            | DatabaseSG     |
| EC2 Instance  | Tyk Gateway         | ApplicationSG  |


## AWS Architecture Diagram
<img src="images/SingleTykGatewayDeployment.png" width="800" height="600">

--->

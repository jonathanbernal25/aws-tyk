# Deploy Tyk on AWS
This repo provides a starting point to quickly deploy one of various types of Tyk archiectures on AWS. 
Each CloudFormation (.yaml) file deploys a single type of architecture.
Under the '/deployments' directory, select an architecture relevant for your usecase. 


## Operating System
AmazonLinux2

## Available Architectures
[development environment](https://github.com/jonathanbernal25/aws-tyk/blob/main/deployments/dev.yaml)

This architecture is for a development environment. 
There is a single EC2 instance with all components installed.

[single gateway environment](https://github.com/jonathanbernal25/aws-tyk/blob/main/deployments/singlegateway.yaml)

This architecture is closer to a production environment. 
There are a total of 5 EC2 instances deployed, each instance with a component installed.
There is no High Availability.

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

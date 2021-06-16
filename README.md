# Tyk on AWS
This repo provides a starting point for users to deploy Tyk on AWS. The single CloudFormation YAML file deploys the entire Tyk stack with a path towards production deployment in mind. 

This repo deploys the following components:

| AWS Resource  | Tyk Stack Component | Security Group |
|---------------|---------------------|----------------| 
| EC2 Instance  | Redis Database      | DatabaseSG     |
| EC2 Instance  | MongoDB Database    | DatabaseSG     |
| EC2 Instance  | Tyk Dashboard       | ApplicationSG  |
| EC2 Instance  | Tyk Pump            | DatabaseSG     |
| EC2 Instance  | Tyk Gateway         | ApplicationSG  |

# Operating System
At the moment, only AmazonLinux is available. Currently adding RHEL7 and RHEL8 architectures. 

# AWS Architecture Diagram
<img src="zimages/SingleTykGatewayDeployment.png" width="800" height="600">


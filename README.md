# Deploy Tyk on AWS
This repo provides a starting point to quickly deploy one of various types of Tyk archiectures on AWS. 
Each CloudFormation (.yaml) file deploys a single type of architecture.
Under the '/deployments' directory, select an architecture relevant for your use-case. 

NOTE: FOR AmazonLinux2 ONLY

# Available Architectures
## Development

The development architecture deploys all components onto a single EC2 instance. 
This is ideal testing and development. \ 
[CloudFormation Template](https://github.com/jonathanbernal25/aws-tyk/blob/main/deployments/dev.yaml)
<img src="images/development.png" width="600" height="600">

## Single Gateway
This architecture deloys all components onto their own EC2 instance. 
This is closer to the best practice of deploying Tyk to a production environment. 
NOTE: No high availability of any component. \
[CloudFormation Template](https://github.com/jonathanbernal25/aws-tyk/blob/main/deployments/singlegateway.yaml)
<img src="images/single-gateway.png" width="600" height="600">

## AWS Architecture Diagram
<img src="images/development.png" width="800" height="600">


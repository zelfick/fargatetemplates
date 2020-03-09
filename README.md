# Fargate Templates
Cloudformation Templates For diferent public fargate deployments


Launch an AWS Fargate cluster in a public VPC with an internet gateway 
(cluster-fargate-public-vpc.yml) 

Add an external, public ALB ingress
(alb-external.yml) 

Deploy a public Fargate service
(service-fargate-public-subnet-public-lb.yml)


note: Check the CloudFormation outputs for the ALB ingress template to get the public facing URL of your service. You can add your own custom hostname using Route53 to create a CNAME for this address.

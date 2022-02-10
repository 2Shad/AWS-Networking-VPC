# VPC (Virtual Private Cloud)

## What is a VPC?
It is a amazon's service that lets you create a logically Isolated network in a Region, to launch your amazon resources in.

## What are Subnets?
They are logical subdivision by availability zone of a larger VPC network, in here you can launch your instances, a use case scenario would be to have a public subnet for resources that would be connected to the internet, and having a private subnet for resources that wouldn't be connected to the internet. in each subnet the IP addresses would start with the same prefix.

## What is a route table? 
route table are a set of rules called route to determine where the traffic for the VPC is directed. It is possible to associate a subnet with particular route tables depending of the user's use case scenario.

## What is an internet gateway?
a CIDR block is an gateway that you attach to your VPC to enable communication between resources in your VPC and the internet.

## What is a CIDR block?
A CIDR block (Classless Inter-Domain Routing) is an internet protocol address allocation and route aggregation methodology.

## What is NACL?
Network ACLs: An optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of your subnets.

![VPC](VPC.png)
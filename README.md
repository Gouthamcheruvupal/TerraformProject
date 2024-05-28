# TerraformProject

This is the Terraform Code to Built the infrastructure in AWS (VPC, SUBNET'S, ROUTE TABLES, SECURITY GROUP'S,EC2 , Application Load Balancers)

Project Overview:
In this project, we used Terraform to automate the provisioning of infrastructure on AWS. The main components of the infrastructure include a Virtual Private Cloud (VPC), multiple subnets, route tables, security groups, EC2 instances, and an Application Load Balancer (ALB). This setup ensures high availability and load balancing for two applications deployed in different availability zones.

**Objectives:**
Create a VPC: Provision a Virtual Private Cloud to isolate the network environment.
Create Subnets: Establish subnets in different availability zones to enhance fault tolerance and high availability.
Configure Route Tables: Set up route tables to manage the routing of traffic within the VPC.
Set Up Security Groups: Define security groups to control inbound and outbound traffic to the EC2 instances.
Deploy EC2 Instances: Launch EC2 instances to host the applications.
Configure Application Load Balancer: Implement an Application Load Balancer to distribute incoming traffic across the EC2 instances automatically.

**Terraform Code Components:**
VPC: The code provisions a VPC to host all resources.
Subnets: Multiple subnets are created across different availability zones to ensure high availability.
Route Tables: Route tables are set up and associated with the subnets to manage network traffic.
Security Groups: Security groups are created to allow and restrict traffic to the instances.
EC2 Instances: EC2 instances are deployed in the subnets to run the applications.
Application Load Balancer: An ALB is configured to distribute traffic evenly across the EC2 instances, ensuring load balancing and high availability.

**Benefits:**
Automation: The entire infrastructure is provisioned and managed using Terraform, ensuring consistency and reducing manual errors.
Scalability: The infrastructure can be easily scaled by modifying the Terraform code and reapplying the configuration.
High Availability: Deploying applications in different availability zones and using an ALB ensures that the applications are highly available and resilient to failures.
Security: Security groups are used to tightly control access to the instances, enhancing the security of the applications

**Conclusion:**
This Terraform project showcases the ability to automate the creation of a robust, scalable, and secure infrastructure on AWS. By leveraging Terraform, we achieve efficient infrastructure management, high availability, and automated load balancing for our deployed applications.


# Virtualization
Aim:
To set up of a Private Cloud  in AWS.

Setting up of a private cloud in AWS:

Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),
involves creating a logically isolated virtual network that you can use to launch AWS
resources. This provides you with full control over your virtual networking environment,
including resource placement, connectivity, and security.
Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual
networking environment, including resource placement, connectivity, and security. Get
started by setting up your VPC in the AWS service console. Next, add resources to it such as
Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS)
instances. Finally, define how your VPCs communicate with each other across accounts,
Availability Zones, or AWS Regions.

Procedure:

1. Plan Your VPC:
● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.
● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.
● Plan internet connectivity:
Determine if you need public internet access and how to configure it.
● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.
2. Create Your VPC:
Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.
 Choose "Create VPC": Initiate the VPC creation process.
Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
other necessary settings.
Create subnets: Define subnets within your VPC to isolate different parts of your
network.
Create route tables: Specify how traffic is routed within and outside the VPC.
 Create security groups: Define access control rules for your resources.
3. Deploying Resources:
Launch EC2 instances: Create and launch virtual machines within your VPC.

Output:
Create VPC:

![Screenshot 2025-04-29 132748](https://github.com/user-attachments/assets/f274fb1d-0aa1-49fa-a526-38b30eb129a5)

Configuring subnets:

![Screenshot 2025-04-29 132801](https://github.com/user-attachments/assets/43e36631-819d-47a2-8ed4-aa6716f63926)

![Screenshot 2025-04-29 132815](https://github.com/user-attachments/assets/4f88b128-6b47-4cf5-abfd-e993bfd43ff0)

Setting Internet Gateway:

![Screenshot 2025-04-29 132827](https://github.com/user-attachments/assets/b7fcb247-acfc-4239-affe-b0e3841f16d5)

![Screenshot 2025-04-29 132837](https://github.com/user-attachments/assets/738daa57-0c41-4daa-b607-4f4784fc1380)

![Screenshot 2025-04-29 132923](https://github.com/user-attachments/assets/ede9c24c-7d9d-4de4-9030-5a0e2dbcd25e)

Creating Route Table:

![Screenshot 2025-04-29 132934](https://github.com/user-attachments/assets/3078edb9-c025-4972-9f84-a5f088c695bb)

Configuring Route Table:

![Screenshot 2025-04-29 132945](https://github.com/user-attachments/assets/cb423ea4-9d98-44b3-b46b-b6db7621d55a)

Editing Routes:

![Screenshot 2025-04-29 132956](https://github.com/user-attachments/assets/4b364e5c-8f6a-4a86-8804-1248152270af)

Creating Route Table:

![Screenshot 2025-04-29 133006](https://github.com/user-attachments/assets/3330cb76-4559-4f3e-9ecf-1ae577294d00)


# **PROJECT OVERVIEW**

Amazon Elastic Compute Cloud (Amazon EC2) is a cloud computing service provided by Amazon Web Services (AWS). It allows users to create and manage virtual servers in the cloud.

In this project, an EC2 instance is launched using the AWS Management Console. The instance provides a virtual computing environment where users can configure the operating system, 
manage storage, configure network settings, and access the server remotely.

# **PROJECT OBJECTIVE**

The main objectives of this project are:
- To understand the fundamentals of Amazon EC2.
- To launch and configure a virtual server in AWS.
- To select an appropriate Amazon Machine Image (AMI).
- To configure instance types and key pairs.
- To configure security groups and network access.
- To connect to the EC2 instance remotely.
- To understand basic cloud server management.

# **AWS SERVICES AND TECHNOLOGIES USED**

Service / Technology	Purpose
Amazon EC2	Virtual server hosting
Amazon Machine Image (AMI)	Operating system template
AWS VPC	Network environment
Security Groups	Firewall and traffic control
Key Pair	Secure server authentication
EBS	Persistent block storage
AWS Management Console	Manage AWS resources

# **KEY COMPONENTS OF EC2**

| Component      | Description                                     |
| -------------- | ----------------------------------------------- |
| Instance       | A virtual server running in AWS.                |
| AMI            | Template containing the operating system.       |
| Instance Type  | Defines CPU, RAM, and networking capacity.      |
| Key Pair       | Used for secure authentication.                 |
| Security Group | Controls incoming and outgoing traffic.         |
| VPC            | Provides an isolated virtual network.           |
| EBS            | Provides persistent block storage.              |
| Public IP      | Allows communication over the internet.         |
| Private IP     | Enables communication within a private network. |

# **PROJECT IMPLEMENTATION STEPS**

Step 1: Login to AWS

Open the AWS Management Console and sign in using your AWS account.

<img width="708" height="348" alt="image" src="https://github.com/user-attachments/assets/06b74bfe-e720-47a3-95bf-b2e342939baa" />

Step 2: Open EC2 Dashboard

Search for EC2 in the AWS console and select the EC2 service

<img width="694" height="346" alt="image" src="https://github.com/user-attachments/assets/5ee38019-c6d4-4afb-8430-6a3084a0fb50" />

Step 3: Select AMI

Choose an operating system such as Amazon Linux or Ubuntu

<img width="695" height="350" alt="image" src="https://github.com/user-attachments/assets/cefd518b-5f41-41d3-a3a9-bdc1ad4a000f" />

Step 4: Select Instance Type

Choose an instance type according to your CPU, RAM and workload requirements.

<img width="714" height="369" alt="image" src="https://github.com/user-attachments/assets/c51cd173-cabf-47bc-a2cc-2035736b5c17" />

Step 5: Create Key Pair

Create a key pair and download the private key file (.pem). Keep it secure.

<img width="735" height="404" alt="image" src="https://github.com/user-attachments/assets/3d76d130-c6a0-4c4c-b259-8951f84ab63b" />

Step 6: Configure Security Group

Configure inbound rules such as SSH (22), HTTP (80), and HTTPS (443), only when required. Restrict SSH access to your own IP.

<img width="728" height="394" alt="image" src="https://github.com/user-attachments/assets/f35a0b27-6836-4336-ace5-243253f3def1" />

Step 7: Configure Storage

Configure the EBS root volume according to your storage requirements.

<img width="729" height="383" alt="image" src="https://github.com/user-attachments/assets/89b966f8-978e-40bc-af72-849ff63502f3" />

Step 8: Launch Instance

Review all configurations and click Launch Instance. Wait until the instance reaches Running status and passes its status checks.

<img width="793" height="399" alt="image" src="https://github.com/user-attachments/assets/2de2d3e3-5fe1-4540-9959-21748c95b979" />

# **CONNECTING TO EC2 INSTANCE**

For a Linux EC2 instance, you can connect through SSH.

SSH command:

ssh -i "my-key.pem" ec2-user@PUBLIC-IP

# **C2 INSTANCE LIFECYCLE**

<img width="761" height="543" alt="image" src="https://github.com/user-attachments/assets/2d638415-604a-4534-afd9-ca65ce760ed1" />
















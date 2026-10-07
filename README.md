\# AWS EC2 Instance with SSH



\## Overview



Created an Amazon EC2 instance and connected to it securely using SSH and an EC2 key pair.



\## AWS Services



\- Amazon EC2

\- Amazon Linux 2023

\- EC2 Key Pair

\- SSH



\## Implementation



1\. Opened the Amazon EC2 console.

2\. Launched an Amazon Linux 2023 EC2 instance.

3\. Selected a free-tier eligible instance type.

4\. Created an RSA key pair in `.pem` format.

5\. Configured the security group to allow SSH access.

6\. Retrieved the instance public IPv4 address and public DNS.

7\. Connected to the instance using SSH from Windows CMD.



\## SSH Command



```bash

ssh -i "ec2-ssh-key.pem" ec2-user@<PUBLIC-DNS>


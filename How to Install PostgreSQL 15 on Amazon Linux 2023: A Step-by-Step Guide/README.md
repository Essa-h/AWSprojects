INTRODUCTION

PostgreSQL is a powerful open-source relational database management system widely used for storing and managing data. If you’ve recently installed Amazon Linux 2023 on your AWS EC2 instance and need guidance on how to install PostgreSQL 15

PRE-REQUISITES

Before you start, ensure you meet the following prerequisites:
1. An AWS EC2 instance running Amazon Linux 2023 with administrator privileges.
2. A minimum of 1GB of available hard disk space, 2GB of RAM, and a single-core CPU.

Step 1- Launching and Configuring Your EC2 Instance
1. Log in to AWS services and select EC2.
<img width="1680" alt="Screenshot 2024-07-08 at 3 55 40 PM" src="https://github.com/Essa-h/AWSprojects/assets/97895341/220b1bc0-61c4-43dc-aba3-4ad3a26ff361">
You can click to “launch instance” button for create a EC2 instance

2. Configure the instance name and the OS image as follows
<img width="1680" alt="Screenshot 2024-07-08 at 8 46 00 PM" src="https://github.com/Essa-h/AWSprojects/assets/97895341/7fa454b2-692c-4a7e-9c5a-b67142b65ccd">

3. Scroll down and configure the instance type and key pair
<img width="1680" alt="Screenshot 2024-07-08 at 8 48 44 PM" src="https://github.com/Essa-h/AWSprojects/assets/97895341/2f356602-d7c9-4382-ae80-77fc5ca2bdd3">

4. Create a security group
<img width="1680" alt="Screenshot 2024-07-08 at 8 49 55 PM" src="https://github.com/Essa-h/AWSprojects/assets/97895341/67ad39f2-839f-4e59-9c16-ff519791660d">

5. Modify to disk size as 20 GB
<img width="1680" alt="Screenshot 2024-07-08 at 8 52 26 PM" src="https://github.com/Essa-h/AWSprojects/assets/97895341/32d7653c-4d7d-443c-8d62-c080f1bba8bf">

6. Check the Summary and click Launch instance (right pane) under the Summary section to launch your EC2 instance.
<img width="803" alt="Screenshot 2024-07-08 at 8 53 54 PM" src="https://github.com/Essa-h/AWSprojects/assets/97895341/2d6136e9-4817-4296-8aa6-8b6b3007a473">
stance.


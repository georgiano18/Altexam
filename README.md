# AltExam

Altschool Second Semester Examination Project

**Documentation**: Provisioning the Server, Installing the Web Server, 
Deploying the HTML Page, and Configuring Networking

## Steps Taken to Set Up an Ubuntu Web Server with Apache

### Step 1: Provisioning the Server

1. Logged in to AWS using my IAM user credentials.
2. Created a new EC2 instance named "ALTSCHOOL" and started the instance.
3. Downloaded the key pair for the instance and noted its location on my 
local machine.
4. Configured the security group inbound rules to allow:
   - Port 22 (SSH) from my IP address
   - Port 80 (HTTP) from anywhere

### Step 2: Connecting to the Server

1. Opened the EC2 terminal and connected to the EC2 instance via SSH:
   ```bash
   ssh -i "MY_EC2_KEY.pem" ubuntu@54.166.55.135


# Lab 3 – Introduction to Amazon Elastic Compute Cloud (EC2)

## Author

* **Name**: V.SANTHOSH 
* **Register Number**: 212224230251
* **Date of Submission**: 17.03.2026
---

## Objective

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* Web browser with internet connectivity
* Basic knowledge of Linux commands (optional)

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Key Pair
* Security Group
* SSH Client (PuTTY / Terminal)

---

## Tasks Performed

### Task 1: Explore Amazon EC2 Dashboard

Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

---

### Task 2: Launch an EC2 Instance

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

---

### Task 3: Configure Security Group

Configure a security group to allow inbound access:

* SSH (Port 22) from your IP address
* HTTP (Port 80) from anywhere (0.0.0.0/0)

This security group acts as a firewall for the instance.

---

### Task 4: Connect to EC2 Instance

Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:

```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

---

### Task 5: Perform Basic Instance Operations

Perform the following operations from the EC2 console:

* Stop the instance
* Start the instance
* Reboot the instance

Observe the state changes of the instance.

---

### Task 6: Monitor EC2 Instance

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

---

### Task 7: Terminate EC2 Instance

Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.

---

## Workflow (Student Explanation)

Task 1: Launch Your Amazon EC2 Instance

Task 2: Monitor Your Instance

Task 3: Update Your Security Group and Access the Web Server

Task 4: Resize Your Instance: Instance Type and EBS Volume

Task 5: Explore EC2 Limits

Task 6: Test Stop Protection

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Dashboard / Instance List

<img width="1910" height="1192" alt="Screenshot 2026-02-27 132245" src="https://github.com/user-attachments/assets/38918826-47b9-4416-ad95-b88e33ad9014" />


---

### Screenshot 2: SSH Connection to Instance

<img width="1010" height="928" alt="Screenshot 2026-03-13 133432" src="https://github.com/user-attachments/assets/2c34baeb-ad6d-4586-9c28-b51869b01c4e" />

<img width="1913" height="1198" alt="Screenshot 2026-02-27 141847" src="https://github.com/user-attachments/assets/18a11f23-a1b9-4f61-9bfe-a1988b82114c" />

---

### Screenshot 3: Instance Monitoring / Status

<img width="1917" height="1052" alt="Screenshot 2026-02-27 142340" src="https://github.com/user-attachments/assets/80db4d6f-7927-4ebb-9f56-48e1a7e6c53d" />


---

## Result 

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.

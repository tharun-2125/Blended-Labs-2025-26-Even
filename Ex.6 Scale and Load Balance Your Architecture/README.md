# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
Author : your name   Reg no : yours   Date :

---

# NAME - THARUN N 
# REG NO - 212225240173

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

Describe step-by-step how you performed this experiment in your own words.

---

## Output Screenshots 

<img width="1920" height="1080" alt="Screenshot (113)" src="https://github.com/user-attachments/assets/0f14f7f8-a17e-4df2-b620-66aacc9aec3c" />
<img width="1920" height="1080" alt="Screenshot (115)" src="https://github.com/user-attachments/assets/48663aab-7dd6-4880-a846-00df1adfe9bc" />
<img width="1005" height="818" alt="Screenshot 2026-11-25 104315" src="https://github.com/user-attachments/assets/bfa348ea-aca3-43a4-bf7d-566ea71b2e41" />
<img width="1006" height="810" alt="Screenshot 2026-11-25 104433" src="https://github.com/user-attachments/assets/762832cf-9035-4ecb-bd4a-638be3ad3a49" />
<img width="1008" height="817" alt="Screenshot 2026-11-25 104528" src="https://github.com/user-attachments/assets/84d8f267-1c04-42f2-82e4-907803a57dd2" />
<img width="1002" height="610" alt="Screenshot 2026-11-25 104724" src="https://github.com/user-attachments/assets/b6c52f7e-34d7-4d97-9276-27de62489e66" />
<img width="896" height="790" alt="Screenshot 2026-11-25 105320" src="https://github.com/user-attachments/assets/020b61d7-689a-4d51-b92a-9db45780dd82" />
<img width="891" height="807" alt="Screenshot 2026-11-25 105414" src="https://github.com/user-attachments/assets/376eab2f-7b20-4646-a637-9ee92d3f140e" />


---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.

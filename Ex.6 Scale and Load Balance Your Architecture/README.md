# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
# Author : Ashwath p 
# Reg no : 212224220012
# Date :26/08/2026

---

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

---

## Output Screenshots 

<img width="943" height="922" alt="Screenshot 2026-08-19 201308" src="https://github.com/user-attachments/assets/bb11370e-29ba-4c0d-8029-8e7ed0e0044f" />

---

<img width="964" height="904" alt="Screenshot 2026-08-19 202033" src="https://github.com/user-attachments/assets/5db0b907-ea07-4062-ba1d-8e68e4f0ba46" />

<img width="948" height="664" alt="Screenshot 2026-08-19 204346" src="https://github.com/user-attachments/assets/1f0c34da-2b0b-4df3-a6c4-832dadd91a4e" />

<img width="947" height="915" alt="Screenshot 2026-08-19 211128" src="https://github.com/user-attachments/assets/11ecd7ae-0fba-4754-9373-004af47e3206" />

## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.

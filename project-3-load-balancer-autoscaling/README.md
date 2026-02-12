# Project 3 - Load Balancer + Auto Scaling

## Objective
Designed and implemented a highly available and fault-tolerant architecture using AWS Application Load Balancer and Auto Scaling Group with CPU-based dynamic scaling.

## Services Used
- EC2
- AMI
- Launch Template
- Application Load Balancer
- Auto Scaling Group
- Auto Scaling → Scaling policies → Add policy → Target tracking → CPU 60%

## 🏗 Architecture

User → Application Load Balancer → EC2 Instances (Auto Scaling Group)

Load Balancer distributes traffic.
Auto Scaling maintains and dynamically scales instances based on CPU usage.

## Scaling Config
Min:1
Desired:2
Max:3

## 📸 Screenshots

### Auto Scaling Group Configuration
![ASG Config](Screenshot 2026-02-13 014438.png)

### EC2 Instances Running
![EC2 Instances](Screenshot 2026-02-13 011237.png)

### Target Group Healthy
![Target Group](Screenshot 2026-02-13 012138.png)

### Load Balancer DNS Working
![Load Balancer](Screenshot 2026-02-13 012505.png)


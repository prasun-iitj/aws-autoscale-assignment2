# Assignment 2 — AWS EC2 Auto Scaling & Security

## Overview
This project demonstrates setting up a Virtual Machine on AWS with 
Auto Scaling and Security configurations.

## Cloud Platform
Amazon Web Services (AWS)

## Services Used
- EC2 (Virtual Machine)
- Auto Scaling Group
- Application Load Balancer
- IAM Roles
- Security Groups (Firewall)

## Auto Scaling Policy
- Minimum instances: 1
- Maximum instances: 3
- Scale out trigger: CPU > 70%
- Scale in: Automatic when load drops

## Security Implemented
- SSH access restricted to admin IP only
- HTTP/HTTPS open to public
- IAM role with least privilege (CloudWatch only)
- All other ports denied by default

## Demo Video
[Click here to watch the demo]([YOUR-VIDEO-LINK-HERE](https://www.youtube.com/watch?v=URprMfupTwg))

## Screenshots
All screenshots are uploaded in this repository.

# AWS DevSecOps Security Project

## Overview
This project demonstrates a secure CI/CD pipeline integrating DevOps and security practices using AWS.

## Architecture
GitHub → GitHub Actions → Security Scan → AWS EC2 → CloudWatch Monitoring

## Security Features
- Integrated security scanning in CI/CD pipeline
- IAM-based access control (Least Privilege)
- Network security using Security Groups
- Continuous monitoring using CloudWatch

## Pipeline Workflow
1. Code push triggers pipeline
2. Security scan (npm audit)
3. Deployment to AWS EC2
4. Monitoring enabled via CloudWatch

## Tools Used
- GitHub Actions (CI/CD)
- AWS EC2 (Compute)
- IAM (Access Control)
- CloudWatch (Monitoring)

## Screenshots
(Add images here)

## Outcome
- Reduced deployment risk using security checks
- Automated secure application delivery
- Improved cloud security posture

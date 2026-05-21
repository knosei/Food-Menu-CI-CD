# 🍔 Food Menu CI/CD Pipeline 

A production-grade CI/CD pipeline for a containerized food delivery application deployed on AWS using ECS Fargate, ECR, and GitHub Actions.

This project demonstrates how modern SaaS teams automate deployments to achieve **zero-downtime releases, scalability, and consistency across environments**.

---
## The Challenge

FreshEats, a fast-growing food delivery startup, is rapidly adding new features to its backend services to support menus, pricing updates, and promotions.

Currently, the engineering team:

- Builds and deploys applications manually
- Runs updates directly on servers
- Faces downtime during deployments
- Experiences inconsistent environments across releases

As the platform scales, this approach leads to:

- Slower release cycles
- Deployment errors
- Difficulty rolling out fixes quickly
- Increased operational risk

---
## What I Built

![Architecture Diagram](Screenshots/architecture-diagram.png)

Design and implement a fully automated CI/CD pipeline that takes application code from development to production without downtime:

- **Docker** - Containerize the application
- **RDS Database** - PostgreSQL/MySQL database for patient data
- **VPC & Networking** - Isolated network with public/private subnets
- **Security Groups** - Network security rules controlling access
- **IAM Roles** - Role-based access control between resources

---

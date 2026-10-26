# AWS ECS Fargate CI/CD Project 

## Project Overview
Automated deployment of a containerized website using AWS CI/CD services.

## Technologies Used
- GitHub
- Docker
- Amazon ECR
- AWS CodeBuild
- AWS CodePipeline
- Amazon ECS Fargate
- Application Load Balancer (ALB)

## Architecture
GitHub → CodePipeline → CodeBuild → Amazon ECR → ECS Fargate → ALB

## Implementation
1. Created a Docker image using Nginx.
2. Pushed the image to Amazon ECR.
3. Configured ECS Fargate and an Application Load Balancer.
4. Automated build and deployment using CodePipeline.
5. Tested website updates through GitHub commits.

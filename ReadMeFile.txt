# CI/CD Implementation Details

This project demonstrates a complete CI/CD pipeline using GitHub Actions to deploy a Node.js application to AWS EC2.

## Pipeline Features:
- Automated testing on every push, since test cases are not included, they won't run.
- Docker image building and saving it 
- Zero-downtime deployment to EC2
- GitHub Actions workflow

## How it works:
1. On push to main branch, GitHub Actions:
   - Builds Docker image
   - Deploys to EC2 instance
2. The EC2 instance runs the Docker container on port 80

Hence a complete CI/CD pipeline with deployment automation on EC2 instance.

Access the live demo at: http://your-ec2-ip

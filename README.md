# CloudMart

## Project Overview
The MultiCloud DevOps & AI Challenge[^1] was an intensive bootcamp focused on building CloudMart, a sophisticated e-commerce platform. The project demonstrated the seamless integration of multiple cloud services, incorporating AWS, Google Cloud, and Azure infrastructures. Throughtout the bootcamp, I developed a modern application using a real-world use case that showcased container orchestration, automated deployment pipelines, AI-powered customer interactions, and cross-cloud analytics capabilities.

![cloudmart-architecture-overview](https://github.com/user-attachments/assets/706aca4c-484e-4e03-81ce-71c254918b1b)

## Daily Challenge Highlights
### Day 1: Foundation Setup
The first day focused on establishing the fundamental infrastructure using infrastructure as Code principles. I used Terraform to provision essential AWS services, including an EC2 workstation and multiple DynamoDB tables for product, order, and ticket management. There was a heavy emphasis on the importance of automated infrastructure provisioning and proper IAM role configuration for secure access management.

### Day 2: Container Architecture
Day two introduced containerization and orchestration concepts. I installed Docker on AWS EC2 instances and created Docker images for CloudMart's frontend and backend components. The day cumulated in deploying a Kubernetes cluster using AWS EKS, complete with load balancers and service accounts, establishing a robust container orchestration environment for the application.

### Day 3: Automation Pipeline
The third day centered on implementing continuous integration and continuous deployment practices. I built an automated CI/CD pipeline using AWS CodePipeline and CodeBuild, enabling automatic Docker image creation and deployment processes. This automation streamlined the development workflow, allowing for efficient code updates and deployment management through GitHub integration.

### Day 4: AI Integration
Day four marked the introduction of artificial intelligence into the application. I implemented Lambda functions for Amazon Bedrock integration and created two AI agents: a product recommendation system using Claude 3 Sonnet and a customer support assistant powered by OpenAI's GPT-4. These integrations enhanced the application's user experience with intelligent product suggesstions and presented a solution to automating customer support.

### Day 5: Multi-Cloud Analytics
The final day expanded the application's capabilities across multiple cloud providers. I created an event-driven microservice in AWS Lambda to store order data in Google Cloud BigQuery for analytics. Additionally, I implemented Azure AI Language Service for analyzing customer support conversations, demonstrating the power of multi-cloud architecture and advanced analytics capabilities.

## Key Technical Stack
- **AWS:** EKS, EC2, Lambda, CodePipeline, CodeBuild, DynamoDB, Bedrock
- **Containerization:** Docker, Kubernetes
- **Infrastructure as Code:** Terraform
- **AI Services:** Amazon Bedrock, OpenAI, Anthropic Claude, Azure AI
- **Google Cloud:** BigQuery
- **Version Control:** GitHub

## Video Demo
https://github.com/user-attachments/assets/3379aa3e-4aa4-459a-bac7-c26d5ea2606a



<img alt="DOCKER BADGE" src="https://github.com/user-attachments/assets/bdda88f1-3dba-455b-958a-7b73d016aa3f" width="200">
<img alt="KUBERNETES BADGE" src="https://github.com/user-attachments/assets/a0ccd526-9a1e-43b0-8afa-47b39b39cd65" width="200">
<img alt="AWS BADGE" src="https://github.com/user-attachments/assets/f076bf1c-6ce0-4fa8-b990-edd2f667b75f" width="200">
<img alt="CLAUDE BADGE" src="https://github.com/user-attachments/assets/7738aee8-e858-40e2-90d9-bd77e8466c9d" width="200">
<img alt="OPENAI BADGE" src="https://github.com/user-attachments/assets/a1f23867-2471-4e90-b800-5981a7bc9714" width="200">
<img alt="GCP BADGE" src="https://github.com/user-attachments/assets/877f76c9-c077-4618-9d67-9d999661a73b" width="200">
<img alt="AZURE BADGE" src="https://github.com/user-attachments/assets/34b193e1-b4c2-45b5-96f9-ff5388071d46" width="200">
<!-- ![EN_MDAC_VIP_BADGE_DOCKER](https://github.com/user-attachments/assets/bdda88f1-3dba-455b-958a-7b73d016aa3f)
![EN_MDAC_VIP_BADGE_KUBERNETES](https://github.com/user-attachments/assets/a0ccd526-9a1e-43b0-8afa-47b39b39cd65)
![EN_MDAC_VIP_BADGE_AWS](https://github.com/user-attachments/assets/f076bf1c-6ce0-4fa8-b990-edd2f667b75f)
![EN_MDAC_VIP_BADGE_CLAUDE](https://github.com/user-attachments/assets/7738aee8-e858-40e2-90d9-bd77e8466c9d)
![EN_MDAC_VIP_BADGE_OPENAI](https://github.com/user-attachments/assets/a1f23867-2471-4e90-b800-5981a7bc9714)
![EN_MDAC_VIP_BADGE_GCP](https://github.com/user-attachments/assets/877f76c9-c077-4618-9d67-9d999661a73b)
![EN_MDAC_VIP_BADGE_AZURE](https://github.com/user-attachments/assets/34b193e1-b4c2-45b5-96f9-ff5388071d46) -->

[^1]: The MultiCloud DevOps & AI Challenge is taught at The Cloud Bootcamp by Jean Rodrigues.

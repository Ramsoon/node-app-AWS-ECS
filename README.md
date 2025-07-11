## Node.js Application Deployment on AWS ECS with NFS Volume & MongoDB Atlas
# node-app-AWS-ECS
This project leverage on Fargate (serveless)

I recently completed the deployment of a Node.js application on AWS ECS (Elastic Container Service), leveraging a cloud-native architecture for scalability and reliability.

What I did?

Containerized the Node.js app and deployed it on AWS ECS Fargate, ensuring seamless orchestration and isolated workloads.
Integrated an  volume (via Amazon EFS) for persistent file storage, enabling shared access across ECS tasks.
Connected to a managed MongoDB Atlas cluster, enabling secure, remote database operations directly from the AWS-hosted application.
Configured a Load Balancer via Elastic Load Balancing (ELB) to ensure stable domain routing and high availability across services.
Managed environment variables, secrets, and network access using AWS ECS task definitions and IAM roles.
I ensured secure communication between services with VPC configuration and proper security group setups.

This setup provided a reliable, scalable, and fully managed environment to support production workloads while minimizing infrastructure overhead.

# DevOps_Interview-questions

- Difference in AWS role and policies?
- Different types of policies?
- What is a principle in policies?
- what is identity center?
- What are the prerequisites for setting up AWS Control Tower?
- What are the different accounts in AWS Control Tower?

**Terraform / Infrastructure as Code:**

1. What is Terraform, and how is it different from CloudFormation?
2. What are Terraform modules, and how do you use them?
3. How do you manage environments in Terraform using Terragrunt?
4. Explain the structure you use for organizing Terraform and Terragrunt code.
5. What are some common issues you’ve faced with Terraform state files, and how did you resolve them?
6. How do you use Terraform to create an EKS cluster or S3 + CloudFront setup?
7. What are Service Control Policies (SCPs), and how do you implement them using Terraform?
8. What are lockup functions?
9. What is the tolist function?
10. What if you need to create one resource in only one environment? - Answer: Count we can use.

**CI/CD (GitLab, Jenkins, Octopus):**

8. Explain how you’ve built a GitLab CI/CD pipeline for a React or Node.js application.

9. How do you use GitLab to push Docker images to ECR?

10. How do you use GitLab OIDC for authentication to AWS?

11. Describe the deployment process using GitLab stages (dev, int, qa, prod).

12. How do you manage secure environment variables in a GitLab pipeline?

13. How do you use Jenkins for deploying Terraform infrastructure?

**Docker / Containers:**

14. How do you write a Dockerfile for a Node.js/React app?

15. How do you optimize Docker image build times?

16. How do you handle multi-stage builds?

**AWS Services (Advanced):**

17. Explain the architecture of a project you’ve built using AWS Cognito, API Gateway, Lambda, and DynamoDB.

18. How do you configure IAM roles and policies for different environments?

19. How do you secure S3 buckets and enforce encryption at rest and in transit?

20. What is a bastion host, and how do you configure one for accessing EKS?

21. How do you implement cost optimization using automation (e.g., EC2 start/stop, key rotation with Lambda)?

22. What are AWS Organizations, and how do you use SCPs to restrict non-US regions?

**Monitoring / Logging / Security:**

23. How do you enforce KMS key rotation and S3 public access block with SCPs?

24. How do you log user activities in your applications?

## **Kubernetes Interview Questions**

1. How do you deploy an application on EKS using Terraform?
2. What is ArgoCD and how have you used it for deploying applications to Kubernetes?
3. How do you configure a bastion host to access an EKS cluster securely?
4. What are some Kubernetes add-ons you’ve deployed and managed on EKS?
5. How do you handle secrets and config maps in Kubernetes?
6. What is the difference between a Deployment, StatefulSet, and DaemonSet in Kubernetes?
7. How do you monitor and troubleshoot pods running in EKS?
8. How do you perform a rolling update and rollback in Kubernetes?
9. How do you handle autoscaling (HPA/Cluster Autoscaler) in EKS?
10. How do you implement GitOps using ArgoCD?

---

## 🔹 **DevOps Interview Questions**

1. Describe the CI/CD pipeline you implemented using GitLab.
2. How do you promote deployments through dev, int, qa, and prod environments?
3. How do you use OIDC to authenticate GitLab pipelines with AWS?
4. How do you handle secrets and environment variables securely in CI/CD pipelines?
5. What is the difference between GitOps and traditional CI/CD?
6. Describe a scenario where you automated security (e.g., IAM key rotation, EC2 stop/start).
7. How do you implement cost control automation in AWS using Lambda?
8. How do you use Jenkins to run Terraform and deploy infrastructure?
9. Describe a KT (Knowledge Transfer) session you gave about Infrastructure as Code.
10. What are the benefits of using Terragrunt with Terraform?

---

## 🔹 **Docker Interview Questions**

1. How do you write a Dockerfile for a React/Node.js application?
2. What is a multi-stage Docker build, and why is it used?
3. How do you push Docker images to AWS ECR using GitLab pipelines?
4. How do you authenticate Docker to ECR using IAM OIDC roles?
5. What is the difference between ENTRYPOINT and CMD in Docker?
6. How do you run and test Docker containers locally during development?
7. How do you optimize Docker image sizes and build times?
8. How do you handle Docker networking between multiple containers (e.g., Node.js + DB)?
9. How do you debug a failing container in a CI/CD pipeline?
10. How do you manage Docker caching in CI/CD for faster builds?

---

## 🔹 **AWS Interview Questions**

### ✅ **Core Services & Architecture**

1. How do you architect a serverless application using Lambda, API Gateway, and DynamoDB?
2. How do you use AWS Cognito for authentication and user management?
3. How do you host a static website using S3 and CloudFront?
4. What is your experience with AWS Amplify in web applications?
5. What are best practices for IAM role and policy design in a multi-account setup?

### ✅ **Networking & Security**

1. How do you restrict AWS services or regions using SCPs?
2. What is the use of a bastion host and how do you secure access to private infrastructure?
3. How do you enforce TLS or S3 public access block at the organization level?

### ✅ **Automation & Monitoring**

1. How do you use Lambda to automate tasks like cost optimization or IAM key rotation?
2. How do you monitor infrastructure and application logs in AWS?

### ✅ **Cost Management**

1. How did you integrate CloudZero for cost analysis and management?
2. What are cost-saving strategies you have implemented in AWS projects?

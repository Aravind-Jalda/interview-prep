# AWS Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. What is AWS?
AWS (Amazon Web Services) is a cloud platform that provides services like compute, storage, networking, and databases on demand.

---

## 2. What is EC2?
EC2 (Elastic Compute Cloud) provides virtual servers in the cloud.  
You can launch, stop, and scale instances based on your needs.

---

## 3. What is S3?
S3 (Simple Storage Service) is object storage used to store files like images, backups, logs, etc.  
It is highly durable and scalable.

---

## 4. What is VPC?
VPC (Virtual Private Cloud) is a private network inside AWS.  
You can control IP range, subnets, routing, and security.

---

## 5. What is a subnet?
A subnet is a smaller network inside a VPC.  
Types:
- Public subnet → has internet access  
- Private subnet → no direct internet access  

---

## 6. What is Internet Gateway?
Internet Gateway allows communication between VPC and the internet.

---

## 7. What is Security Group?
Security Group acts as a firewall for EC2 instances.  
It controls inbound and outbound traffic.

---

## 8. What is NACL?
Network ACL is another layer of security at subnet level.  
Unlike security groups, it is stateless.

---

## 9. What is IAM?
IAM (Identity and Access Management) is used to manage users, roles, and permissions in AWS.

---

## 10. What is an IAM Role?
IAM Role is used to grant permissions to AWS services without using credentials.  
Example: EC2 accessing S3.

---

## 11. What is Auto Scaling?
Auto Scaling automatically increases or decreases EC2 instances based on load.

---

## 12. What is Load Balancer?
Distributes traffic across multiple servers.  
Types:
- Application Load Balancer (ALB)
- Network Load Balancer (NLB)

---

## 13. What is RDS?
RDS (Relational Database Service) is a managed database service.  
Supports MySQL, PostgreSQL, etc.

---

## 14. What is CloudWatch?
CloudWatch is used for monitoring logs, metrics, and alarms in AWS.

---

## 15. What is CloudTrail?
CloudTrail records API activity and user actions in AWS.  
Used for auditing and security.

---

## 16. What is EBS?
EBS (Elastic Block Store) is storage attached to EC2 instances.  
Used like a hard disk.

---

## 17. What is Route 53?
Route 53 is a DNS service used to route traffic to your applications.

---

## 18. What is AMI?
AMI (Amazon Machine Image) is a template used to launch EC2 instances.

---

## 19. What is Elastic IP?
Elastic IP is a static public IP address assigned to an EC2 instance.

---

## 20. What is Infrastructure as Code?
Managing infrastructure using code (Terraform, CloudFormation).  
Helps automate provisioning.

---

## Bonus: How AWS is used in DevOps?

- Host applications (EC2, ECS, EKS)
- Store data (S3)
- Automate deployments (CodePipeline, Jenkins)
- Monitor systems (CloudWatch)

---

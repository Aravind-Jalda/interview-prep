# AWS Scenario-Based Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. Your website is down. How do you troubleshoot?

Steps:
- Check EC2 instance status
- Verify security group (port 80/443 open)
- Check load balancer health
- Check application logs
- Verify DNS (Route 53)

---

## 2. EC2 instance is not reachable. What will you check?

- Security group rules
- NACL rules
- Instance status (running/stopped)
- SSH key and permissions
- Network configuration (public IP, subnet)

---

## 3. Disk is full in EC2. What will you do?

- Check disk usage: df -h  
- Find large files: du -sh *  
- Clean logs or temp files  
- Increase EBS volume size  
- Extend filesystem  

---

## 4. High CPU usage in EC2. How to handle?

- Check processes (top, ps)  
- Restart application if needed  
- Scale using Auto Scaling  
- Optimize application  

---

## 5. How do you design a highly available application?

- Use multiple AZs  
- Use load balancer  
- Use Auto Scaling  
- Store data in managed services (RDS, S3)  

---

## 6. How do you secure AWS environment?

- Use IAM roles (no hardcoded keys)  
- Enable MFA  
- Restrict security groups  
- Use private subnets  
- Enable logging (CloudTrail)

---

## 7. How do you reduce AWS cost?

- Stop unused EC2 instances  
- Use reserved instances  
- Delete unused resources  
- Use S3 lifecycle policies  
- Monitor billing  

---

## 8. How do you allow EC2 to access S3?

- Create IAM role  
- Attach role to EC2  
- Grant S3 permissions  

---

## 9. How do you deploy application in AWS?

Steps:
- Launch EC2  
- Install dependencies  
- Deploy code  
- Configure load balancer  
- Set up DNS  

---

## 10. How do you monitor applications in AWS?

- Use CloudWatch metrics  
- Create alarms  
- Monitor logs  
- Use dashboards  

---

## 11. How do you handle traffic spike?

- Enable Auto Scaling  
- Use load balancer  
- Optimize backend  

---

## 12. RDS database is slow. What will you check?

- CPU and memory usage  
- Slow queries  
- Indexing  
- Storage performance  

---

## 13. How do you backup data in AWS?

- Use S3 for backups  
- Enable RDS snapshots  
- Use lifecycle policies  

---

## 14. How do you restrict access to production?

- Use IAM roles  
- Limit user permissions  
- Use security groups  
- Enable approval process  

---

## 15. How do you migrate application to AWS?

- Lift and shift (EC2)  
- Use managed services  
- Test and validate  

---

## 16. How do you handle logs in AWS?

- Store logs in CloudWatch  
- Export to S3  
- Analyze logs  

---

## 17. What will you do if S3 data is deleted accidentally?

- Enable versioning  
- Restore previous version  
- Use backup strategy  

---

## 18. How do you connect private EC2 to internet?

- Use NAT Gateway  
- Configure route table  

---

## 19. How do you manage secrets in AWS?

- Use AWS Secrets Manager  
- Use IAM roles  
- Avoid hardcoding  

---

## 20. Explain a real-time AWS project

Example:

"I worked on deploying application in AWS where:
- EC2 was used for hosting  
- ALB handled traffic  
- Auto Scaling managed load  
- S3 stored static files  
- CloudWatch monitored system"

---

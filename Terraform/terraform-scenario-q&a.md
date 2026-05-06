# Terraform Scenario-Based Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. Terraform apply failed. What will you do?

- Check error message  
- Fix configuration  
- Run plan again  
- Re-apply  

---

## 2. State file is corrupted. What will you do?

- Restore from backup  
- Use remote state  
- Avoid manual edits  

---

## 3. How do you manage multiple environments?

- Use workspaces  
- Use separate state files  
- Use variables  

---

## 4. How do you share Terraform state?

- Use remote backend (S3, Azure Storage)  
- Enable locking  

---

## 5. How do you handle drift?

- Run terraform plan  
- Compare changes  
- Apply updates  

---

## 6. Resource not created. What will you check?

- Configuration  
- Dependencies  
- Permissions  

---

## 7. How do you reuse code?

- Use modules  
- Create reusable templates  

---

## 8. How do you pass variables?

- CLI  
- tfvars file  
- environment variables  

---

## 9. How do you secure Terraform?

- Do not store secrets in code  
- Use secret managers  
- Restrict access  

---

## 10. How do you manage secrets?

- Use environment variables  
- Use secret manager (AWS Secrets Manager)  

---

## 11. How do you debug Terraform?

- Check logs  
- Use terraform plan  
- Enable debug mode  

---

## 12. How do you automate Terraform?

- Use CI/CD pipelines  
- Run plan and apply automatically  

---

## 13. How do you destroy specific resource?

terraform destroy -target=resource_name

---

## 14. How do you update infrastructure?

- Modify configuration  
- Run terraform apply  

---

## 15. How do you handle dependencies?

- Terraform auto detects  
- Use depends_on if needed  

---

## 16. How do you monitor Terraform runs?

- Check logs  
- Use CI/CD tools  

---

## 17. How do you handle large infrastructure?

- Use modules  
- Split configurations  

---

## 18. How do you rollback changes?

- Revert code  
- Apply previous configuration  

---

## 19. How do you handle concurrency?

- Use remote backend with locking  

---

## 20. Explain real-time Terraform usage

Example:

"I used Terraform to create AWS infrastructure including EC2, S3, and VPC.  
Used remote state and integrated with Jenkins pipeline."

---

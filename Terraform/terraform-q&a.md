# Terraform Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. What is Terraform?
Terraform is an Infrastructure as Code (IaC) tool used to create and manage infrastructure using code.

---

## 2. What is Infrastructure as Code (IaC)?
IaC means managing infrastructure using code instead of manual setup.  
It helps in automation and consistency.

---

## 3. What is a provider in Terraform?
A provider is a plugin that allows Terraform to interact with cloud platforms.  
Example: AWS, Azure.

---

## 4. What is a resource in Terraform?
A resource is a component like EC2, S3, or VM that Terraform creates.

---

## 5. What is a Terraform configuration file?
It is a `.tf` file where infrastructure is defined.

---

## 6. What is terraform init?
Initializes Terraform project and downloads providers.

---

## 7. What is terraform plan?
Shows what changes Terraform will make before applying.

---

## 8. What is terraform apply?
Creates or updates infrastructure based on configuration.

---

## 9. What is terraform destroy?
Deletes all resources managed by Terraform.

---

## 10. What is state file?
Terraform state file stores the current state of infrastructure.

---

## 11. Why state file is important?
It helps Terraform track resources and detect changes.

---

## 12. What is remote state?
Storing state file in remote storage (like S3) for team collaboration.

---

## 13. What is terraform refresh?
Updates state file with real infrastructure.

---

## 14. What is variable in Terraform?
Variables allow dynamic values.

Example:
variable "region" {}

---

## 15. What is output in Terraform?
Outputs display values after execution.

---

## 16. What is module in Terraform?
Module is a reusable block of code.

---

## 17. What is terraform workspace?
Used to manage multiple environments (dev, prod).

---

## 18. What is dependency in Terraform?
Resources depend on each other and are created in order.

---

## 19. What is drift in Terraform?
When actual infrastructure differs from Terraform state.

---

## 20. How Terraform is used in DevOps?

- Automate infrastructure  
- Manage cloud resources  
- Maintain consistency  
- Integrate with CI/CD  

---

## Bonus Example

terraform init → plan → apply

---

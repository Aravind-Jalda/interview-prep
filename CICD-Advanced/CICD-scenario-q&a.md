# CI/CD Advanced Scenario-Based Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. Pipeline is failing. What will you do?

- Check logs  
- Identify failed stage  
- Fix issue  
- Re-run pipeline  

---

## 2. Deployment failed in production. What will you do?

- Rollback to previous version  
- Identify issue  
- Fix and redeploy  

---

## 3. How do you design CI/CD pipeline?

Steps:
- Code commit trigger  
- Build stage  
- Test stage  
- Artifact creation  
- Deploy to environments  

---

## 4. How do you implement Blue-Green deployment?

- Maintain two environments  
- Deploy new version to idle environment  
- Switch traffic  

---

## 5. How do you implement Canary deployment?

- Deploy to small users  
- Monitor performance  
- Gradually increase traffic  

---

## 6. How do you secure pipeline?

- Use secrets management  
- Avoid hardcoding  
- Restrict access  

---

## 7. How do you handle multiple environments?

- Use environment variables  
- Use separate configs  
- Deploy step-by-step  

---

## 8. Build is successful but deployment failed. Why?

- Environment issue  
- Configuration issue  
- Network issue  

---

## 9. How do you reduce pipeline time?

- Use caching  
- Run stages in parallel  
- Optimize build  

---

## 10. How do you manage artifacts?

- Store in repository  
- Use versioning  
- Deploy correct version  

---

## 11. How do you handle rollback?

- Use previous artifact  
- Redeploy  
- Verify  

---

## 12. How do you integrate Docker in CI/CD?

- Build image  
- Push to registry  
- Deploy container  

---

## 13. How do you integrate Kubernetes?

- Deploy using kubectl/Helm  
- Monitor deployment  

---

## 14. How do you monitor pipeline?

- Check logs  
- Use alerts  
- Track failures  

---

## 15. How do you handle secrets?

- Use secret manager  
- Use environment variables  

---

## 16. How do you automate testing?

- Add test stage  
- Run unit/integration tests  

---

## 17. How do you handle merge requests?

- Trigger pipeline  
- Run checks  
- Approve and merge  

---

## 18. How do you debug pipeline issues?

- Analyze logs  
- Reproduce issue  
- Fix step  

---

## 19. How do you design highly reliable pipeline?

- Add retries  
- Add rollback  
- Add monitoring  

---

## 20. Real-time answer (Interview Ready)

Example:

"I designed CI/CD pipeline where code push triggers build, tests run, Docker image is created, pushed to registry, and deployed to Kubernetes with rollback strategy."

---

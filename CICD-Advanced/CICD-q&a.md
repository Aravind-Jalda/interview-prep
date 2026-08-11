# CI/CD Advanced Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. What is CI/CD pipeline?
A CI/CD pipeline is a sequence of automated steps to build, test, and deploy applications.

---

## 2. What are stages in a pipeline?
Common stages:
- Build  
- Test  
- Deploy  

Advanced pipelines include:
- Code scan  
- Security scan  
- Approval stages  

---

## 3. What is multi-stage pipeline?
Pipeline divided into multiple stages for better control and visibility.

---

## 4. What is Blue-Green deployment?
Two environments:
- Blue (current)
- Green (new)

Traffic is switched to new environment after testing.

---

## 5. What is Canary deployment?
Deploy new version to small percentage of users first, then gradually increase.

---

## 6. What is rolling deployment?
Gradually replace old instances with new ones.

---

## 7. What is rollback strategy?
Revert to previous stable version if deployment fails.

---

## 8. What is pipeline as code?
Defining pipeline using code (Jenkinsfile, YAML).

---

## 9. What is artifact in CI/CD?
Build output stored for deployment.  
Example: JAR, Docker image.

---

## 10. What is artifact repository?
Stores build artifacts.  
Example: Nexus, Artifactory.

---

## 11. What is versioning?
Assigning versions to builds.  
Example: v1.0.0

---

## 12. What is environment separation?
Using different environments:
- Dev  
- QA  
- Prod  

---

## 13. What is approval process?
Manual approval before production deployment.

---

## 14. What is pipeline trigger?
Pipeline starts automatically on:
- Code push  
- Pull request  

---

## 15. What is parallel execution?
Running multiple stages at same time to reduce time.

---

## 16. What is pipeline failure handling?
- Stop pipeline  
- Notify team  
- Fix issue  
- Retry  

---

## 17. What is secret management in CI/CD?
Store credentials securely using tools or environment variables.

---

## 18. What is code quality check?
Using tools like SonarQube to analyze code.

---

## 19. What is CI/CD best practice?

- Automate everything  
- Use version control  
- Secure pipelines  
- Monitor pipelines  

---

## 20. Example pipeline flow

Code → Build → Test → Scan → Deploy → Monitor

---

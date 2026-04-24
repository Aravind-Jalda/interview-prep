# Jenkins Interview Questions & Answers (DevOps - 4 Years)

---

## 1. What is Jenkins?
Jenkins is an open-source automation tool used for CI/CD (Continuous Integration and Continuous Deployment).  
It helps automate building, testing, and deploying applications.

---

## 2. What is CI/CD?
- CI (Continuous Integration) → Automatically build and test code when changes are pushed  
- CD (Continuous Deployment/Delivery) → Automatically deploy code to environments  

Jenkins is widely used to implement CI/CD pipelines.

---

## 3. What is a Jenkins job?
A Jenkins job is a task or project that Jenkins executes.  
Examples:
- Build job
- Test job
- Deployment job

---

## 4. What is a Jenkins pipeline?
A pipeline is a sequence of steps defined as code to automate the CI/CD process.  
It includes stages like build, test, and deploy.

---

## 5. What is Jenkinsfile?
A Jenkinsfile is a script written in Groovy that defines the pipeline.  
It is stored in the Git repository.

---

## 6. What are the types of pipelines?
- Declarative pipeline → simple and structured  
- Scripted pipeline → flexible and complex  

Declarative is mostly used in real projects.

---

## 7. Example of a simple pipeline
pipeline {
agent any
stages {
stage('Build') {
steps {
echo 'Building...'
}
}
}
}

---

## 8. What is an agent in Jenkins?
Agent is the machine where Jenkins runs the job.  
It can be:
- Master node
- Worker node (agent)

---

## 9. What is master and agent concept?
- Master → controls Jenkins, schedules jobs  
- Agent → executes jobs  

Used to distribute load.

---

## 10. What are Jenkins plugins?
Plugins extend Jenkins functionality.  
Examples:
- Git plugin
- Docker plugin
- Pipeline plugin

---

## 11. How Jenkins integrates with Git?
Jenkins pulls code from Git repositories using webhooks or polling.  
Whenever code is pushed, Jenkins pipeline gets triggered automatically.

---

## 12. What is webhook?
Webhook is a trigger from Git (GitHub/Bitbucket) to Jenkins when code changes occur.  
It helps in automatic pipeline execution.

---

## 13. What is build trigger?
It defines when a job should run.

Types:
- Manual trigger  
- Poll SCM  
- Webhook  
- Scheduled (cron)

---

## 14. What is a stage in pipeline?
A stage represents a step in the pipeline.

Examples:
- Build  
- Test  
- Deploy  

It helps in better visibility and tracking.

---

## 15. What is post block in pipeline?
Used to define actions after pipeline execution.

Example:
- success → run when pipeline succeeds  
- failure → run when pipeline fails  

---

## 16. How to handle credentials in Jenkins?
Jenkins provides a credentials store to securely store secrets like:
- passwords  
- API keys  
- SSH keys  

Used in pipelines via credentials binding.

---

## 17. What is Blue Ocean?
Blue Ocean is a modern UI for Jenkins pipelines.  
It provides better visualization of pipeline stages.

---

## 18. What is Jenkins workspace?
Workspace is the directory where Jenkins stores project files and builds during execution.

---

## 19. How do you debug a failed Jenkins job?
Steps:
- Check console output  
- Verify logs  
- Check script errors  
- Validate environment variables  
- Re-run job with debug options  

---

## 20. How Jenkins is used in DevOps?
Jenkins automates:
- Code build  
- Testing  
- Deployment  
- Integration with tools like Docker, Kubernetes  

Example flow:
Code push → Jenkins build → Test → Deploy

---

## Bonus: Real-Time Use Case

- Developer pushes code to Git  
- Webhook triggers Jenkins  
- Jenkins builds Docker image  
- Pushes image to registry  
- Deploys to Kubernetes  

---

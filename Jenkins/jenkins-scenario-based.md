# Jenkins Scenario-Based Interview Questions & Answers (DevOps - 2-5 Years)

---

## 1. You pushed wrong code to production via Jenkins. What will you do?

First, I will immediately stop any ongoing deployments in Jenkins.  
Then:
- Rollback to previous stable version (using previous build or artifact)
- Identify root cause (wrong branch / manual trigger / config issue)
- Fix pipeline safeguards (branch restriction, approval step)

Prevention:
- Add approval before production deploy
- Restrict main branch deployments

---

## 2. Jenkins job is failing. How do you debug?

Steps:
1. Check console output logs
2. Identify exact stage where failure occurred
3. Verify script errors or command issues
4. Check environment variables and credentials
5. Re-run with debug (set -x in scripts)

---

## 3. How do you design a CI/CD pipeline?

Basic pipeline stages:
1. Code checkout (Git)
2. Build (Maven/npm)
3. Test (unit tests)
4. Code quality (SonarQube)
5. Build artifact (JAR/Docker image)
6. Push artifact (Nexus/Docker registry)
7. Deploy (Dev → QA → Prod)

---

## 4. How do you trigger Jenkins automatically on code push?

Use webhook:
- Configure webhook in GitHub/Bitbucket
- Provide Jenkins endpoint URL
- Jenkins listens and triggers pipeline automatically

---

## 5. How do you handle multiple environments (Dev, QA, Prod)?

Approach:
- Use parameters in pipeline
- Maintain separate configs for each environment
- Use conditional stages

Example:
if (env == "prod") {
  deploy to prod
}

---

## 6. How do you secure Jenkins?

Steps:
- Enable authentication (LDAP / local users)
- Use role-based access control (RBAC)
- Store secrets in Jenkins credentials store
- Use HTTPS
- Restrict access to master node

---

## 7. How do you store and use credentials in pipeline?

Store credentials in Jenkins → Credentials Manager  

Use in pipeline:
withCredentials([string(credentialsId: 'token', variable: 'TOKEN')]) {
  sh 'echo $TOKEN'
}

---

## 8. Jenkins server is slow. What will you check?

- CPU and memory usage
- Number of running jobs
- Disk space
- Old builds cleanup
- Plugin performance
- Logs for errors

---

## 9. How do you clean old builds?

Options:
- Configure "Discard Old Builds" in job
- Use log rotation
- Delete workspace periodically

---

## 10. How do you handle build failures automatically?

- Use post block:
post {
  failure {
    mail to: 'team@example.com'
  }
}

- Retry mechanism
- Slack/email notifications

---

## 11. How do you scale Jenkins?

- Use multiple agents
- Use distributed builds
- Use Kubernetes agents (dynamic pods)
- Separate build and deploy workloads

---

## 12. How do you integrate Jenkins with Docker?

Steps:
- Build Docker image in pipeline
- Tag image
- Push to Docker registry

Example:
docker build -t app:latest .
docker push app:latest

---

## 13. How do you deploy to Kubernetes using Jenkins?

Steps:
- Build Docker image
- Push to registry
- Update Kubernetes manifest
- Apply using kubectl

Example:
kubectl apply -f deployment.yaml

---

## 14. How do you handle pipeline failures and retries?

Use retry block:
retry(3) {
  sh 'some command'
}

Also:
- Add timeout
- Use proper error handling

---

## 15. How do you handle parallel jobs?

Use parallel stages:

parallel {
  stage('Test1') { steps { ... } }
  stage('Test2') { steps { ... } }
}

Improves speed of pipeline.

---

## 16. How do you manage configuration in Jenkins?

- Use environment variables
- Use config files (config maps)
- Use parameterized builds

---

## 17. How do you restrict production deployment?

- Add manual approval step
- Restrict access to specific users
- Use branch-based deployment rules

---

## 18. How do you handle secrets securely?

- Never hardcode secrets
- Use Jenkins credentials store
- Use secret injection in pipeline

---

## 19. How do you monitor Jenkins?

- Use logs
- Integrate with monitoring tools (Prometheus, Grafana)
- Set alerts for failures

---

## 20. Explain a real-time pipeline you worked on

Example answer:

"I worked on a pipeline where:
- Code was pushed to Git
- Jenkins triggered automatically via webhook
- Build was done using Maven
- Docker image was created and pushed
- Deployment was done to Kubernetes cluster
- Notifications were sent via Slack"

---

## Bonus Tips

Interviewers expect:
- Real examples
- Problem-solving approach
- Understanding of failures

Focus on:
- Debugging
- Security
- Scalability

---

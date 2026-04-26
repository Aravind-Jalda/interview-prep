# Kubernetes Scenario-Based Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. Pod is not running. What will you check?

- kubectl get pods  
- kubectl describe pod  
- kubectl logs  
- Check image, resources, errors  

---

## 2. Application is not accessible. Why?

- Service not configured  
- Port mismatch  
- Ingress issue  
- Pod not running  

---

## 3. How do you debug a pod?

- Check logs  
- Exec into pod  
- Describe pod  
- Check events  

---

## 4. Pod is restarting continuously. Why?

- CrashLoopBackOff  
- Application failure  
- Resource limits  

---

## 5. How do you scale application?

- kubectl scale  
- Use HPA (Horizontal Pod Autoscaler)  

---

## 6. How do you deploy application in Kubernetes?

- Create deployment YAML  
- Apply using kubectl  
- Expose via service  

---

## 7. How do you update application?

- Update image version  
- Apply deployment  
- Rolling update happens  

---

## 8. How do you rollback deployment?

kubectl rollout undo deployment <name>

---

## 9. How do you check logs?

kubectl logs pod-name

---

## 10. How do you access pod?

kubectl exec -it pod-name -- /bin/bash

---

## 11. How do you expose service externally?

- NodePort  
- LoadBalancer  
- Ingress  

---

## 12. How do you manage secrets?

- Use Kubernetes Secrets  
- Avoid hardcoding  

---

## 13. How do you handle configuration?

- Use ConfigMaps  

---

## 14. How do you monitor Kubernetes?

- kubectl commands  
- Logs  
- Monitoring tools  

---

## 15. How do you troubleshoot networking issue?

- Check service  
- Check endpoints  
- Verify ports  

---

## 16. How do you ensure high availability?

- Multiple replicas  
- Use load balancer  
- Use multiple nodes  

---

## 17. How do you handle resource limits?

- Define CPU/memory limits in YAML  

---

## 18. How do you clean unused resources?

- Delete unused pods  
- Clean old deployments  

---

## 19. How do you connect pods?

- Use services  
- Use DNS  

---

## 20. Explain real-time Kubernetes usage

Example:

"I deployed application using Kubernetes where:
- Docker image was used  
- Deployment managed pods  
- Service exposed application  
- Auto scaling handled load"

---

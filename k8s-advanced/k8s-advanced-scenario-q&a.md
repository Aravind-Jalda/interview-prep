# Kubernetes Advanced Scenario-Based Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. Pod is running but not receiving traffic. Why?

- Readiness probe failing  
- Service misconfigured  
- Port mismatch  

---

## 2. Pod is restarting frequently (CrashLoopBackOff)

- Check logs  
- Check liveness probe  
- Check application errors  

---

## 3. Application is slow in Kubernetes

- Check CPU/memory usage  
- Check HPA  
- Scale pods  

---

## 4. How do you implement auto scaling?

- Configure HPA  
- Set CPU threshold  

---

## 5. How do you expose application externally?

- Use Ingress  
- Use LoadBalancer  

---

## 6. How do you secure Kubernetes cluster?

- Use RBAC  
- Use network policies  
- Restrict access  

---

## 7. How do you manage configuration?

- Use ConfigMaps  
- Use Secrets  

---

## 8. How do you deploy using Helm?

- Create chart  
- Install using helm install  

---

## 9. How do you update application?

- Update image  
- Use rolling update  

---

## 10. How do you rollback deployment?

kubectl rollout undo deployment <name>

---

## 11. How do you debug networking issue?

- Check service  
- Check endpoints  
- Check network policy  

---

## 12. Node is not ready. What will you check?

- Node status  
- Resources  
- Logs  

---

## 13. How do you ensure high availability?

- Use multiple replicas  
- Use multiple nodes  
- Use load balancer  

---

## 14. Pod is pending. Why?

- Insufficient resources  
- Node issue  
- Scheduling constraints  

---

## 15. How do you manage secrets securely?

- Use Kubernetes Secrets  
- Avoid hardcoding  

---

## 16. How do you handle zero downtime deployment?

- Use rolling updates  
- Use readiness probes  

---

## 17. How do you monitor Kubernetes?

- Use Prometheus  
- Use Grafana  
- Check logs  

---

## 18. How do you manage large clusters?

- Use namespaces  
- Use Helm  
- Use automation  

---

## 19. How do you control traffic routing?

- Use Ingress  
- Use service  

---

## 20. Real-time answer (Interview Ready)

Example:

"I deployed application using Kubernetes with HPA for scaling, Ingress for routing, and readiness/liveness probes for stability."

---

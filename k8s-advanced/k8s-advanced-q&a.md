# Kubernetes Advanced Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. What is Horizontal Pod Autoscaler (HPA)?
HPA automatically scales pods based on CPU or memory usage.

---

## 2. What is Vertical Pod Autoscaler (VPA)?
VPA adjusts CPU and memory limits of pods instead of scaling count.

---

## 3. What is Cluster Autoscaler?
Automatically adds or removes nodes based on workload.

---

## 4. What is liveness probe?
Checks if container is alive.  
If it fails, Kubernetes restarts the container.

---

## 5. What is readiness probe?
Checks if container is ready to serve traffic.  
If it fails, traffic is not sent to pod.

---

## 6. Difference between liveness and readiness?

- Liveness → restart container  
- Readiness → stop traffic  

---

## 7. What is Ingress?
Ingress manages external HTTP/HTTPS access to services.

---

## 8. What is Ingress Controller?
Component that implements Ingress rules.  
Example: NGINX Ingress Controller.

---

## 9. What is Helm?
Helm is a package manager for Kubernetes.  
Used to deploy applications using charts.

---

## 10. What is Helm chart?
Collection of YAML files used to deploy applications.

---

## 11. What is RBAC?
Role-Based Access Control used to manage permissions.

---

## 12. What is ServiceAccount?
Provides identity for pods to interact with cluster.

---

## 13. What is Network Policy?
Controls network communication between pods.

---

## 14. What is PodDisruptionBudget?
Ensures minimum number of pods are available during disruptions.

---

## 15. What is StatefulSet vs Deployment?

- Deployment → stateless apps  
- StatefulSet → stateful apps  

---

## 16. What is DaemonSet?
Runs one pod per node.

---

## 17. What is ConfigMap vs Secret?

- ConfigMap → non-sensitive data  
- Secret → sensitive data  

---

## 18. What is resource limit and request?

- Request → minimum required  
- Limit → maximum allowed  

---

## 19. What is node affinity?
Controls which nodes pods can run on.

---

## 20. What is taint and toleration?
Controls which pods can be scheduled on nodes.

---

## Bonus Flow

User → Ingress → Service → Pod

---

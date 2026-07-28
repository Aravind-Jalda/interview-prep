# Kubernetes Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. What is Kubernetes?
Kubernetes (K8s) is a container orchestration tool used to deploy, manage, and scale containerized applications.

---

## 2. What is a Pod?
A Pod is the smallest unit in Kubernetes.  
It contains one or more containers that run together.

---

## 3. What is a Node?
A Node is a machine (VM or physical server) where pods run.

---

## 4. What is a Cluster?
A cluster is a group of nodes managed by Kubernetes.

---

## 5. What is a Deployment?
Deployment is used to manage application pods.  
It ensures desired number of replicas are running.

---

## 6. What is a Service?
A Service exposes pods and allows communication.  
Types:
- ClusterIP  
- NodePort  
- LoadBalancer  

---

## 7. What is a Namespace?
Namespace is used to organize resources in a cluster.

---

## 8. What is ConfigMap?
Used to store configuration data.

---

## 9. What is Secret?
Used to store sensitive data like passwords and tokens.

---

## 10. What is Ingress?
Ingress manages external access to services, usually HTTP/HTTPS.

---

## 11. What is ReplicaSet?
Ensures a specified number of pod replicas are running.

---

## 12. What is Auto Scaling in Kubernetes?
Kubernetes can scale pods automatically based on CPU/memory usage.

---

## 13. What is kubectl?
Command-line tool to interact with Kubernetes cluster.

Example:
kubectl get pods

---

## 14. What is rolling update?
Gradually updates application without downtime.

---

## 15. What is rollback?
Reverts to previous version if deployment fails.

---

## 16. What is Persistent Volume (PV)?
Storage resource in cluster.

---

## 17. What is Persistent Volume Claim (PVC)?
Request for storage by application.

---

## 18. What is DaemonSet?
Runs one pod on each node.

---

## 19. What is StatefulSet?
Used for stateful applications like databases.

---

## 20. How Kubernetes is used in DevOps?

- Deploy containers  
- Manage scaling  
- Ensure high availability  
- Automate deployments  

---

## Bonus Example

Docker → Kubernetes → Scalable deployment

---

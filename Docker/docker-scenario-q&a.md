# Docker Scenario-Based Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. Container is not starting. What will you check?

- Check logs (docker logs)  
- Verify Dockerfile  
- Check command/entrypoint  
- Check port conflicts  

---

## 2. Application inside container is not accessible. Why?

- Port not exposed  
- Port mapping missing  
- Firewall issue  
- Application not running  

---

## 3. How do you debug a running container?

- docker logs  
- docker exec into container  
- Check application logs  

---

## 4. Container stops automatically. Why?

- Main process exited  
- Error in application  
- Check logs  

---

## 5. How do you reduce Docker image size?

- Use lightweight base image (alpine)  
- Remove unnecessary files  
- Use multi-stage build  

---

## 6. How do you persist data in Docker?

- Use volumes  
- Avoid storing data inside container  

---

## 7. How do you connect containers?

- Use Docker network  
- Use docker-compose  

---

## 8. How do you deploy app using Docker?

Steps:
- Write Dockerfile  
- Build image  
- Push to registry  
- Run container  

---

## 9. How do you push image to Docker Hub?

- docker login  
- docker tag  
- docker push  

---

## 10. How do you handle multiple containers?

- Use docker-compose  
- Define services in YAML  

---

## 11. Container is using high CPU. What will you check?

- Check processes inside container  
- Optimize application  
- Limit resources  

---

## 12. How do you restart container automatically?

Use:
--restart always

---

## 13. How do you update running container?

- Pull new image  
- Stop old container  
- Start new container  

---

## 14. How do you clean unused Docker resources?

docker system prune

---

## 15. How do you handle secrets in Docker?

- Use environment variables  
- Use secret management tools  
- Avoid hardcoding  

---

## 16. How do you monitor containers?

- docker stats  
- Logs  
- External tools  

---

## 17. How do you scale containers?

- Run multiple containers  
- Use load balancer  
- Use Kubernetes  

---

## 18. Difference between VM and container?

- VM → full OS  
- Container → lightweight, shares OS  

---

## 19. How do you debug network issue in Docker?

- Check network  
- Check ports  
- Test connectivity  

---

## 20. Explain real-time Docker usage

Example:

"I used Docker to containerize application, pushed image to registry, and deployed via Jenkins pipeline."

---

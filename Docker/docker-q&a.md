# Docker Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. What is Docker?
Docker is a containerization platform used to package applications and their dependencies into containers.  
Containers ensure the application runs the same in any environment.

---

## 2. What is a container?
A container is a lightweight, isolated environment where an application runs.  
It shares the host OS kernel but runs independently.

---

## 3. What is a Docker image?
An image is a template used to create containers.  
It contains application code, libraries, and dependencies.

---

## 4. What is a Dockerfile?
A Dockerfile is a script that contains instructions to build a Docker image.

Example:
FROM ubuntu
RUN apt-get update

---

## 5. What is the difference between image and container?
- Image → blueprint  
- Container → running instance of image  

---

## 6. What is Docker Hub?
Docker Hub is a public registry where Docker images are stored and shared.

---

## 7. What is docker build?
Used to create an image from Dockerfile.

Example:
docker build -t myapp .

---

## 8. What is docker run?
Used to create and start a container.

Example:
docker run -d -p 80:80 nginx

---

## 9. What is docker ps?
Lists running containers.

---

## 10. What is docker stop?
Stops a running container.

---

## 11. What is docker rm?
Removes a container.

---

## 12. What is docker rmi?
Removes an image.

---

## 13. What is port mapping?
Maps container port to host port.

Example:
-p 8080:80

---

## 14. What is volume in Docker?
Volume is used to persist data outside container.

---

## 15. What is bind mount?
Maps a host directory to container.

---

## 16. What is docker-compose?
Tool to define and run multi-container applications using YAML file.

---

## 17. What is a network in Docker?
Allows containers to communicate with each other.

---

## 18. What is docker logs?
Used to view container logs.

---

## 19. What is docker exec?
Used to run command inside running container.

Example:
docker exec -it container bash

---

## 20. How Docker is used in DevOps?

- Build application images  
- Run containers  
- Integrate with CI/CD pipelines  
- Deploy to Kubernetes  

---

## Bonus Example

docker build → docker push → deploy

---

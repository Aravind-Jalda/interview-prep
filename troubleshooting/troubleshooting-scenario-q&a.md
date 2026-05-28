# Real-Time Troubleshooting Scenarios (DevOps - 2 to 5 Years)

---

## 1. Application is not accessible (Most Common Question)

Steps:
- Check DNS  
- Check load balancer  
- Check server status  
- Check application logs  
- Check firewall  

---

## 2. Unable to SSH into server

- Check instance status  
- Verify port 22  
- Check security group  
- Check key and username  

---

## 3. High CPU usage on server

- Run top  
- Identify process  
- Restart service if needed  
- Scale system  

---

## 4. Disk is full

- Check df -h  
- Find large files (du -sh)  
- Clean logs  
- Extend disk  

---

## 5. Docker container is not running

- docker ps -a  
- docker logs  
- Check entrypoint  
- Fix issue and restart  

---

## 6. Kubernetes pod is in CrashLoopBackOff

- kubectl logs  
- kubectl describe pod  
- Check application error  
- Fix and redeploy  

---

## 7. Service is not reachable in Kubernetes

- Check pod status  
- Check service  
- Check endpoints  
- Verify ports  

---

## 8. Jenkins pipeline failed

- Check build logs  
- Identify failed stage  
- Fix script/config  
- Re-run pipeline  

---

## 9. API is slow

- Check server load  
- Check database  
- Analyze logs  
- Scale resources  

---

## 10. Database connection issue

- Check DB status  
- Check connection string  
- Check network  
- Verify credentials  

---

## 11. Prometheus metrics not showing

- Check target  
- Check exporter  
- Check scrape config  

---

## 12. Grafana dashboard empty

- Check data source  
- Check query  
- Check time range  

---

## 13. Deployment failed in Kubernetes

- Check rollout status  
- Check logs  
- Check YAML config  

---

## 14. Website works locally but not in production

- Check environment variables  
- Check networking  
- Check configuration  

---

## 15. SSL/HTTPS not working

- Check certificate  
- Check port 443  
- Check load balancer  

---

## 16. Load balancer not routing traffic

- Check target health  
- Check listener rules  
- Check backend servers  

---

## 17. Terraform apply failed

- Check error  
- Fix config  
- Run plan again  

---

## 18. Ansible playbook failed

- Check syntax  
- Check logs  
- Verify connectivity  

---

## 19. Logs are not generated

- Check logging config  
- Check permissions  
- Restart service  

---

## 20. Real-time answer (Interview Ready)

Example:

"When application was not accessible, I checked DNS, load balancer, server, and logs.  
Found port was blocked in security group, fixed it, and issue was resolved."

---

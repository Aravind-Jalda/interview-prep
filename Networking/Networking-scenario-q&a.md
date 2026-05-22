# Networking Scenario-Based Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. Server is not reachable. What will you check?

- Check if server is running  
- Ping the server  
- Check firewall rules  
- Verify security group/NSG  
- Check network connectivity  

---

## 2. Website is not opening. What will you do?

- Check DNS resolution  
- Ping domain  
- Check server status  
- Verify ports (80/443)  
- Check load balancer  

---

## 3. Unable to SSH into server. What will you check?

- Port 22 open  
- Security group rules  
- Correct key and username  
- Server running  

---

## 4. How do you check open ports on a server?

Use:
netstat -tulnp
or
ss -tulnp

---

## 5. Application is slow. What will you check?

- Network latency  
- Server load  
- Bandwidth usage  
- Logs  

---

## 6. DNS is not resolving. What will you do?

- Check DNS configuration  
- Use nslookup/dig  
- Verify domain settings  

---

## 7. How do you troubleshoot connectivity issue?

- Ping  
- Traceroute  
- Check firewall  
- Check routing  

---

## 8. How do you allow access to application?

- Open required port in firewall  
- Update security group  
- Restart service if needed  

---

## 9. How do you restrict access to server?

- Close unused ports  
- Use firewall rules  
- Allow only specific IPs  

---

## 10. What will you do if port is blocked?

- Check firewall  
- Update rules  
- Restart service  

---

## 11. How do you check if service is running on port?

Use:
netstat or ss  
or
curl localhost:port  

---

## 12. How do you debug API issue?

- Use curl  
- Check response code  
- Verify logs  

---

## 13. How do you connect private network to internet?

- Use NAT gateway  
- Configure routing  

---

## 14. How do you handle traffic spike?

- Use load balancer  
- Scale servers  
- Optimize network  

---

## 15. How do you secure network?

- Use firewall  
- Use HTTPS  
- Restrict access  

---

## 16. How do you check internet connectivity?

ping google.com

---

## 17. What will you do if high latency?

- Check network path  
- Optimize routing  
- Use CDN  

---

## 18. How do you monitor network?

- Use monitoring tools  
- Check logs  
- Track metrics  

---

## 19. How do you troubleshoot load balancer issue?

- Check backend servers  
- Check health checks  
- Verify routing  

---

## 20. Explain real-time networking issue

Example:

"Application was not reachable due to blocked port in security group.  
After opening port, issue was resolved."

---

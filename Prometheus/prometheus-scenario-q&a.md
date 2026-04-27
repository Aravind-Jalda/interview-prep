# Prometheus Scenario-Based Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. Metrics are not showing in Prometheus. What will you check?

- Target status in Prometheus UI  
- Check scrape configuration  
- Verify exporter is running  
- Check network connectivity  

---

## 2. How do you debug a target down issue?

- Check if service is running  
- Check endpoint URL  
- Verify firewall  
- Check logs  

---

## 3. Alerts are not firing. Why?

- Check alert rules  
- Check Alertmanager configuration  
- Verify thresholds  
- Check logs  

---

## 4. High CPU usage detected. What will you do?

- Check metrics in Prometheus  
- Identify process  
- Scale system  
- Optimize application  

---

## 5. How do you monitor servers using Prometheus?

- Install Node Exporter  
- Configure Prometheus  
- Add target  
- Visualize in Grafana  

---

## 6. How do you monitor application metrics?

- Add instrumentation in app  
- Expose metrics endpoint  
- Configure Prometheus  

---

## 7. How do you create alert?

- Define alert rule  
- Set condition  
- Configure Alertmanager  

---

## 8. How do you reduce Prometheus storage usage?

- Reduce retention time  
- Optimize scrape interval  
- Remove unused metrics  

---

## 9. How do you scale Prometheus?

- Use federation  
- Use remote storage  
- Split workloads  

---

## 10. How do you monitor Kubernetes?

- Use kube-state-metrics  
- Use node exporter  
- Configure Prometheus  

---

## 11. How do you check targets in Prometheus?

Open:
http://localhost:9090/targets

---

## 12. How do you query metrics?

Use PromQL:

rate(cpu_usage[5m])

---

## 13. How do you troubleshoot missing metrics?

- Check exporter  
- Check scrape config  
- Check labels  

---

## 14. How do you monitor API performance?

- Track request count  
- Track latency  
- Set alerts  

---

## 15. How do you integrate Prometheus with Grafana?

- Add Prometheus as data source  
- Create dashboards  

---

## 16. How do you handle alert noise?

- Tune thresholds  
- Use alert grouping  
- Reduce duplicate alerts  

---

## 17. How do you secure Prometheus?

- Use authentication  
- Restrict access  
- Use HTTPS  

---

## 18. How do you monitor logs vs metrics?

- Prometheus → metrics  
- Use other tools for logs  

---

## 19. What will you do if Prometheus is slow?

- Reduce data  
- Optimize queries  
- Increase resources  

---

## 20. Explain real-time monitoring setup

Example:

"I used Prometheus with Node Exporter to collect system metrics,  
Alertmanager to send alerts, and Grafana for dashboards."

---

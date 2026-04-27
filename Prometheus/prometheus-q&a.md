# Prometheus Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. What is Prometheus?
Prometheus is an open-source monitoring and alerting tool.  
It collects metrics from systems and stores them as time-series data.

---

## 2. What is a metric?
A metric is a numerical value that represents system performance.  
Example:
- CPU usage  
- Memory usage  
- Request count  

---

## 3. What is a time-series database?
It stores data along with timestamps.  
Prometheus stores metrics with time information.

---

## 4. What is scraping?
Prometheus collects metrics by pulling data from targets at regular intervals.  
This process is called scraping.

---

## 5. What is a target?
A target is a system or service from which Prometheus collects metrics.  
Example: server, application, container.

---

## 6. What is an exporter?
Exporter is a tool that exposes metrics in Prometheus format.  
Example:
- Node Exporter (for system metrics)

---

## 7. What is PromQL?
PromQL is the query language used in Prometheus to retrieve and analyze metrics.

Example:
rate(http_requests_total[5m])

---

## 8. What is Alertmanager?
Alertmanager handles alerts sent by Prometheus.  
It sends notifications via email, Slack, etc.

---

## 9. What is a scrape interval?
It defines how frequently Prometheus collects metrics.

---

## 10. What is a job in Prometheus?
A job is a group of targets with similar configuration.

---

## 11. What is a label?
Labels are key-value pairs used to identify metrics.

Example:
method="GET"

---

## 12. What is Grafana?
Grafana is a visualization tool used with Prometheus to create dashboards.

---

## 13. Difference between pull and push model?
- Prometheus uses pull (scraping)  
- Push is used in tools like Pushgateway  

---

## 14. What is Pushgateway?
Used to push metrics for short-lived jobs.

---

## 15. What is retention in Prometheus?
Defines how long metrics are stored.

---

## 16. What is service discovery?
Automatically finds targets to monitor.

---

## 17. What is node exporter?
Collects system-level metrics like CPU, memory, disk.

---

## 18. What is blackbox exporter?
Used to monitor endpoints (HTTP, ping, etc.)

---

## 19. How Prometheus is used in DevOps?

- Monitor servers  
- Monitor applications  
- Alert on issues  
- Integrate with Grafana  

---

## 20. Example flow

Prometheus → collects metrics → Alertmanager → sends alerts → Grafana → visualizes data

---

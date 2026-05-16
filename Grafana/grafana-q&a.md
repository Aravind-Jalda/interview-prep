# Grafana Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. What is Grafana?
Grafana is an open-source visualization tool used to create dashboards for monitoring data.  
It is commonly used with Prometheus to visualize metrics.

---

## 2. What is a dashboard?
A dashboard is a collection of panels that display metrics in graphs, tables, or charts.

---

## 3. What is a panel?
A panel is a single visualization unit in a dashboard.  
Example: CPU usage graph.

---

## 4. What is a data source?
A data source is where Grafana fetches data from.  
Examples:
- Prometheus  
- MySQL  
- Elasticsearch  

---

## 5. How Grafana works with Prometheus?
Grafana queries Prometheus using PromQL and displays results as dashboards.

---

## 6. What is a query in Grafana?
A query retrieves data from the data source.

Example:
rate(cpu_usage[5m])

---

## 7. What is a variable in Grafana?
Variables allow dynamic filtering in dashboards.  
Example: select server name from dropdown.

---

## 8. What is alerting in Grafana?
Grafana can send alerts based on conditions.  
Example: CPU > 80%

---

## 9. What is a threshold?
Threshold defines limit values for alerts or visualization.

---

## 10. What is a time range?
Time range defines the duration of data shown (last 5 min, 1 hour, etc.)

---

## 11. What is a dashboard refresh?
It defines how often the dashboard updates data.

---

## 12. What is a template?
Templates use variables to make dashboards reusable.

---

## 13. What is Grafana Explore?
Explore is used for ad-hoc querying and debugging metrics.

---

## 14. What is annotation?
Annotations mark important events on graphs (deployments, failures).

---

## 15. What is alert notification?
Grafana sends alerts via:
- Email  
- Slack  
- Webhooks  

---

## 16. What is provisioning in Grafana?
Automating dashboards and data sources using configuration files.

---

## 17. What is role-based access in Grafana?
Controls who can view or edit dashboards.

---

## 18. What is Loki?
Loki is a log aggregation system used with Grafana for log monitoring.

---

## 19. How Grafana is used in DevOps?

- Visualize metrics  
- Monitor systems  
- Create alerts  
- Debug issues  

---

## 20. Example usage

Prometheus → Grafana dashboards → Alerts → Notifications

---

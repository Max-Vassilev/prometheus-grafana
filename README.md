# Website Monitoring with Prometheus and Grafana

This repository is used to monitor a frontend website hosted on an AWS S3 bucket.

- **Prometheus**: Used to scrape and store metrics, including uptime and response time.
- **Grafana**: Visualizes the metrics with dashboards, showing status and latency.
- **Blackbox Exporter**: Probes the website endpoints, feeding uptime and latency metrics into Prometheus.

This stack ensures end-to-end monitoring of the S3-hosted site.

# Gallery:

## Prometheus

**Targets**
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/669608f9-f13c-4c00-a9b9-e31946e43a75" />

## Grafana

**Creating a custom dashboard for Blackbox Exporter**  
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/347e2afd-a7f3-443f-b5df-e104aec5d48b" />

**Dashboard visualization**
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/1adf5939-37c8-4ed6-9f6f-3dea6dbc59d9" />

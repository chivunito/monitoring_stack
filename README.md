# Monitoring stack with docker
inspired from [this tuto](https://finestructure.co/blog/2016/5/16/monitoring-with-prometheus-grafana-docker-part-1)  
This project bootstraps a monitoring stack containing :
- Prometheus server as monitoring and time serie database
- Alertmanager for handling alerts 
- Grafana for visualization
- Node-exporter for generating target metrics

## Installation
```bash
docker-compose up -d
```

## Authors
* **Thibaut Sarion** 
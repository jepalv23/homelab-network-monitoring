# homelab-network-monitoring
A simulated homelab deployment documenting network monitoring using Docker, Prometheus, Grafana, and Uptime Kuma.


# Homelab Network Monitoring

A small-scale network monitoring environment built to explore
infrastructure monitoring, containerization, and Linux server
administration.

## Overview

This project demonstrates a simulated homelab monitoring
environment using Docker Compose, Prometheus, Grafana, and
Uptime Kuma.

The goal is to centralize infrastructure metrics and provide
visibility into service availability.

## Infrastructure

| Component | Description |
|---|---|
| Host OS | Ubuntu Server 22.04 |
| Container Runtime | Docker |
| Orchestration | Docker Compose |
| Metrics Collection | Prometheus |
| Visualization | Grafana |
| Availability Monitoring | Uptime Kuma |

## Network Configuration

Example lab addressing:

| Device | IP Address |
|---|---|
| Gateway | 192.168.1.1 |
| Homelab Host | 192.168.1.100 |
| Monitoring Services | Docker network |
| Test Client | 192.168.1.120 |

All addresses are example values for this simulated lab.

## Services

### Prometheus
Collects and stores infrastructure metrics.

### Grafana
Provides dashboards for visualizing collected metrics.

### Uptime Kuma
Monitors service availability and response status.

## Deployment

Clone the repository:

```bash
git clone https://github.com/USERNAME/homelab-network-monitoring.git

cd homelab-network-monitoring
```

Start the environment:

```bash
docker compose up -d
```

Check running containers:

```bash
docker ps
```

View container logs:

```bash
docker compose logs -f
```

## Security Considerations

- Restrict access to monitoring dashboards.
- Avoid exposing management ports publicly.
- Use strong credentials.
- Keep containers and host packages updated.
- Store secrets outside version control.

## Learning Objectives

- Docker container management
- Linux server administration
- Network monitoring
- Metrics collection
- Infrastructure troubleshooting
- Service availability monitoring

## Project Status

Documentation and example configurations are
provided for educational purposes.

Deployment and operational testing should be
completed before marking this environment as
fully operational.

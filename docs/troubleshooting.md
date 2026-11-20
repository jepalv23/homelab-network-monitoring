
# Troubleshooting Notes

## Issue 1: Container Not Starting

Check container status:

```bash
docker ps -a
```

Inspect container logs:

```bash
docker logs prometheus
```

## Issue 2: Prometheus Target Unavailable

Verify Prometheus configuration.

Check target status through:

http://localhost:9090/targets

## Issue 3: Grafana Dashboard Unavailable

Check whether the container is running:

```bash
docker ps | grep grafana
```

Inspect logs:

```bash
docker logs grafana
```

## Maintenance Commands

Check disk usage:

```bash
df -h
```

Check memory:

```bash
free -m
```

Check network interfaces:

```bash
ip addr
```

Check listening ports:

```bash
ss -tulpn
```

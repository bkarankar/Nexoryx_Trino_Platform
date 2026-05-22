# Nexoryx_Trino_Platform

Production-ready Trino analytics platform for Kubernetes with:

- Trino
- PostgreSQL
- Hive Metastore
- MinIO Object Storage
- Spark Integration
- NGINX Ingress
- Autoscaling
- Persistent Storage
- Monitoring-ready architecture

## Features

- Distributed SQL query engine
- Hive Metastore integration
- Object storage support
- Spark interoperability
- Kubernetes-native deployment
- Horizontal scaling
- Persistent storage
- Resource limits
- Health probes
- Ingress routing
- Production-ready manifests

## Stack

- Kubernetes
- Trino
- PostgreSQL
- Hive Metastore
- MinIO
- Spark
- NGINX Ingress
- Prometheus
- Grafana

## Deployment

```bash
kubectl apply -f kubernetes/
```

## Namespace

```bash
nexoryx-trino
```

## Components

- Trino Coordinator
- Trino Workers
- PostgreSQL
- Hive Metastore
- MinIO
- Ingress
- Autoscaling

## Notes

Update passwords, storage classes, and ingress domains before production deployment.

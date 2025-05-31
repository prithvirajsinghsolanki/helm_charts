# Base Application Helm Chart

This is a **base Helm chart** designed to deploy containerized applications using either a **Deployment** or a **StatefulSet** on Kubernetes. It includes support for ConfigMaps, Secrets, persistent volumes, probes, RBAC, service accounts, and more.

---

## 🚀 Features

- Supports both `Deployment` and `StatefulSet` types
- Multi-volume persistent storage via `volumeClaimTemplates`
- Configurable environment variables (plain, ConfigMap, or Secret)
- HTTP readiness and liveness probes
- Resource requests and limits
- Secret mounting as volumes
- RBAC and ServiceAccount support
- Works with NodePort, ClusterIP, and LoadBalancer

---

## 🔧 Installation

```bash
helm install <release-name> ./your-chart-folder


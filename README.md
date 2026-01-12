<div align="center">

# Josiah Boman

### Technical Program Manager | Systems Engineer | Platform Engineering

*Building scalable infrastructure and leading technical programs since 2016*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/josiahboman/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@josiahboman.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JosiahBoman)

</div>

---

## About Me

I'm a **Technical Program Manager (TPgM)** and **Systems Engineer** with expertise in **platform engineering**. With nearly a decade of experience, I specialize in designing, implementing, and managing complex infrastructure systems. My passion lies at the intersection of technical excellence and strategic program delivery.

---

## Technical Skills

<div align="center">

### Infrastructure & Orchestration
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![etcd](https://img.shields.io/badge/etcd-419EDA?style=flat-square&logo=etcd&logoColor=white)

### Networking & Storage
![Flannel](https://img.shields.io/badge/Flannel_CNI-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![MetalLB](https://img.shields.io/badge/MetalLB-FF6600?style=flat-square&logo=kubernetes&logoColor=white)
![NFS](https://img.shields.io/badge/NFS-0078D4?style=flat-square&logo=files&logoColor=white)
![Longhorn](https://img.shields.io/badge/Longhorn-5F259F?style=flat-square&logo=rancher&logoColor=white)

### Monitoring & Observability
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Alertmanager](https://img.shields.io/badge/Alertmanager-E6522C?style=flat-square&logo=prometheus&logoColor=white)

### Hardware & Systems
![Intel](https://img.shields.io/badge/Intel-0071C5?style=flat-square&logo=intel&logoColor=white)
![TrueNAS](https://img.shields.io/badge/TrueNAS-0095D5?style=flat-square&logo=truenas&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)

</div>

---

## Homelab Infrastructure

> *Production-grade Kubernetes cluster running on 3x ASUS NUC 155h*

### Cluster Architecture

| Component | Configuration |
|-----------|---------------|
| **Control Plane** | 3-node HA with Kubernetes v1.35.0 |
| **etcd** | Stacked cluster with 3 voting members |
| **VIP Failover** | kube-vip for high availability |
| **CNI** | Flannel for pod networking |
| **Load Balancer** | MetalLB with L2 advertisement |

### Storage Stack

```
                    ┌─────────────────────────────────────┐
                    │           TrueNAS Server            │
                    │  ┌─────────────┬─────────────────┐  │
                    │  │   Movies    │    TV Shows     │  │
                    │  │   (NFS)     │     (NFS)       │  │
                    │  └──────┬──────┴────────┬────────┘  │
                    │         │               │           │
                    │    Longhorn Backups     │           │
                    └─────────┼───────────────┼───────────┘
                              │               │
        ┌─────────────────────┼───────────────┼─────────────────────┐
        │                     │   Kubernetes  │                     │
        │  ┌──────────────────┴───────────────┴──────────────────┐  │
        │  │              Longhorn (3-replica)                   │  │
        │  │           50GB HA Distributed Storage               │  │
        │  └─────────────────────────────────────────────────────┘  │
        └───────────────────────────────────────────────────────────┘
```

### GPU & Media Services

| Feature | Status |
|---------|--------|
| Intel GPU Plugin | Deployed on all 3 nodes |
| Hardware Transcoding | Intel Quick Sync (i915) |
| Plex Media Server | Running with GPU passthrough |
| Media Storage | NFS mounts (read-only for protection) |

### Monitoring Stack

| Tool | Purpose |
|------|---------|
| **Kubernetes Dashboard** | Cluster management with admin access |
| **Prometheus** | Metrics collection and querying |
| **Grafana** | Pre-configured K8s dashboards |
| **Alertmanager** | Alerting and notifications |

### Network & Security

- **Tailscale** - Secure mesh VPN with proper RBAC
- **MetalLB** - LoadBalancer services for local network
- **Storage VLAN** - Isolated NFS traffic
- **ServiceAccount Roles** - Principle of least privilege

---

<div align="center">

### Let's Connect

*Open to discussions about Kubernetes, platform engineering, and infrastructure architecture*

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/josiahboman/)

</div>

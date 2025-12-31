Hello! I'm Josiah 👋

I have been working as a Technical Program Manager (TPgM) and Systems Engineer (SysEng) since 2016 specializing in platform engineering.

[![linkedinicon](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/josiahboman/)
[![gmailicon](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@josiahboman.com)

---

My homelab k8s stack:

**Infrastructure (3x ASUS NUC 155h)**

✅ 3-node HA control plane running Kubernetes v1.35.0
✅ Stacked etcd cluster with 3 voting members for high availability
✅ kube-vip providing VIP failover
✅ Flannel CNI for pod networking (fixed br_netfilter issues on all nodes)
✅ Control plane taints removed - nodes can run workloads
✅ Swap disabled on all nodes for Kubernetes compatibility

**Networking & Load Balancing**

✅ MetalLB installed and configured
✅ L2 advertisement for LoadBalancer services
✅ NFS client installed on all nodes for storage access Distributed Storage
✅ Longhorn deployed with 3-replica redundancy across nodes
✅ 50GB default replica count for high availability
✅ NFS backup target configured to TrueNAS (:/mnt/tank0/kubernetes/longhorn-backups)
✅ Longhorn UI accessible
✅ Backup/restore functionality tested and working

**GPU Support**

✅ Intel GPU device plugin installed on all 3 nodes
✅ Hardware transcoding ready (gpu.intel.com/i915 available on all nodes)

**Monitoring & Management StackDashboards & Observability**

✅ Kubernetes Dashboard
✅ Admin user created with cluster-admin access
✅ Bearer token authentication configured
✅ Prometheus Metrics collection and querying
✅ Grafana
✅ Pre-configured Kubernetes dashboards
✅ Connected to Prometheus data source
✅ Alertmanager configured

**Plex Media Server Deployment**

✅ Plex running in the media namespace
✅ Local access & Tailscale access
✅ Intel Quick Sync GPU passthrough for hardware transcoding
✅ 50GB Longhorn PVC for config/metadata (replicated across nodes)

**Media Storage**

✅ NFS volumes mounted from TrueNAS (Movies: /mnt → /movies, TV Shows: /mnt → /television)
✅ Read-only mounts for media protection
✅ NFS exports configured correctly on TrueNAS

**Security & Access**

✅ Tailscale sidecar configured with proper RBAC
✅ ServiceAccount and Role created for Tailscale permissions
✅ Connected to Tailscale (visible in admin console)
✅ MetalLB LoadBalancer for local network access

**Storage Infrastructure **

✅ TrueNAS Integration
✅ NFS shares configured on storage VLAN
✅ Dataset structure organized
✅ Proper NFS permissions
✅ Network access from Kubernetes nodes










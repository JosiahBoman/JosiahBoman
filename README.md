<div align="center">

# Josiah Boman

### Technical Program Manager & Systems Engineer

**Google | Distributed Systems | 10+ Years Experience**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/josiahboman/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact@josiahboman.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JosiahBoman)

</div>

---

## About Me

Technical Program Manager and Systems Engineer with **10+ years** leading cross-functional teams to deliver end-to-end full stack software development projects. I've engaged a diverse spectrum of clients including **Fortune 500 companies**, **Venture Capital-backed startups**, the **U.S. Congress**, the **Central Intelligence Agency**, and the **Intelligence Community**.

Currently driving technical programs at **Google Public Sector**, bringing together my expertise in distributed systems, cloud architecture, and program management.

---

## Professional Experience

| Role | Organization | Duration |
|------|--------------|----------|
| **Technical Program Manager** | Google | 2024 - Present |
| **Lead Software & Systems Engineer** | Booz Allen Hamilton | 2024 |
| **Collection Management Officer** | Central Intelligence Agency | 2022 - 2024 |
| **Senior Technical Project Manager** | Altria | 2021 - 2022 |
| **Legislative Staff** | U.S. House of Representatives | 2016 - 2021 |
| **Software & Systems Engineer** | Stealth Startup | 2014 - 2019 |

---

## Education

| Degree | Institution |
|--------|-------------|
| **M.S. Systems Engineering** | Johns Hopkins Whiting School of Engineering |
| **B.A. Interdisciplinary Studies** | University of Missouri-Columbia |
| **Certificate, Multicultural Studies** | University of Missouri-Columbia |

---

## Certifications

<div align="center">

### Cloud & Kubernetes
![GCP](https://img.shields.io/badge/Google_Cloud_Professional_Architect-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![KCSA](https://img.shields.io/badge/KCSA-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![KCNA](https://img.shields.io/badge/KCNA-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

### Project & Program Management
![PMP](https://img.shields.io/badge/PMP-4A154B?style=flat-square&logo=pmi&logoColor=white)
![PMI-ACP](https://img.shields.io/badge/PMI--ACP-4A154B?style=flat-square&logo=pmi&logoColor=white)
![SAFe](https://img.shields.io/badge/SAFe_6_Agilist-FF6B00?style=flat-square&logo=scaled-agile&logoColor=white)
![PSM](https://img.shields.io/badge/PSM_I-009FDA?style=flat-square&logo=scrumalliance&logoColor=white)

### Systems Engineering & Security
![ASEP](https://img.shields.io/badge/ASEP-0066CC?style=flat-square&logo=incose&logoColor=white)
![Security+](https://img.shields.io/badge/Security+-C8202F?style=flat-square&logo=comptia&logoColor=white)
![ITF+](https://img.shields.io/badge/ITF+-C8202F?style=flat-square&logo=comptia&logoColor=white)

</div>

<details>
<summary><b>View All Certifications</b></summary>

| Certification | Issuer | Status |
|--------------|--------|--------|
| Google Cloud Professional Cloud Architect | Google | Active |
| KCSA: Kubernetes and Cloud Native Security Associate | Linux Foundation | Active |
| KCNA: Kubernetes and Cloud Native Associate | Linux Foundation | Active |
| Project Management Professional (PMP) | PMI | Active |
| PMI Agile Certified Practitioner (PMI-ACP) | PMI | Active |
| Associate Systems Engineering Professional (ASEP) | INCOSE | Active |
| Certified SAFe 6 Agilist | Scaled Agile | Active |
| Professional Scrum Master (PSM I) | Scrum.org | Active |
| CompTIA Security+ | CompTIA | Active |
| CompTIA IT Fundamentals (ITF+) | CompTIA | Active |

</details>

---

## Technical Skills

<div align="center">

### Infrastructure & Orchestration
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

### Networking & Storage
![Flannel](https://img.shields.io/badge/Flannel_CNI-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![MetalLB](https://img.shields.io/badge/MetalLB-FF6600?style=flat-square&logo=kubernetes&logoColor=white)
![Longhorn](https://img.shields.io/badge/Longhorn-5F259F?style=flat-square&logo=rancher&logoColor=white)
![TrueNAS](https://img.shields.io/badge/TrueNAS-0095D5?style=flat-square&logo=truenas&logoColor=white)

### Monitoring & Observability
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Alertmanager](https://img.shields.io/badge/Alertmanager-E6522C?style=flat-square&logo=prometheus&logoColor=white)

</div>

---

## Professional Organizations

- **Institute of Electrical and Electronics Engineers (IEEE)** - Member
- **INCOSE - Washington Metro Area Chapter** - Member
  - Agile Systems & Systems Engineering | Architecture | AI Systems | Defense Systems | PM-SE Integration
- **Project Management Institute (PMI) - Washington, DC Chapter** - Member
- **Congressional Tech Staff Association** - Member

---

## Volunteer Experience

| Role | Organization | Focus |
|------|--------------|-------|
| Cloud Architect | Missouri State Society | Education |
| Volunteer | PMI Washington DC Chapter | Science & Technology |
| Visitor's Office Volunteer | White House | Education |

---

## Homelab Infrastructure

> *Production-grade Kubernetes cluster running on 3x ASUS NUC 155h*

<details>
<summary><b>View Homelab Details</b></summary>

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

### Monitoring Stack

| Tool | Purpose |
|------|---------|
| **Kubernetes Dashboard** | Cluster management |
| **Prometheus** | Metrics collection |
| **Grafana** | Visualization dashboards |
| **Alertmanager** | Alerting & notifications |

### Security

- **Tailscale** - Secure mesh VPN with RBAC
- **Storage VLAN** - Isolated NFS traffic
- **ServiceAccount Roles** - Principle of least privilege

</details>

---

<div align="center">

### Let's Connect

*Open to discussions about distributed systems, platform engineering, and cloud architecture*

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/josiahboman/)

</div>

Hey, I'm Godwin 👋


DevOps / Platform Engineer & Data Engineer with 5+ years of experience building production infrastructure, deploying and managing containerised applications, and architecting scalable data platforms.

I work across the full stack of modern infrastructure, from provisioning bare metal Linux servers and cloud environments, to containerising and deploying applications on Kubernetes, to building data pipelines and analytics warehouses that drive business decisions.

Currently building self-hosted infrastructure in my homelab and and writing about it on [Substack](https://geewynn.substack.com).

---
 
### What I work with
 
**Linux & Servers:** Ubuntu · Bare Metal · PXE Boot · Server Provisioning · EC2 · ECS · Azure VMs

**Containerisation:** Docker · Kubernetes (k3s, EKS, GKE, AKS) · Helm · Container Registries · Multi-stage Builds
 
**Networking & Ingress:** Cilium (eBPF) · Traefik · kube-vip · ExternalDNS · Cloudflare Tunnel · cert-manager · Load Balancing · DNS Management
 
**Infrastructure as Code:** Terraform · Ansible
 
**GitOps & CI/CD:** ArgoCD · Flux CD · GitHub Actions · GitLab CI/CD · Kustomize
 
**App Deployment & Databases:** CloudNativePG (PostgreSQL) · MySQL · ClickHouse · Kafka (Strimzi) · Longhorn (Distributed Storage) · n8n · Serverless Pipelines
 
**Observability & Monitoring:** Prometheus · Grafana · Loki · Hubble · AlertManager · Node Exporter · AWS CloudWatch · GCP Monitoring
 
**Security:** DevSecOps · Secrets Management (Azure Key Vault) · Zero-Trust Networking · Cloudflare Tunnel
 
**Data Platforms & Warehousing:** BigQuery · Snowflake · ClickHouse · DBT · CDC (Change Data Capture) · Google Cloud Datastream
 
**Data Orchestration & Streaming:** Kafka · Dagster · Airflow · Apache Beam · Kubeflow
 
**Cloud Platforms:** AWS · GCP · Azure
 
**Languages:** Python · SQL · Bash · YAML · HCL
 
---


### Featured Projects
 
#### [Kubernetes Homelab](https://github.com/geewynn/homelab)
3-node HA Kubernetes cluster on bare metal Linux servers — fully automated from PXE boot to running containerised services using Ansible and Terraform. Deployed CloudNativePG for PostgreSQL, configured Cilium CNI with eBPF as kube-proxy replacement, kube-vip for control plane failover, Traefik for L7 ingress routing, Longhorn for distributed storage, and ArgoCD ApplicationSets for GitOps-driven app delivery. Full observability with Prometheus, Grafana, Loki, and Hubble. Secured external access via Cloudflare Tunnel with zero open ports.
 
#### [K8s Platform Infra](https://github.com/geewynn/k8s-platform-infra)
Production-grade Kafka (Strimzi) and ClickHouse (Altinity) deployment on a self-hosted 3-node HA Kubernetes cluster. Containerised workloads managed with Terraform and ArgoCD, monitored with Prometheus, Grafana, and AlertManager. [Read the blog post →](https://substack.com/@geewynn/p-182902116)
 
#### [n8n Multi-Tenant Platform](https://github.com/geewynn/azure-k8s-deplyment) · [GitOps Config](https://github.com/geewynn/n8n-gitops)
End-to-end containerised application deployment on Azure AKS. Infrastructure provisioned with Terraform, multi-tenant n8n workflow platform deployed via Flux CD with Kustomize overlays per environment, Traefik ingress with cert-manager TLS, CloudNativePG databases, and Azure Key Vault for secrets management.
 

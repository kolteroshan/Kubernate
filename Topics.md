🧠 0. Foundations (Pre-Kubernetes)

    🌱 Needed before starting KCNA / CKA / CKAD

        * 0.1 What is Linux, CLI basics (cd, ls, grep, etc.)
        * 0.2 What is a virtual machine vs container.
        * 0.3 Docker basics: Images, Containers, Dockerfile, Volumes
        * 0.4 YAML basics: syntax, indentation, objects.
        * 0.5 What is DevOps, CI/CD, Cloud.
        * 0.6 Cloud-native principles (12-factor app, microservices)

🟢 1. KCNA Topics – Cloud Native & Kubernetes Basics

    📦 1.x Containers & Orchestration

        * 1.1 What is a container and why it's useful.
        * 1.2 Container runtimes: containerd, CRI-O, Docker.
        * 1.3 Why orchestration is needed.
        * 1.4 What is kubernetes.

    ⚙️ 1.x Kubernetes Fundamentals

        * 1.5 Kubernetes architecture: Master & Worker nodes.
        * 1.6 What are Pods, Deployments, Services.
        * 1.7 Labels, Selectors, Namespaces.
        * 1.8 Kubelet, kube-proxy, API Server overview.
        * 1.9 How Kubernetes schedules and scales containers.

    🧱 1.x Cloud Native Ecosystem (CNCF)

        * 1.10 CNCF landscape: Kubernetes, Prometheus, Envoy, etc.
        * 1.11 What is a Service Mesh.
        * 1.12 GitOps, Helm, Kustomize

    🕵️ 1.x Observability

        * 1.13 Logs, metrics, tracing (Prometheus, Fluentd basics)

🟡 2. CKA Topics – Cluster Admin & Management

    🏗️ 2.x Cluster Setup & Configuration

        * 2.1 Install Kubernetes with kubeadm.
        * 2.2 Kubernetes config files, certificates
        * 2.3 Kubeconfig, cluster context switching.
        * 2.4 etcd - what it is and how to back it up/restore
        * 2.5 CNI plugins - Calico, Flannel
        * 2.6 Managing systemd services.

    🧩 2.x Scheduling & Workloads

        * 2.7 Pod design: static pods, multi-container pods.
        * 2.8 Taints, tolerations, node affinity/anti-affinity
        * 2.9 DaemonSets, Jobs, CronJobs.
        * 2.10 Controlloing where Pods go

    🌐 2.x Services & Networking

        * 2.11 Service types: ClusterIP. NodePort, LoadBalancer.
        * 2.12 Ingress controllers and rules.
        * 2.13 Network Policies (allow/block traffic).

    💾 2.x Storage

        * 2.14 Volumes, Persistent Volumes (PV), PVCs.
        * 2.15 StorageClass, AccessModes.
        * 2.16 ConfgMaps & Secrets.

    🔍 2.x Troubleshooting & Logging

        * 2.17 Debugging: logs, describe, events.
        * 2.18 CrashLoopBackOff, ImagePullBackOff.
        * 2.19 node/pod/network issues.
        * 2.20 CPU/memory resource issues.

🟡 3. CKAD Topics – App Development & Deployment

    🔧 3.x Core Concepts

        * 3.1 Pods, ReplicaSets, Deployments deep dive.
        * 3.2 Rolling updates, canary deployments.
        * 3.3 Deployment Strategies.

    ⚙️ 3.x Configuration & Secrets

        * 3.4 ConfigMaps: injecting config into Pods.
        * 3.5 Secrets: environment variables and volumes.
        * 3.6 Environment variables, command overrides.

    📊 3.x Observability & Health Checks

        * 3.7 Liveness and Readiness probes.
        * 3.8 Logs, debugging broken apps.
        * 3.9 Labels, annotations for monitoring.

    🔁 3.x Multi-Container Pods

        * 3.10 Sidecar patterns (logging, proxy).
        * 3.11 Init containers.
        * 3.12 Shared volumes

    🌐 3.x Networking

        * 3.13 Service discovery
        * 3.14 DNS inside Kubernetes
        * 3.15 Ingress basics (host/path-based routing)
    
    💾 3.x Persistence

        * 3.16 Volume types (emptyDir, hostPath).
        * 3.17 PVCs in apps.
        * 3.18 Stateful apps overview

🔁 4. Beyond Certification (Advanced / Optional)

    * 4.1 Kubernetes RBAC (Roles, ClusterRoles)
    * 4.2 Pod Security Policies / Admission Controllers.
    * 4.3 Monitoring with Prometheus/Grafana
    * 4.4 Helm 3 - chart creation and deployment
    * 4.5 GitOps with ArgoCD or FluxCD
    * 4.6 Custom Resource Definitions (CRDs)
    * 4.7 Operators and controller patterns.
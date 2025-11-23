
# CKA Exam Domains & Topics (Official CNCF Syllabus)

This file outlines the Certified Kubernetes Administrator (CKA) exam domains and topics. It mirrors the official CNCF syllabus and is organized for quick reference and study planning.

## Table of contents
- [Domain 1 — Cluster Architecture, Installation & Configuration (25%)](#domain-1)
- [Domain 2 — Workloads & Scheduling (15%)](#domain-2)
- [Domain 3 — Services & Networking (20%)](#domain-3)
- [Domain 4 — Storage (10%)](#domain-4)
- [Domain 5 — Troubleshooting (30%)](#domain-5)

---

## Domain 1 — Cluster Architecture, Installation & Configuration (25%)

1.1 Manage Role-Based Access Control (RBAC)

- Roles, ClusterRoles
- RoleBinding, ClusterRoleBinding
- ServiceAccounts
- Access scopes

1.2 Manage a Highly Available Kubernetes Cluster

- API-server HA
- etcd HA
- Control plane redundancy

1.3 Provision & Maintain Kubernetes Infrastructure

- Cluster setup basics
- Managing nodes
- Node lifecycle
- Labels, taints

1.4 Perform Cluster Maintenance

- Cordon, drain, uncordon nodes
- Upgrade strategy
- Backup & restore basics

1.5 Use Kubeadm to Install/Upgrade a Cluster

- Kubeadm conceptual knowledge (hands-on optional)

1.6 Implement etcd Backup & Restore

- Snapshots
- Restore procedure
- Disaster recovery

---

## Domain 2 — Workloads & Scheduling (15%)

2.1 Understand Deployments & Rollback / Rollout

- Deployment strategies
- Rolling updates
- Version history

2.2 Scheduling

- Manual scheduling
- `nodeSelector`
- Node Affinity / Anti-Affinity
- Taints & tolerations
- Pod priority

2.3 Understand DaemonSets

- Node-level workloads
- Use-cases: logging agents, monitoring

2.4 Resource Management

- Requests & limits
- LimitRange
- ResourceQuota
- Pod QoS classes

2.5 Multi-Container Pod Design

- Init containers
- Sidecar containers
- Ambassador/Adapter patterns

---

## Domain 3 — Services & Networking (20%)

3.1 Cluster Networking Concepts

- Pod-to-Pod networking
- Node-to-Pod networking
- CNI basics

3.2 Service Types

- ClusterIP
- NodePort
- LoadBalancer
- ExternalName

3.3 Ingress Controller & Ingress Resources

- Path routing
- Host routing
- TLS termination

3.4 Network Policies

- Allow/Deny traffic
- Namespace / label-based rules

3.5 Troubleshoot Networking

- DNS issues
- Connectivity tests
- kube-proxy behavior

---

## Domain 4 — Storage (10%)

4.1 Persistent Storage

- PersistentVolume
- PersistentVolumeClaim
- StorageClass

4.2 Volume Types

- `emptyDir`
- `hostPath`
- ConfigMap / Secret volumes
- Downward API

4.3 StatefulSets Storage

- VolumeClaimTemplates
- Stable network identity

4.4 Understand Access Modes & Policies

- ReadWriteOnce / ReadOnlyMany / ReadWriteMany
- Reclaim policies

---

## Domain 5 — Troubleshooting (30%)

5.1 Application Failure

- CrashLoopBackOff
- ImagePull errors
- Resource limit issues
- Probe failures

5.2 Control Plane Failure

- API-server not running
- Scheduler failure
- Controller manager issues

5.3 Worker Node Failure

- Node NotReady
- Node pressure issues
- kubelet issues

5.4 Networking Failures

- DNS lookup failure
- NetworkPolicy blocking
- CNI plugin issues

5.5 Storage Failures

- PVC/PV binding issues
- Mount errors
- Access mode mismatch

5.6 Debugging Tools

- `kubectl logs`
- `kubectl exec`
- `kubectl debug`
- `kubectl top`
- `kubectl get events`
- JSONPath expressions

---

_Last updated: 23 November 2025_
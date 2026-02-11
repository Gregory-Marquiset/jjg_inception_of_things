> This project has been created as part of the 42 curriculum by [jeportie](https://github.com/jeportie), [jmaruffy](https://github.com/Maruffly) and [gmarquis](https://github.com/Gregory-Marquiset).

---

## Table of Contents

* [Description](#description)
* [Instructions](#instructions)
* [CI/CD & Project management](#cicd--project-management)
* [Contributors responsibilities](#contributors-responsabilities)
* [Resources](#resources)

---
<a id="description"></a>

## 🌐 Description

### Inception of Things (IoT) — Kubernetes & GitOps Introduction

**Overview:**  
Inception of Things is a system administration project focused on discovering Kubernetes through lightweight distributions (K3s and K3d). The project introduces virtualization, container orchestration, Ingress configuration, and GitOps deployment workflows using Argo CD.

**Goal:**  
Understand and implement a minimal Kubernetes infrastructure from scratch, including:

- Virtual machine provisioning
- K3s cluster setup (server + agent)
- Deployment of multiple applications
- Ingress routing based on host rules
- GitOps workflow with Argo CD
- Versioned application deployment

**Environment Constraints:**

- All mandatory parts are executed inside virtual machines
- Strict folder structure (`p1`, `p2`, `p3`, optional `bonus`)
- Public Git repository required for GitOps part

---

### Project Structure

The project is divided into three mandatory parts:

#### Part 1 — K3s & Vagrant

- Creation of two virtual machines via Vagrant
- Installation of K3s:
  - Server (controller mode)
  - Agent (worker mode)
- Static IP configuration
- SSH access without password
- kubectl usage

#### Part 2 — K3s & Three Applications

- Single VM running K3s (server mode)
- Deployment of three web applications
- Ingress configuration with host-based routing
- Replicas management for selected applications

#### Part 3 — K3d & Argo CD

- Installation of K3d (Docker-based Kubernetes)
- Namespace isolation:
  - `argocd`
  - `dev`
- GitOps deployment via Argo CD
- Versioned Docker image (v1 → v2)
- Automatic synchronization after Git update

---

<a id="instructions"></a>

## 🚀 Instructions

Project setup and execution steps will be documented here once implementation begins.

---

<a id="cicd--project-management"></a>

## ⚙ CI/CD & Project management

This section will document:

- Repository organization
- Branching strategy
- Git workflow conventions
- Automation scripts (if implemented)
- GitOps workflow (Argo CD integration)

Details will be added as the project progresses.

---

<a id="contributors-responsabilities"></a>

## 👥 Contributors responsibilities

Roles and responsibilities will be defined and documented here.

Each contributor will be able to explain:

- Infrastructure setup
- Kubernetes configuration
- Application deployment
- GitOps workflow
- Automation scripts

This section will be updated during development.

---

<a id="resources"></a>

## 📑 Resources

### Documentation / References

* [Kubernetes Documentation](https://kubernetes.io/docs/)
* [K3s Documentation](https://docs.k3s.io/)
* [K3d Documentation](https://k3d.io/)
* [Vagrant Documentation](https://developer.hashicorp.com/vagrant/docs)
* [Argo CD Documentation](https://argo-cd.readthedocs.io/)
* [Docker Documentation](https://docs.docker.com/)

---

> This is a 42 school project. No license is provided.

---

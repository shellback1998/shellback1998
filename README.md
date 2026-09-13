# Hi, I'm Scott Gaudet 👋

### Engineering Technology Professional • Developer • DevOps & Homelab Learner • Scrimbassador

I'm an engineering technology professional with more than 20 years of experience working with complex engineering systems, digital engineering platforms, data, and technology.

I'm expanding that background into modern software development, automation, DevOps, containerization, and infrastructure technologies.

My learning has grown from front-end development with **HTML, CSS, and JavaScript** into **Python, Docker, Ansible, CI/CD, Linux, Raspberry Pi, and Kubernetes/K3s**.

I learn best by building real systems, breaking them, troubleshooting them, documenting what happened, and then improving them.

* 🧠 **What I build:** Web applications, automation tools, containerized applications, homelab infrastructure, and technical learning projects
* ⚙️ **DevOps & Infrastructure:** Docker, Docker Compose, Ansible, GitHub Actions, GHCR, Linux, Tailscale, Kubernetes & K3s
* 💻 **Development:** JavaScript, Node.js, HTML, CSS, Python & C#
* 🥧 **Homelab:** Turing Pi / Raspberry Pi cluster, Linux VMs, networking, containers & Kubernetes
* 📚 **Currently learning:** Kubernetes, K3s, CI/CD, infrastructure automation, Markdown, and full-stack development
* 🎯 **Current goal:** Combine engineering experience, software development, automation, and DevOps to build useful real-world systems
* 📡 **Fun fact:** When I'm not working with engineering systems, code, or my homelab, I'm an amateur radio operator

---

## 🛠️ My Toolkit

### Development

`JavaScript` • `Node.js` • `HTML` • `CSS` • `Python` • `C#`

### DevOps & Automation

`Docker` • `Docker Compose` • `Ansible` • `GitHub Actions` • `CI/CD` • `GitHub Container Registry`

### Kubernetes & Infrastructure

`Kubernetes` • `K3s` • `Linux` • `Ubuntu` • `Debian` • `Tailscale` • `SSH`

### Homelab

`Turing Pi` • `Raspberry Pi` • `VMware` • `ARM64` • `x86-64`

### Development Tools

`Git` • `GitHub` • `Visual Studio Code` • `JetBrains IDEs` • `Markdown`

---

# 🧪 DevOps & Homelab Learning Lab

I'm building a hands-on homelab to learn modern DevOps and infrastructure concepts rather than only studying them theoretically.

My lab combines:

```text
GitHub
   |
   v
GitHub Actions / CI
   |
   v
Container Images
   |
   v
GitHub Container Registry
   |
   v
Ansible / Kubernetes
   |
   v
Linux VMs + Turing Pi Cluster
```

The environment gives me a place to experiment with real deployment, networking, automation, container, and orchestration workflows.

## 🥧 Turing Pi Cluster

My homelab includes a multi-node Turing Pi / Raspberry Pi environment used for learning:

* Linux administration
* SSH and remote management
* Docker
* Docker Compose
* Ansible
* ARM64 containers
* Networking
* Cluster administration
* Kubernetes worker-node concepts

The environment is remotely accessible using **Tailscale**, while cluster traffic remains on the local network.

---

# 🐳 Docker & Containerization

I've been using Docker to move beyond simply running containers and learn how complete multi-container applications are designed and operated.

Topics I've practiced include:

* Docker images and containers
* Dockerfiles
* Alpine and slim base images
* Port publishing
* Docker networking
* Volumes and persistent data
* Docker Compose
* Container logs and troubleshooting
* Multi-container application architecture
* ARM64 vs AMD64 container architecture
* Multi-platform container builds

---

# 🗳️ Voting Application

One of my primary DevOps learning projects is a multi-container voting application.

The application contains:

```text
Browser
   |
   v
Python / Flask Vote App
   |
   v
Redis
   |
   v
Python Worker
   |
   v
PostgreSQL
   |
   v
Node.js Results App
   |
   v
Browser
```

This project has become my test application for learning Docker, CI/CD, Ansible, container registries, multi-architecture builds, and eventually Kubernetes.

### Technologies

`Python` • `Flask` • `Redis` • `PostgreSQL` • `Node.js` • `Docker` • `Docker Compose`

---

# 🔄 CI/CD With GitHub Actions

I built a GitHub Actions pipeline for the voting application to learn CI/CD through a real project.

The pipeline currently performs:

```text
Git Push
   |
   v
GitHub Actions
   |
   +--> Validate Docker Compose
   |
   +--> Build Containers
   |
   +--> Start Application
   |
   +--> Run Smoke Tests
   |
   +--> Build AMD64 + ARM64 Images
   |
   +--> Publish Images to GHCR
```

Topics I've practiced include:

* GitHub Actions workflows
* Automated Docker builds
* Docker Compose validation
* Runtime smoke testing
* GitHub Container Registry
* Buildx
* QEMU
* AMD64 and ARM64 images
* Commit-based image tags
* CI troubleshooting

---

# 🤖 Infrastructure Automation With Ansible

I'm using Ansible to learn how infrastructure and application deployment can be automated rather than manually repeated across machines.

My Ansible lab includes:

* Inventories
* Ad-hoc commands
* Playbooks
* Variables
* Group variables
* Loops
* Conditionals
* Roles
* Handlers
* Idempotency
* Ansible Vault
* Package management
* Cluster health checks
* Application deployment

I've also used Ansible to deploy the voting application from **GitHub Container Registry to an ARM64 Turing Pi node**.

---

# ☸️ Kubernetes & K3s

I'm currently learning Kubernetes using a dedicated **K3s control-plane VM**, with plans to add Turing Pi systems as ARM64 worker nodes.

My Kubernetes learning started from the fundamentals rather than immediately deploying a large application.

So far I've worked with:

* Kubernetes clusters and nodes
* Control planes
* Pods
* Deployments
* ReplicaSets
* Services
* NodePort
* ClusterIP
* Labels and selectors
* EndpointSlices
* Scaling
* Desired vs actual state
* Self-healing
* Rolling updates
* Rollbacks
* Declarative YAML configuration
* `kubectl`
* Git-based Kubernetes configuration

One of my favorite demonstrations so far was deliberately deleting a Pod and watching Kubernetes automatically create a replacement to restore the desired replica count.

### Current Kubernetes Architecture

```text
HP Windows Host
│
├── turing-manager VM
│     └── Ansible / Docker / Cluster Administration
│
└── k8s-manager VM
      └── K3s Control Plane
              |
              └── Turing Pi ARM64 Workers — coming next
```

Next topics include **ConfigMaps, Secrets, persistent storage, Ingress, worker nodes, monitoring, and eventually deploying the voting application to Kubernetes**.

---

# 📝 Technical Documentation

Another part of this journey is learning to properly document what I build.

I'm creating documentation for my labs using:

* Markdown
* GitHub READMEs
* Architecture diagrams
* Command references
* Step-by-step lab documentation
* Troubleshooting notes
* Word and PDF reference guides

I'm also learning Markdown itself so I can create and maintain technical documentation without relying entirely on generated documentation.

---

# 🚀 Featured Projects

## 🗳️ Voting Application

A multi-container application I'm using as the foundation for learning Docker, CI/CD, container registries, Ansible, ARM64 deployment, and eventually Kubernetes.

**Tech Stack:** `Python` • `Flask` • `Redis` • `PostgreSQL` • `Node.js` • `Docker` • `GitHub Actions` • `GHCR` • `Ansible`

---

## ☸️ Turing K3s Lab

My hands-on Kubernetes learning environment.

The project documents Kubernetes concepts as I build them, beginning with Deployments, Pods, Services, scaling, self-healing, rolling updates, rollback, and declarative YAML.

**Tech Stack:** `Kubernetes` • `K3s` • `Linux` • `YAML` • `Git` • `Turing Pi`

---

## 🃏 Blackjack

A browser-based Blackjack game built while developing my understanding of core JavaScript concepts and application logic.

**What I practiced:**

* JavaScript functions and application logic
* Arrays and objects
* Conditional logic
* DOM manipulation
* HTML and CSS
* Git and GitHub workflow
* Netlify deployment

**Tech Stack:** `JavaScript` • `HTML` • `CSS` • `Netlify`

---

## 📇 Leads Tracker

A web-based leads tracking application that introduced me to persistent application data and cloud-hosted realtime databases.

**What I practiced:**

* JavaScript application logic
* DOM manipulation
* Event listeners
* User input
* Persistent data
* Firebase Realtime Database
* Netlify deployment

**Tech Stack:** `JavaScript` • `HTML` • `CSS` • `Firebase` • `Netlify`

---

# 🎓 Continuous Learning

My learning path now spans several connected areas:

```text
Software Development
        |
        +--> JavaScript / Node.js
        +--> Python
        +--> C#
        |
        v
Version Control
        |
        +--> Git
        +--> GitHub
        |
        v
Containers
        |
        +--> Docker
        +--> Docker Compose
        |
        v
Automation
        |
        +--> Ansible
        |
        v
CI/CD
        |
        +--> GitHub Actions
        +--> GHCR
        |
        v
Container Orchestration
        |
        +--> Kubernetes
        +--> K3s
```

I'm continuing my full-stack development training through **Scrimba** while using my homelab to gain practical experience with Linux, automation, DevOps, and Kubernetes.

---

# 💡 Engineering Meets Software & DevOps

My professional background is rooted in engineering technology and digital engineering, where I've spent more than two decades working with complex engineering applications, data, systems, and processes.

Software development, automation, and DevOps are a natural extension of that experience.

I'm particularly interested in the intersection of:

* ⚙️ Engineering technology
* 💻 Software development
* 🤖 Automation
* 🐳 Containers
* ☸️ Kubernetes
* 🔗 APIs and system integration
* 📊 Data and analytics
* 🧠 Problem solving

My goal isn't simply to learn another programming language or collect technologies.

I want to understand **how modern systems are designed, automated, deployed, operated, troubleshot, and improved**.

---

# 🌐 Connect With Me

I'm always interested in connecting with developers, engineers, homelab enthusiasts, lifelong learners, and others working at the intersection of software, engineering, automation, and DevOps.

🚀 **Always learning. Always building.**

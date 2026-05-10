# KDM CLI

KDM CLI is a modern command-line monitoring and management tool built for Docker and Kubernetes environments. It provides developers and DevOps engineers with a lightweight, terminal-first experience for monitoring containers, pods, clusters, and system health in real time.

---

## Overview

KDM is designed to simplify infrastructure visibility directly from the terminal without requiring heavy dashboards or complex monitoring platforms. The tool automatically detects Docker containers and Kubernetes resources, providing real-time operational insights and health monitoring.

The project focuses on speed, simplicity, and developer productivity while maintaining scalability for production-grade environments.

---

## Core Features

### Docker Monitoring
- Automatic detection of running containers
- Container health monitoring
- CPU and memory usage tracking
- Container uptime analysis
- Real-time container statistics

### Kubernetes Monitoring
- Kubernetes cluster detection
- Pod and node monitoring
- Namespace visibility
- Deployment status tracking
- Resource utilization metrics
- Pod health and restart analysis

### Real-Time Monitoring
- Live system metrics
- Resource consumption tracking
- Health status reporting
- Runtime diagnostics
- Performance visibility

### Notification System (Planned)
- Discord webhook integration
- Email alert support
- Health failure notifications
- Automated incident alerts

---

## Technology Stack

| Technology | Purpose |
|------------|---------|
| TypeScript | Core application development |
| Node.js | Runtime environment |
| Docker Engine API | Docker container communication |
| Kubernetes Client API | Kubernetes cluster interaction |
| Commander.js | CLI command management |
| Chalk | Terminal styling |
| Ora | CLI loaders and spinners |
| Inquirer | Interactive command prompts |

---

## Installation

### Global Installation

```bash
npm install -g kdm-cli
```

### Start KDM

```bash
kdm
```

---

## CLI Commands

### General Commands

```bash
kdm --help
kdm --version
```

### Docker Commands

```bash
kdm docker ps
kdm docker stats
kdm docker health
```

### Kubernetes Commands

```bash
kdm k8s pods
kdm k8s nodes
kdm k8s health
```

### Monitoring

```bash
kdm monitor
```

---

## Project Structure

```bash
kdm-cli/
│
├── src/
│   ├── commands/
│   ├── docker/
│   ├── kubernetes/
│   ├── monitor/
│   ├── services/
│   └── utils/
│
├── bin/
├── package.json
├── tsconfig.json
└── README.md
```

---

## Development Goals

KDM aims to provide a unified terminal-based monitoring experience for containerized environments and orchestration systems. The long-term vision includes support for advanced infrastructure management, distributed monitoring, and intelligent operational insights.

---

## Planned Features

- Interactive terminal dashboard
- Multi-cluster Kubernetes support
- AI-powered health analysis
- Historical metrics tracking
- Log aggregation and streaming
- Prometheus integration
- Grafana integration
- Remote infrastructure monitoring
- Cloud deployment monitoring
- Real-time visualization support

---

## Philosophy

KDM is built around the following principles:

- Minimal setup
- Fast execution
- Terminal-first workflow
- Lightweight architecture
- Developer-centric experience
- Production-ready scalability

---

## Website

```txt
https://kdm-cli.vercel.app/
```

---

## Contributing

Contributions are welcome from developers, DevOps engineers, and open-source contributors.

### Contribution Workflow

```bash
git clone <repository-url>

git checkout -b feature/new-feature

git commit -m "Add new feature"

git push origin feature/new-feature
```

---

## License

MIT License

---

## Author

Utkarsh Patrikar

KDM CLI is an open-source initiative focused on modern container monitoring and Kubernetes operational tooling.

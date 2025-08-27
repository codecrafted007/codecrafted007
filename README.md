# 👋 Hi, I'm Brajesh (codecrafted007)

🚀 Senior Backend Engineer | Distributed Systems | Golang | Kubernetes-Native Infra  
🔧 Building scalable, infra-heavy backend systems across cloud and edge environments.  
🌐 Currently focused on service orchestration, mesh-aware rollouts, and secure multi-cluster coordination.

### 🔧 Tech Stack
- **Languages:** Golang, Python, Bash, Java
- **Infra:** Kubernetes, Helm, Terraform, Docker, eBPF (learning), Envoy (beginner)
- **Cloud:** AWS, GCP, On-Premise hybrid systems
- **Interests:** Service Mesh, System Design, LLM Infra, Observability, Chaos Engineering

### 📂 Notable Projects
- **upgrade-service**: Go-based upgrade engine handling distributed rollouts across hybrid edge clusters.
- **mongo_k8s_migrate_offline.sh**: Shell tool for offline MongoDB migrations across K8s clusters.
- **File Chunk Downloader**: Python-based file chunk stitching engine with resume support and disk space validation.
- ⚡ autozap

**Structured, opinionated logging wrapper for Go using Uber's Zap logger**

`autozap` is a lightweight and extensible logging module designed for production-grade Go services. It wraps around [Zap](https://github.com/uber-go/zap) and adds:

- Opinionated log formatting (caller info, request ID, timestamps)
- Default log level configs
- Easy-to-use global logger access
- Context-aware logging helpers
- Sensible defaults for infrastructure-oriented microservices

---

## 🛠️ Features

- ✅ Pre-configured Zap production logger with optional debug override
- ✅ Global logger setup (`autozap.Init()`) for shared use
- ✅ `WithRequestID()` for context propagation in microservices
- ✅ Automatically injects `caller`, `timestamp`, and structured fields
- ✅ Supports `Info()`, `Debug()`, `Warn()`, `Error()` methods
- ✅ Designed for simplicity and minimal setup in distributed Go backends



> I'm always looking to contribute to performance-sensitive backend problems and production-first Go tooling.

📫 Reach me at: [LinkedIn](https://www.linkedin.com/in/brajeshpant) | [codecrafted007@gmail.com](mailto:codecrafted007@gmail.com)

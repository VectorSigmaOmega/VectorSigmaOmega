# Abhinash Dutta

CS student at NIT Silchar. I build things to understand them — sometimes that means writing a container runtime from scratch, sometimes it means injecting eBPF code into the kernel to watch packets fly by at line-rate.

I'm drawn to systems work: the closer to the metal, the better. But I also care about the full stack from kernel hooks to distributed backends to the UI that makes it all usable.

---

## What I'm working on

| Project | What it is | Stack |
|---|---|---|
| [K-Watch](https://github.com/VectorSigmaOmega/K-Watch) | eBPF/XDP network observability engine — SYN-flood detection + auto-mitigation, sub-5% CPU overhead, CO-RE portable | C++20, libbpf, XDP |
| [Vortex](https://github.com/VectorSigmaOmega/Vortex) | Container runtime from scratch — namespaces, cgroups, filesystem sandboxing, no external deps | C++20, Linux |
| [Guardian](https://github.com/VectorSigmaOmega/Guardian) | Fleet monitoring + auto-remediation — alert → Slack → webhook → Ansible runbook loop | Python, Prometheus, Alertmanager, Grafana, Ansible |
| [SwiftBatch](https://github.com/VectorSigmaOmega/SwiftBatch) | Async image processing backend — production-style with worker queue, object storage, observability | Go, Postgres, Redis, MinIO, Docker, K8s |
| [Sentinel](https://github.com/VectorSigmaOmega/Sentinel) | Graph-native supply chain intelligence — disruption simulation, blast-radius tracing, recovery recommendations | TypeScript |
| [PacketForge](https://github.com/VectorSigmaOmega/PacketForge) | Userspace L2/L3 network stack — ARP, ICMP, and raw Ethernet crafted by hand over `AF_PACKET` | C++20 |
| [BasicRAG](https://github.com/VectorSigmaOmega/BasicRAG) | RAG system over PDFs — FAISS in-memory vector store, Gemini embeddings + synthesis | Python, FastAPI, FAISS, React, Gemini API |

---

## Stack

```
Systems    C++20 · C · eBPF/XDP · libbpf · Linux internals
Backend    Go · Python · TypeScript · FastAPI · REST
Infra      Docker · Kubernetes · Prometheus · Grafana · Ansible
Data       PostgreSQL · Redis · MinIO · FAISS
Frontend   React · Vite
```

---

## A few older things

- **[Collaborate.](https://github.com/VectorSigmaOmega/Collaborate.)** — real-time shared whiteboard (JS, WebSockets)
- **[AStar](https://github.com/VectorSigmaOmega/AStar)** — A\* pathfinding visualizer (Python + Pygame)
- **[TicTacToe](https://github.com/VectorSigmaOmega/TicTacToe)** — minimax solver (C++)
- **[Matrix-Rain](https://github.com/VectorSigmaOmega/Matrix-Rain)** — console matrix rain effect (C)

---

## Connect

- Portfolio: [abhinash.dev](https://www.abhinash.dev/)
- Email: abhinashjrt22@gmail.com
- Open to: internships, SWE roles, anything interesting

---

*"Eager to learn everything under the sun."*

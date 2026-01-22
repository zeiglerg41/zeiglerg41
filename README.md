# Hey there! I'm Garrett.

Software Engineer building production infrastructure that doesn't go down. Currently at Remote Tracking Systems developing real-time tracking systems for vehicles, assets, and personnel across proving grounds, secure campuses, airports, and critical facilities.

## What I Do

I focus on high-availability architecture, infrastructure automation, and embedded systems. From React Native apps to PostgreSQL replication, Docker Swarm orchestration to ARM cross-compilation - building full-stack systems that handle thousands of real-time updates with sub-second failover.

**Stack:** PostgreSQL, Redis, Node.js, Go, Next.js, React Native, Docker Swarm, Tile38, C, Python, Lighttpd, Keepalived

## Contact

- **Work:** <garrett@remotetrackingsystems.com>
- **Personal:** <zeiglerg41@gmail.com>
- **LinkedIn:** [linkedin.com/in/garrettzeigler](https://linkedin.com/in/garrettzeigler)
- **Portfolio:** [zeiglerg41.github.io](https://zeiglerg41.github.io/garrett_zeigler_page.github.io/)

---

## Professional Work @ Remote Tracking Systems, Inc

Building production infrastructure for real-time tracking of vehicles, assets, and personnel at proving grounds, secure campuses, airports, and critical facilities.

### vMonitor - High-Availability Tracking Platform

Handles thousands of position updates per minute with sub-second failover and zero-downtime deployments. Real-time geofence monitoring, alerts, and fleet management that survives node failures without anyone noticing.

**Infrastructure:** Node.js/Express REST API, PostgreSQL replication (repmgr), Redis pub/sub event broadcasting, Docker Swarm orchestration, WebSockets for live updates, Tile38 geospatial queries. Keepalived (VRRP) manages automatic failover, PM2 handles process management, Mutagen/lsyncd sync data between nodes.

### React Native Tracking Application

Turn any phone into a tracking device. Works standalone for GPS broadcasting or as a BLE gateway for vehicle/asset-mounted sensors, eliminating dedicated hardware needs in many scenarios.

**Tech:** React Native cross-platform mobile, BLE integration for external tracking hardware, custom binary protocol (FRI messages) for secure position transmission, real-time geofence detection, works with self-hosted or cloud infrastructure.

### Embedded Device Infrastructure

Manage entire ARM device clusters from a browser with automatic failover between nodes. Complete stack for tracking devices running Yocto Linux.

**Built:** High-performance C binary (vgateway) with direct SQLite integration for sub-millisecond data queries, Python CGI backend for system configuration (networkd, NTP, keepalived), Lighttpd web server cross-compiled for ARM EABI5, keepalived VRRP clustering with custom health checks, shell-based deployment automation for cluster-wide config synchronization.

### Enterprise CRM Platform

Centralized workforce operations that were previously spreadsheet chaos. Coordinates site installations and manages secure integrations for on-prem deployments.

**Deployment:** Hardened Linux infrastructure behind customer firewalls with strict access controls and security hardening.

### Content & Marketing

Handle content marketing and technical writing on LinkedIn. Led redevelopment of Remote Tracking Systems website.

---

## Personal Projects

### VocaVista

Microservices language learning platform with voice conversation and real-time feedback. Basically Anki meets ChatGPT with actual speaking practice.

Built with Docker Swarm orchestration, React Native/Expo for mobile UI, OpenAI Whisper for speech-to-text, Coqui TTS for text-to-speech, LLaMa 2 7B/Mistral 7B for conversation engine with API fallbacks (OpenAI, Anthropic). Backend uses NATS for event messaging, Redis for session management, PostgreSQL for persistence, Traefik as API gateway, and Prometheus/Grafana for monitoring. Modular compose architecture for independent service deployment.

### CLIO (Command Line Interactive Operator)

Terminal-based AI coding assistant with full file editing capabilities and local model support. Like claude-code but fully open source with complete workflow control.

Built with Python and Textual framework for interactive TUI. Supports any OpenAI-compatible API (Ollama, OpenWebUI, local vLLM) or hosted providers (OpenAI, Anthropic, Gemini, DeepSeek). Implements agentic tool use for autonomous file operations and shell command execution, hybrid context management with RAG (ChromaDB + MiniLM embeddings) for semantic retrieval beyond sliding window. Includes VS Code/Cursor extension with inline diff previews and CodeLens accept/reject buttons.

### Server Monitoring Agent

Lightweight Go-based monitoring system with automated remediation for self-hosted infrastructure. Catches problems and fixes them before alerts even fire.

Built with Go for minimal resource footprint (15-20MB RAM, <1% CPU). Monitors disk usage via syscall and Docker container health. Reports metrics to API backend for analysis and alerting. Implements configurable health checks with automatic failover detection. Deployed as systemd service or standalone binary. Started in my homelab, now deployed in production environments.

---

## What I'm Into

Building reliable systems that don't need babysitting. High-availability architecture, CI/CD automation, infrastructure as code. Big on zero-downtime deployments and understanding what's actually happening under the hood - VPNs, load balancing, service orchestration, networking, that kind of thing. Security-conscious but pragmatic about it.

Open to connecting with folks working on distributed systems, site reliability, and infrastructure automation.

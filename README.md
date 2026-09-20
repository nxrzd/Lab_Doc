# Homelab Documentation

This is an index of the documented components of my self-hosted homelab. Each subsystem has its own README covering purpose, architecture, and operational notes.

**A note on scope:** identifying details (public domains, real IP addresses, exact hostnames, external tunnel endpoints, and exact software versions) have been redacted or replaced with placeholders throughout this documentation set. Software/project names are kept accurate since that information is already public (open-source projects), but topology details that would help someone map or target this specific deployment are intentionally generic.

## Components

| Doc | Covers |
|---|---|
| [proxmox-infrastructure.md](./proxmox-infrastructure.md) | Compute cluster, VM/LXC layout, storage |
| [network-security-monitoring.md](./network-security-monitoring.md) | Firewall, SIEM, log/metrics stack |
| [docker.md](./docker.md) | Containerized services and orchestration approach |
| [python-scripts.md](./python-scripts.md) | Automation and tooling scripts |
| [jellyfin.md](./jellyfin.md) | Media server |
| [web-dev-projects.md](./web-dev-projects.md) | Hosted personal/dev web projects |
| [smb-servers.md](./smb-servers.md) | File sharing |
| [nextcloud.md](./nextcloud.md) | Self-hosted cloud storage |
| [pentest-lab-images.md](./pentest-lab-images.md) | Offensive-security practice VMs (TryHackMe / HTB) |
| [local-ai.md](./local-ai.md) | Local LLM inference |
| [authentik.md](./authentik.md) | Identity provider / SSO |

## General conventions used across these docs

- IP addresses are shown as a redacted private range (e.g. `10.x.x.x`) rather than actual host addresses.
- Public domains are replaced with `<redacted-domain>` or a generic `example.lab` placeholder.
- Node/VM names are functional (e.g. `pve-node-a`) rather than the literal hostnames in production.
- Credentials, API keys, and tunnel configs are never included — only the pattern/approach is documented.

# Homelab Documentation

This is an index of the documented components of my self-hosted homelab. Each subsystem has its own README covering purpose, architecture, and operational notes.

**A note on scope:** identifying details (public domains, real IP addresses, exact hostnames, external tunnel endpoints, and exact software versions) have been redacted or replaced with placeholders throughout this documentation set. Software/project names are kept accurate since that information is already public (open-source projects), but topology details that would help someone map or target this specific deployment are intentionally generic.

## Components



| Component                       | Repo                                                                                                                                                         |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Proxmox infrastructure          | [PVE_Infra_Docs](https://github.com/nxrzd/PVE_Infra_Docs)                                                                                                    |
| Network security & monitoring   | [Net_Sec_Doc](https://github.com/nxrzd/Net_Sec_Doc)                                                                                                          |
| DNS (Pi-hole + Unbound)         | [DNS_Doc](https://github.com/nxrzd/DNS_Doc)                                                                                                                  |
| Docker                          | [Docker_Doc](https://github.com/nxrzd/Docker_Doc)                                                                                                            |
| Python scripts / automation     | [Scripting_Doc](https://github.com/nxrzd/Scripting_Doc)                                                                                                      |
| Jellyfin                        | [Jellyfin_Doc](https://github.com/nxrzd/Jellyfin_Doc)                                                                                                        |
| Web dev projects                | [Web_Projects_Doc](https://github.com/nxrzd/Web_Projects_Doc)                                                                                                |
| SMB servers                     | [SMB_Server_Doc](https://github.com/nxrzd/SMB_Server_Doc)                                                                                                    |
| Nextcloud                       | [Nextcloud_Doc](https://github.com/nxrzd/Nextcloud_Doc) (compose reference: [Nextcloud-Docker-Compose-](https://github.com/nxrzd/Nextcloud-Docker-Compose-)) |
| Pentest lab / TryHackMe / HTB   | [Pentest_Lab_Doc](https://github.com/nxrzd/Pentest_Lab_Doc)                                                                                                  |
| Local AI                        | [Local_AI_Doc](https://github.com/nxrzd/Local_AI_Doc)                                                                                                        |
| Authentik                       | [Authentik_Doc](https://github.com/nxrzd/Authentik_Doc)                                                                                                      |
| Overall lab replica / reference | [HomeLab_Doc](https://github.com/nxrzd/HomeLab_Doc) — "docker containers to replicate a close image to my setup that I run at home" (formerly `Lab_Doc`)     |
|                                 |                                                                                                                                                              |



## General conventions used across these docs

- IP addresses are shown as a redacted private range (e.g. `10.x.x.x`) rather than actual host addresses.
- Public domains are replaced with `<redacted-domain>` or a generic `example.lab` placeholder.
- Node/VM names are functional (e.g. `pve-node-a`) rather than the literal hostnames in production.
- Credentials, API keys, and tunnel configs are never included — only the pattern/approach is documented.

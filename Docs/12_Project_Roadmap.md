---
title: Project Roadmap
tags:
  - homelab
  - roadmap
status: active
---

# Project Roadmap

## Phase 1 — Core Platform

- [x] Install [Proxmox VE](04_Proxmox.md)
- [x] Create virtual networking for home-LAN services
- [x] Deploy [Pi-hole](05_Pi-hole.md) and configure DNS filtering
- [x] Deploy [Docker](08_Docker.md), `media-docker` and the initial media services
- [x] Preserve [OPNsense](06_OPNsense.md) VM 102 and export a persistent configuration backup for future reuse

## Phase 2 — Reliability and Administration

- [ ] Configure Proxmox TOTP or WebAuthn two-factor authentication (recovery keys generated)
- [x] Run an extended SMART test for the backup disk
- [x] Configure Proxmox backups for selected core guests
- [ ] Test restoration of a backup into a new, unused VM/CT ID
- [ ] Add an off-host copy for important backups
- [ ] Confirm stable addressing for `media-docker`
- [ ] Review Pi-hole operations and recovery procedure

## Phase 3 — Core Service Operations

- [ ] Complete only useful media-stack integrations
- [ ] Review the temporary qBittorrent VPN configuration before treating it as final
- [ ] Configure private remote access only if required
- [ ] Document service maintenance and recovery procedures

## Deferred — Enterprise Security Lab (Separate Project)

- OPNsense private-LAN expansion, IPv6 policy, management rules, VPN and IDS/IPS
- Managed switching, second NIC, VLANs and inter-VLAN routing
- Active Directory, Windows clients, CA/PKI, WSUS and file services
- security monitoring, Sysmon, Sigma, Suricata, Zeek, OpenVAS and attack simulations
- Enterprise monitoring, high availability and Kubernetes

## Related Notes

- [Network Architecture](03_Network_Architecture.md)
- [Proxmox](04_Proxmox.md)
- [Pi-hole](05_Pi-hole.md)
- [OPNsense](06_OPNsense.md)
- [Docker](08_Docker.md)
- [TODO](../TODO.md)

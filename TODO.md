---
title: TODO
tags:
  - homelab
  - todo
status: active
---

# TODO

## Core Foundation

- [x] Install [Proxmox VE](Docs/04_Proxmox.md)
- [x] Create virtual networking for the core services
- [x] Deploy [Pi-hole](Docs/05_Pi-hole.md)
- [x] Configure DNS filtering
- [x] Deploy [Docker](Docs/08_Docker.md)
- [x] Finish Ubuntu Server installation for `media-docker`
- [x] Install Portainer on `media-docker`

## Preserve OPNsense Baseline

The isolated OPNsense LAN is reserved for the separate **Enterprise Security Lab** project. Do not expand its private-network configuration in this project.

- [x] Preserve the downloaded OPNsense configuration backup outside the Ubuntu live session
- [x] Detach the OPNsense ISO and verify boot order
- [x] Export a current, validated OPNsense configuration backup
- [x] Preserve VM 102 powered off until the Enterprise Security Lab begins

## Core Reliability and Administration

- [ ] Configure a Proxmox TOTP or WebAuthn second factor for administration
  - [x] Recovery keys generated and stored.
- [x] Run and record the extended SMART test for the 320 GB backup disk
- [x] Configure Proxmox backups for selected core VM/container configuration
  - Storage `Backup-320` contains backups for OPNsense VM 102 and Pi-hole CT 100.
- [ ] Test restoration of a backup into a new, unused VM/CT ID
- [ ] Define an off-host copy for important backups
- [ ] Confirm or create a DHCP reservation for `media-docker` (`192.168.1.30` planned)
- [ ] Review Pi-hole updates, upstream DNS and recovery procedure

## Media Services

- [ ] Install Tailscale on `media-docker` if private remote access is required
- [ ] Configure Jellyfin hardware transcoding / Intel Quick Sync if needed
- [ ] Install Bazarr for subtitles if required
- [ ] Connect qBittorrent to Sonarr/Radarr/Lidarr
- [ ] Review failing public indexers such as 1337x
- [ ] Replace or review the temporary VPNBook test configuration before treating qBittorrent VPN routing as final
- [ ] Troubleshoot Lidarr music indexers later

## Deferred — Enterprise Security Lab (Separate Project)

The following work is intentionally outside this project's scope and will be planned and documented in a separate vault or repository:

- [ ] Private OPNsense LAN configuration, IPv6 policy, management rules, VPN and IDS/IPS
- [ ] Windows Server, Active Directory, DNS, Group Policy and Windows client
- [ ] Kali Linux and attack simulations
- [ ] security monitoring, Sysmon, Sigma rules, Zeek, Suricata and vulnerability scanning
- [ ] Managed switch, second NIC, VLANs and inter-VLAN routing
- [ ] Enterprise services such as CA/PKI, WSUS, file server and secrets management
- [ ] High availability, Kubernetes and enterprise monitoring

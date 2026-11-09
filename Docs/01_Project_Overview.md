---
title: Project Overview
tags:
  - homelab
  - portfolio
  - infrastructure
status: active
---

# Project Overview

## Summary

This vault documents the core infrastructure of a personal homelab: Proxmox virtualization, home-LAN services, Pi-hole, Docker workloads, media storage and operational resilience. The goal is a stable, well-documented platform for personal services and infrastructure practice.

## Scope

### In scope

- [Proxmox VE](04_Proxmox.md) virtualization and virtual networking
- Home-LAN services, addressing and DNS filtering with [Pi-hole](05_Pi-hole.md)
- [Docker](08_Docker.md), Portainer and the `media-docker` media stack
- Storage, backup and recovery planning
- Preservation of the existing [OPNsense](06_OPNsense.md) VM as a reusable baseline

### Out of scope: Enterprise Security Lab

The private network, Active Directory, Windows clients, Kali, security monitoring, VLANs, IDS/IPS and security exercises will be developed as a separate future project named **Enterprise Security Lab**. The same Proxmox host and OPNsense VM may be reused, but that project will have its own scope, architecture and documentation.

Existing [Active Directory](07_Active_Directory.md) notes are retained only as pre-project reference material; they are not active work items for this homelab core project.

## Objectives

### Technical
- Learn and operate [Proxmox VE](04_Proxmox.md)
- Run and maintain [Docker](08_Docker.md) services
- Provide DNS filtering with [Pi-hole](05_Pi-hole.md)
- Manage dedicated media storage and personal services
- Improve backup, recovery and administration practices
- Preserve a foundational [OPNsense](06_OPNsense.md) deployment for future reuse

### Portfolio
This homelab is continuously documented as a professional portfolio project demonstrating practical virtualization, Linux, networking, service operations and infrastructure documentation.

## Skills Demonstrated
- Virtualization and resource management
- Linux administration
- Docker and containerized services
- DNS filtering and home-LAN services
- Storage and backup planning
- Virtual networking and foundational firewall deployment
- Infrastructure documentation

## Related Notes

- [Hardware Inventory](02_Hardware_Inventory.md)
- [Network Architecture](03_Network_Architecture.md)
- [Proxmox](04_Proxmox.md)
- [Pi-hole](05_Pi-hole.md)
- [OPNsense](06_OPNsense.md)
- [Docker](08_Docker.md)
- [Implementation Log](09_Implementation_Log.md)
- [TODO](../TODO.md)
- [CHANGELOG](../CHANGELOG.md)

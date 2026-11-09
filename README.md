# HomeLab Core Infrastructure

## Overview

This project documents the design, implementation and operation of the core infrastructure in a personal homelab. Its current scope is Proxmox virtualization, home-LAN services, Docker workloads, media storage, DNS filtering and resilience.

The isolated enterprise network, Active Directory and SIEM work are intentionally deferred to a separate future project, **Enterprise Security Lab**. This separation keeps personal services independent from the future security-training environment while allowing both projects to reuse the same physical Proxmox host.

Detailed documentation is available in [Project Overview](Docs/01_Project_Overview.md) and the other notes under `Docs`.

## Objectives

### Technical
- Learn and operate Proxmox VE
- Run and maintain Docker-based services
- Provide private DNS filtering with Pi-hole
- Operate a personal media stack on dedicated storage
- Establish tested backup and recovery practices
- Maintain the foundational OPNsense VM for later reuse

### Portfolio

This homelab is continuously documented as part of a professional portfolio. It demonstrates practical infrastructure, virtualization, Linux, storage and service-operations skills.

## Skills Demonstrated

### Virtualization
- Proxmox
- Resource management
- Virtual networking

### Linux and services
- Ubuntu
- Docker and Docker Compose
- Portainer
- Pi-hole
- Media services

### Networking
- Home-LAN addressing
- DNS filtering
- Virtual bridges
- Foundational OPNsense deployment

### Infrastructure
- Storage planning
- Backup planning
- Documentation
- Architecture design

## Current Priorities

- Preserve the existing OPNsense baseline for the future Enterprise Security Lab.
- Complete restore testing, then improve Proxmox access protection and off-host backup.
- Stabilize and document the Docker/media services running on `media-docker`.
- Keep home-LAN services private; add remote access only through a deliberate, secure design.

## Future Project Boundary

**Enterprise Security Lab** will be a separate project for the isolated private network, Active Directory, Windows clients, Kali, security monitoring, VLANs, IDS/IPS and attack/detection exercises. Its planning material is retained in this vault only as historical reference until that project is created.

## Future Improvements

- Test restoration and add an off-host backup copy
- Add off-host backup storage
- Configure Proxmox two-factor authentication
- Complete selected media-stack integrations
- Add private remote access where needed
- Create the separate Enterprise Security Lab project

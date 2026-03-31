# Homelab Documentation

This repository documents my homelab environment and the systems I use to learn and practice enterprise-style IT concepts on a smaller scale. The lab is focused on virtualization, clustered infrastructure, VLAN segmentation, backups, disaster recovery, and automation.

I use this environment to build hands-on experience with technologies and operational habits that translate directly to production IT, including documentation, change tracking, validation, and recovery planning. My goal is not just to make things work, but to build them in a way that is repeatable, supportable, and resilient.

## Environment Overview

### Core Technologies
- Proxmox VE
- TrueNAS
- MikroTik CRS310
- Brocade ICX7250
- OPNsense
- Pi-hole
- ZFS
- Ansible
- Tera Term / serial console tools

### Current Focus Areas
- Multi-node virtualization and clustering
- VLAN design and network segmentation
- Shared storage and backup strategy
- Disaster recovery and restore validation
- Automation and documentation
- Practical infrastructure troubleshooting

## What I Built

- A multi-node Proxmox-based lab environment for virtualization, testing, and service hosting
- Segmented networking using VLANs, managed switching, and firewalling
- Centralized storage and backup workflows using TrueNAS, NFS, and ZFS
- Documentation and recovery procedures for restores, failover, and configuration management
- A compact custom hardware layout using repurposed systems, 10Gb networking, and custom cooling solutions

## Selected Highlights

### Proxmox Cluster and Virtualization
Built a Proxmox-based environment to practice VM deployment, templates, storage integration, backup workflows, and clustered infrastructure concepts.

### Storage and Backup Design
Implemented a storage and retention approach using TrueNAS, ZFS datasets, NFS-backed backup targets, and regular restore validation.

### Networking and Segmentation
Designed the environment around VLAN separation, switch-based segmentation, and firewall-controlled traffic flow to better mirror real-world operational practices.

### Documentation and Recovery Mindset
Documented changes, fixes, recovery steps, and infrastructure design decisions to reduce repeat troubleshooting and improve maintainability over time.

## Hardware Summary

- 2 Dell OptiPlex 3080 Micro systems
- 1 Dell 7050 SFF used for NAS and storage
- 1 custom mATX Proxmox node
- 1 Intel NUC utility node
- MikroTik CRS310 switch
- Brocade ICX7250 switch
- Intel X520 10Gb NICs
- TrueNAS-backed shared storage

## Why This Repo Exists

I use this repository to track how I design, build, troubleshoot, and improve my lab over time. It is intended to show practical systems work, not just finished diagrams. The lab helps me deepen my understanding of infrastructure, supportability, backup strategy, and operational discipline.

## Planned Improvements

- Add sanitized network diagrams
- Add selected configuration examples and automation samples
- Publish cleaner summaries of backup, VLAN, and cluster design
- Version more infrastructure documentation in Git

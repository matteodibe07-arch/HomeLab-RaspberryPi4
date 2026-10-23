# Raspberry Pi 4 HomeLab

A personal HomeLab built around a Raspberry Pi 4 running Raspberry Pi OS Lite, focused on Linux system administration, networking, self-hosted services, and cybersecurity.

This project is continuously evolving as I experiment with new technologies, improve the infrastructure, and document configurations, network architecture, and technical challenges.

## Overview

The HomeLab provides a practical environment for learning how to deploy, manage, and maintain services on a Linux-based server.

The project combines hands-on system administration with network design and documentation. The goal is to understand how the different components interact, how services can be accessed securely, and how the infrastructure can be improved over time.

## Hardware & Operating System

- **Hardware:** Raspberry Pi 4
- **Operating System:** Raspberry Pi OS Lite (headless installation)
- **Administration:** SSH and command-line tools

## Services & Technologies

| Technology           | Purpose                                        |
| -------------------- | ---------------------------------------------- |
| Raspberry Pi OS Lite | Lightweight Linux server operating system      |
| Pi-hole              | Network-level DNS filtering and ad blocking    |
| Nextcloud            | Self-hosted file storage and synchronization   |
| Nextcloud Images     | Photo browsing and management                  |
| Tailscale            | Private network connectivity and remote access |
| SSH                  | Remote server administration                   |
| Cisco Packet Tracer  | Network topology modeling and documentation    |

## Network Architecture

The network architecture will be documented using Cisco Packet Tracer to provide a visual representation of the HomeLab topology.

The diagram will aim to illustrate:

- Network devices and their connections.
- IP addressing and subnet organization.
- Client access to the HomeLab services.
- DNS traffic and Pi-hole's role in name resolution.
- Remote access through Tailscale.
- Communication between the main components of the infrastructure.

**Note:** Cisco Packet Tracer will be used as a network modeling and documentation tool. The simulated topology will represent the relevant network relationships, not necessarily reproduce every aspect of the real Raspberry Pi environment or Tailscale's operation.

## Learning Objectives

- **Linux System Administration:** Managing a headless Linux server and its services.
- **Networking & DNS:** Understanding IP addressing, DNS resolution, and network traffic.
- **Self-Hosting:** Deploying and maintaining personal cloud services.
- **Remote Access:** Understanding private connectivity and remote administration.
- **Cybersecurity:** Exploring access control, secure configurations, and system hardening.
- **Network Design:** Modeling and documenting network topology with Cisco Packet Tracer.

## Repository Structure

```text
HomeLab-RaspberryPi4/
├── README.md
├── docs/
│   ├── architecture.md
│   ├── networking.md
│   └── services/
├── diagrams/
│   └── homelab-topology.pkt
└── configs/
```

The repository structure will evolve as documentation, diagrams, and configuration examples are added.

## Roadmap

- [x] Set up a Raspberry Pi 4 running Raspberry Pi OS Lite.
- [x] Deploy Pi-hole.
- [x] Deploy Nextcloud and Nextcloud Images.
- [x] Configure remote access using Tailscale.
- [ ] Design the network topology in Cisco Packet Tracer.
- [ ] Document IP addressing, DNS, and service communication.
- [ ] Document installation and configuration procedures.
- [ ] Review backup and recovery procedures.
- [ ] Explore additional monitoring and security improvements.

## Project Status

**Ongoing personal project.**

This repository documents the evolution of the HomeLab, including its architecture, configuration, troubleshooting process, and future improvements.

The objective is to build practical skills through experimentation and maintain clear technical documentation of the infrastructure.


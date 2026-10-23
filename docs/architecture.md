# HomeLab Architecture

## Overview

The HomeLab is built around a Raspberry Pi 4 running Raspberry Pi OS Lite. It provides a lightweight, headless environment for hosting services and experimenting with Linux system administration, networking, and cybersecurity.

Docker is used to deploy and manage containerized applications, keeping services separated and simplifying their administration and maintenance.

## Hardware & Operating System

- **Hardware:** Raspberry Pi 4
- **Operating System:** Raspberry Pi OS Lite
- **Administration:** SSH through the command line
- **Containerization:** Docker

## Services

The HomeLab hosts the following services:

| Service | Purpose |
|---|---|
| Pi-hole | Network-level DNS filtering and ad blocking |
| Nextcloud | Self-hosted file storage and synchronization |
| Nextcloud Images | Photo browsing and management within Nextcloud |
| Tailscale | Private network connectivity and remote access |

Docker is used to run the services configured as containers. The exact deployment method and networking configuration depend on each service's setup.

## Architecture Principles

The infrastructure follows these general principles:

- **Lightweight deployment:** Using a headless operating system to minimize unnecessary resource usage.
- **Service separation:** Running applications in containers where appropriate.
- **Maintainability:** Keeping service configurations and deployment files organized.
- **Remote administration:** Managing the server through SSH.
- **Security:** Limiting access to services and protecting credentials and sensitive configuration data.

## Network Architecture

The Raspberry Pi is connected to the home network through the home router. Client devices can access the services according to the network configuration and the access permissions in place.

Remote connectivity is provided through Tailscale, allowing authorized devices to connect to the HomeLab without treating the services as automatically exposed to the public Internet.

The network topology is documented separately in the `diagrams/` directory.

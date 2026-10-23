# Network Architecture

## Overview

The HomeLab is connected to my home network through a wireless router. The Raspberry Pi 4 acts as the main server, hosting several self-hosted services accessible to authorized devices.

The network is designed to provide local access to the services and remote connectivity when needed.

## Network Components

- **Home Router:** Connects the HomeLab to the local network and provides Internet connectivity.
- **Raspberry Pi 4:** Hosts the HomeLab services running on Raspberry Pi OS Lite.
- **Client Devices:** Computers, smartphones, and other devices that access the services.
- **Pi-hole:** Provides DNS filtering for devices configured to use it.
- **Tailscale:** Provides private connectivity for remote access to the HomeLab.

## Local Network

Devices connected to the home network can communicate with the Raspberry Pi according to the network configuration.

Pi-hole can filter DNS requests from clients configured to use it, while Nextcloud provides access to personal files and photos.

SSH is used for command-line administration of the Raspberry Pi.

## Remote Access

Tailscale provides a way to connect authorized devices to the HomeLab remotely through a private network.

This allows remote access without assuming that the HomeLab services are directly exposed to the public Internet.

## Network Diagram

The network topology is documented in the [`diagrams/`](../diagrams/) directory using Cisco Packet Tracer.

The diagram is a logical representation of the infrastructure and does not reproduce every aspect of the real network or Tailscale's operation.

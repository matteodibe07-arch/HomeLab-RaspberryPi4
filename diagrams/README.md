# HomeLab Network Diagrams

This directory contains network diagrams representing the architecture of my Raspberry Pi 4 HomeLab.

## Network Topology

The `homelab-topology.pkt` file contains a Cisco Packet Tracer representation of the HomeLab infrastructure, including:

- **Home Network:** The local network connecting the Raspberry Pi server and client devices.
- **Remote Network:** An external network representing devices accessing the HomeLab from outside the local network.
- **Raspberry Pi 4:** The central server running Raspberry Pi OS Lite and hosting services such as Pi-hole, Nextcloud, and SSH.
- **Tailscale:** Private remote connectivity for accessing the HomeLab from authorized devices.
- **Internet / WAN:** A logical representation of the external network connecting the home and remote environments.

## Purpose

The goal of these diagrams is to document the network architecture, visualize the relationships between devices, and provide a clear overview of how the HomeLab components are organized.

Cisco Packet Tracer is used for network topology modeling and documentation. The diagram is a logical representation of the infrastructure and does not reproduce every aspect of the real environment, including the actual operation of Tailscale.

The diagrams will be updated as the infrastructure evolves.

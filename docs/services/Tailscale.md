# Tailscale

## Overview

Tailscale is a VPN solution used in my Raspberry Pi 4 HomeLab to provide secure remote connectivity between authorized devices.

It creates a private network that allows devices to communicate securely, even when they are connected to different networks.

## Purpose

The main goals of using Tailscale are:

- **Remote access:** Connect to the HomeLab when away from the local network.
- **Private connectivity:** Allow authorized devices to communicate through a private network.
- **Remote administration:** Access the Raspberry Pi remotely using SSH.
- **Reduced exposure:** Enable remote connectivity without necessarily exposing services directly to the public Internet.

## Deployment

Tailscale is part of my HomeLab infrastructure, which runs on a Raspberry Pi 4 with Raspberry Pi OS Lite.

The specific installation method and configuration are managed separately from this documentation.

## Integration with the HomeLab

Tailscale complements the other services running on the Raspberry Pi.

It allows authorized devices to connect remotely to the server, making it possible to administer the system and access supported services when away from home.

SSH is used for command-line administration, while access to services such as Nextcloud depends on their individual network and access configurations.

## Security Considerations

- Only authorize trusted devices on the private network.
- Protect account credentials and authentication keys.
- Keep the Raspberry Pi and Tailscale software updated.
- Review access permissions and avoid exposing services unnecessarily.

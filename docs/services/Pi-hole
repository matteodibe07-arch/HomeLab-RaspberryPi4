# Pi-hole

## Overview

Pi-hole is a network-level DNS filtering service running on my Raspberry Pi 4 HomeLab. It helps block requests to known advertising, tracking, and unwanted domains before connections are established.

## Purpose

The main goals of using Pi-hole are:

- **DNS filtering:** Blocks domains included in configured blocklists.
- **Network-wide filtering:** Allows devices on the home network to use Pi-hole for DNS resolution.
- **Centralized management:** Provides a web interface to monitor DNS activity and manage filtering settings.

## Deployment

Pi-hole runs as part of my HomeLab infrastructure on a Raspberry Pi 4 running Raspberry Pi OS Lite. Docker Compose is used to manage containerized services.

## Network Integration

Pi-hole is configured as the DNS server on the home router. Devices that receive this DNS configuration from the router can use Pi-hole automatically, without requiring individual DNS configuration.

DNS requests are filtered according to Pi-hole's configured blocklists and settings. Devices using a different DNS server may bypass this filtering.

## Access and Management

Pi-hole provides a web-based administration interface for monitoring DNS queries, reviewing blocked requests, and managing filtering lists.

The administration interface should only be accessible to authorized users.

## Security Considerations

- Avoid exposing the DNS service or administration interface directly to the public Internet.
- Keep Pi-hole and its blocklists reasonably up to date.
- Never publish passwords, authentication tokens, or other sensitive configuration details.

# 🏡 My Homelab with Docker, Pi-hole, Nextcloud, and Nginx Proxy Manager

This is a self-hosted homelab environment running multiple services with Docker Compose. It includes:

- **Nextcloud** for private cloud storage
- **Pi-hole** for network-wide ad blocking and local DNS
- **Nginx Proxy Manager** (NPM) for reverse proxy with free SSL via Let's Encrypt
- **DuckDNS** for dynamic DNS

---

## 📦 Stack Overview

| Service         | Description                        | Port(s)         | URL                                 |
|-----------------|------------------------------------|------------------|--------------------------------------|
| Nextcloud       | Private file hosting (cloud)       | Internal only    | https://cloud.omarnaru.duckdns.org   |
| Pi-hole         | Network-wide ad blocker + DNS      | 53, 8080         | http://omarnaru.duckdns.org:8080     |
| Nginx Proxy Mgr | Reverse proxy + SSL certificates   | 80, 81, 443      | https://omarnaru.duckdns.org         |


# 🏠 Forsthaus Homelab

Private self-hosted infrastructure for cloud services and family projects.

## 🎯 Overview

Self-hosted cloud platform prioritizing privacy and control, replacing commercial cloud providers with open-source alternatives and modern AI-powered features.

## 🖥️ Infrastructure

**Cloud Services:**
- 📸 Photo management with AI organization
- ☁️ File storage and synchronization
- 🔐 Centralized SSO authentication
- 🌐 Reverse proxy with SSL
- 📊 Container orchestration
- 🏠 Service dashboard

**Network:**
- Private VPN for secure admin access
- DNS filtering and ad-blocking
- SSL encryption via trusted proxy
- Distributed architecture across multiple locations

## 🏗️ Tech Stack

**Core:** Docker, Docker Compose, Linux  
**Services:** Immich, Nextcloud, Authentik  
**Networking:** Nginx Proxy Manager, Tailscale, AdGuard  
**Security:** OAuth 2.0, Forward Auth, Let's Encrypt  

## 📁 Repositories

- **hetzner-server** - Main cloud infrastructure
- **network-config** - DNS, VPN, routing configs
- Additional device-specific configs (private)

## 🔒 Security

- All services protected by SSO authentication
- Private repositories with encrypted secrets
- No public-facing admin interfaces
- Regular automated backups

---

**Status:** Operational  
**Architecture:** Hybrid cloud + local services

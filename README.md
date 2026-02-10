# BakedIn Status

[![Uptime CI](https://github.com/pantry-hash/status/workflows/Uptime%20CI/badge.svg)](https://github.com/pantry-hash/status/actions?query=workflow%3A%22Uptime+CI%22)
[![Response Time CI](https://github.com/pantry-hash/status/workflows/Response%20Time%20CI/badge.svg)](https://github.com/pantry-hash/status/actions?query=workflow%3A%22Response+Time+CI%22)

This repository contains the status page for [BakedIn](https://bakedin.co), powered by [Upptime](https://upptime.js.org).

## Live Status

Visit **[status.bakedin.co](https://status.bakedin.co)** to see the current status of all services.

## Monitored Services

| Service | Description |
|---------|-------------|
| BakedIn Website | Main marketing site |
| Production API | Backend API services |
| Staging API | Pre-production testing |
| MCP Research | Research MCP server |
| MCP CI/CD | CI/CD MCP server |
| MCP Dashboard | Dashboard MCP server |

## How It Works

- **GitHub Actions** monitors endpoints every 5 minutes
- **GitHub Issues** are automatically created for downtime
- **GitHub Pages** hosts the status page
- **Git history** provides uptime metrics over time

## Vendor Due Diligence

This status page solution has been reviewed and approved per [VDD-001](https://github.com/bakedin-ai/bakedin_prod/docs/vendors/VDD-001-upptime.md):

- **License**: MIT
- **Security**: No CVEs, no security advisories
- **Compliance**: Mapped to SOC 2, ISO 27001, ISO 42001

## Links

- [BakedIn](https://bakedin.co)
- [Support](https://bakedin.co/support)
- [Upptime Documentation](https://upptime.js.org)

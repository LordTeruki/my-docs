# Platform Overview

Computus Cloud Beta consists of two main access points:

| Component | URL | Purpose |
|----------|-----|---------|
| **Beta Portal** | https://beta.computus.io | Web dashboard, VM management, billing, SSH keys, S3 credentials |
| **S3 API Endpoint** | https://s3.computus.io:8080 | Object storage (buckets & files) |

## Core Technology Stack

- **OpenStack** — powers compute, networking, and storage
- **OSIE** — handles user accounts, billing, metering, and portal workflows
- **Swift (with S3 compatibility)** — provides Amazon S3-compatible object storage

## Beta Architecture Summary

- You manage everything through the web portal at `beta.computus.io`
- VMs are launched on our OpenStack cluster
- Public access to VMs is via **IPv6 only**
- Private IPv4 networks are fully available for internal communication between VMs
- Object storage is accessed directly via the S3 API

---

**Next:** [Beta Limitations & Rules](beta-limitations.md)

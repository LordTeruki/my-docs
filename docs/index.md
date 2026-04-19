# Computus Cloud Beta Docs

Welcome to the official documentation for **Computus Cloud Beta**.

Computus Cloud is an independent OpenStack-based cloud platform. This beta environment lets you test our infrastructure directly, with **OSIE** managing accounts, billing, metering, and workflows, and fully S3-compatible object storage.

> **This is a closed beta.** All usage is metered and subject to strict limits. Your feedback will directly shape the final platform.

## Beta Endpoints

| Service           | Endpoint                          | Notes                          |
|-------------------|-----------------------------------|--------------------------------|
| **Beta Portal**   | https://beta.computus.io         | Main dashboard and management |
| **S3 API**        | https://s3.computus.io:8080      | Note the **:8080** port       |

## Beta Limitations (Please Respect These)

**Object Storage (S3)**
- Maximum **200 GB** total storage per account
- Create credentials via **Access → S3/EC2 Credentials** in the portal

**Compute (Virtual Machines)**
- Maximum **2 VMs** total per account
- Available images: **Ubuntu**, **Debian**, **Rocky Linux**
- Available flavors: **Tiny**, **Small**, **Medium** only
- Public networking: **IPv6 only** (no public IPv4)
- Private IPv4 networking fully supported

**Networking**
- Unlimited private networks and subnets
- Full freedom to attach interfaces and experiment

## Quick Start Guide

1. **[Sign up / Log in](https://beta.computus.io)** to the Beta Portal
2. **[Create S3 Credentials](object-storage/access-keys-and-secret-keys.md)** (Access Key + Secret Key)
3. **[Create your first Bucket](object-storage/creating-buckets.md)** and test at `s3.computus.io:8080`
4. **[Upload an SSH Key](compute/ssh-keys.md)**
5. **[Launch your first VM](compute/creating-a-vm.md)** (select "external net" + your SSH key)
6. Connect to your VM using its **public IPv6** address

## Main Sections

- **[Object Storage (S3)](object-storage/object-storage-overview.md)** — Buckets, credentials, AWS CLI, S3 Browser
- **[Compute](compute/creating-a-vm.md)** — Launching VMs, flavors, images, IPv6 access
- **[Networking](networking/networks-overview.md)** — Private networks and advanced setups
- **[Control Panel](control-panel/dashboard-overview.md)** — Dashboard, billing, projects
- **[Troubleshooting](troubleshooting/)** — Common beta issues

---

**We want your feedback!**  
Use the **Support Requests** section in the beta portal to report bugs, share what worked well, suggest improvements, or describe interesting private networking setups you build.

Thank you for helping test Computus Cloud!

— The Computus Team
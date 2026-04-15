# Computus Cloud Docs

Welcome to the documentation portal for **Computus Cloud**.

Computus Cloud is an independent cloud platform built on **OpenStack**, with **OSIE** providing customer account, billing, and service workflows, and **S3-compatible object storage** exposed through a dedicated API endpoint.

## Public Endpoints

### Cloud Portal
`https://cloud.computus.io`

Use the cloud portal to:
- register an account
- verify your email
- log in to the customer dashboard
- manage billing
- provision and manage services
- view invoices and account status

### S3 API
`https://s3.computus.io`

Use the S3 endpoint for:
- bucket creation
- object uploads and downloads
- backup tools
- AWS CLI compatible workflows
- application integrations that support the Amazon S3 API

## Platform Overview

Computus Cloud is organized into two main customer-facing access points:

- **`cloud.computus.io`** for the customer portal and OSIE-managed workflows
- **`s3.computus.io`** for S3-compatible object storage access

Behind the scenes, the platform is powered by OpenStack services including compute, networking, identity, image management, and object storage.

## Core Services

Computus Cloud is designed to provide:

- virtual machines
- private networking
- floating IPs
- project and tenant isolation
- S3-compatible object storage
- billing and account lifecycle management

## Recommended First Steps

If you are new to the platform, start here:

1. Read [What is Computus Cloud?](getting-started/what-is-computus-cloud.md)
2. Review the [Platform Overview](getting-started/platform-overview.md)
3. Complete [Account Signup](getting-started/account-signup.md)
4. Confirm your email in [Email Verification](getting-started/email-verification.md)
5. Continue to [First Login to cloud.computus.io](getting-started/first-login.md)

## Common Tasks

### Access the Portal
Go to [Accessing the Portal](control-panel/accessing-the-portal.md)

### Create a Virtual Machine
See [Creating a VM](compute/creating-a-vm.md)

### Configure Networking
See [Networks Overview](networking/networks-overview.md)

### Use Object Storage
Start with [Object Storage Overview](object-storage/object-storage-overview.md)

### Connect with AWS CLI
See [Using AWS CLI](object-storage/using-aws-cli.md)

## High-Level Architecture

```text
[ Customer Browser / Client ]
           |
           v
   cloud.computus.io
      (OSIE Portal)
           |
           v
      OSIE Backend
           |
           v
     OpenStack APIs
   ├── Keystone
   ├── Nova
   ├── Neutron
   ├── Glance
   └── Swift
           |
           v
     s3.computus.io
   (S3-Compatible API)
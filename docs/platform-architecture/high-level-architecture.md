# High-Level Architecture

Computus Cloud Beta is built on a modern OpenStack-based infrastructure designed for reliability and ease of use.

## Architecture Overview

Your Browser
    |
    v
https://beta.computus.io
    (Computus Dashboard)
    |
    v
OpenStack Services
    - Nova (Compute)
    - Neutron (Networking)
    - Glance (Images)
    - Keystone (Identity)
    - Swift (Object Storage with S3 compatibility)
    |
    v
https://s3.computus.io:8080

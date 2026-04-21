\# High-Level Architecture



Computus Cloud Beta is built on a modern OpenStack-based infrastructure designed for reliability and ease of use.



\## Architecture Overview



```text

\[ Your Browser ]

&#x20;      |

&#x20;      v

https://beta.computus.io

&#x20;  (Computus Dashboard)

&#x20;      |

&#x20;      v

&#x20;  OpenStack Services

&#x20;  ├── Nova (Compute)

&#x20;  ├── Neutron (Networking)

&#x20;  ├── Glance (Images)

&#x20;  ├── Keystone (Identity)

&#x20;  └── Swift (Object Storage with S3 compatibility)

&#x20;      |

&#x20;      v

&#x20;  s3.computus.io:8080


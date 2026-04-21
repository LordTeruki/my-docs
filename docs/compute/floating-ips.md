\# IPv6 Access Only (Beta)



During the beta, all virtual machines receive a \*\*public IPv6 address\*\* automatically. There are \*\*no public IPv4 addresses\*\* available.



\## What You Get



\- One public IPv6 address per VM (on "external net")

\- Full outbound and inbound IPv6 connectivity

\- Private IPv4 address on the internal network



\## Connecting to Your VM



You must connect using the IPv6 address via SSH. Most modern operating systems and networks support IPv6.



\*\*Example:\*\*

```bash

ssh ubuntu@2607:xxxx:xxxx:xxxx::xxxx


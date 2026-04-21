\# API Keys \& Credentials



This section is critical for using the platform.



\## Two Types of Credentials



\### 1. S3 Credentials (Object Storage)



\*\*Path:\*\* Access → S3 Credentials



\*\*How to create:\*\*

1\. Go to \*\*Access → S3 Credentials\*\*

2\. Click \*\*Create Credentials\*\*

3\. Give it a description (e.g. "My Backup Tool")

4\. Click \*\*Create\*\*

5\. \*\*Immediately copy and save\*\* the \*\*Access Key\*\* and \*\*Secret Key\*\* securely



> These are used with the S3 endpoint `https://s3.computus.io:8080`



\### 2. SSH Keys (for Virtual Machines)



\*\*Path:\*\* Access → SSH Keys



\*\*How to create:\*\*

1\. Go to \*\*Access → SSH Keys\*\*

2\. Click \*\*Create SSH Key\*\*

3\. Give it a name

4\. Paste your \*\*public key\*\* (e.g. content of `id\_ed25519.pub` or `id\_rsa.pub`)

5\. Click \*\*Save\*\*



You must upload at least one SSH key before launching any VM.



\## Best Practices



\- Never share your Secret Key

\- Create separate credentials for different tools or applications

\- Rotate credentials periodically

\- Delete unused credentials



\---



\*\*All Control Panel pages updated.\*\*



Would you like me to also revise the \*\*Getting Started\*\* section to remove any remaining OSIE mentions for consistency? Or should we move straight to the \*\*Object Storage (S3)\*\* section now?


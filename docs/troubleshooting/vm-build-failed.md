\# VM Build Failed



\## Common Reasons



\- No SSH key uploaded before launching the instance

\- Did not select \*\*"external net"\*\* as the network

\- Selected a flavor or image that is not available in beta

\- Reached the limit of 2 VMs



\## How to Fix



1\. Go to \*\*Access → SSH Keys\*\* and upload a public key

2\. Delete any failed instance

3\. Launch again, making sure to:

&#x20;  - Choose Ubuntu/Debian/Rocky

&#x20;  - Choose Tiny/Small/Medium flavor

&#x20;  - Select \*\*external net\*\*

&#x20;  - Select your SSH key



Check the instance logs in the dashboard for more details.


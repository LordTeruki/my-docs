\# SSH Keys (Required)



You \*\*must\*\* upload at least one SSH public key before you can create any virtual machine.



\## How to Add an SSH Key



1\. Go to \*\*Access → SSH Keys\*\* in the dashboard

2\. Click \*\*Create SSH Key\*\* or \*\*Add Key\*\*

3\. Give it a clear name (e.g. "My Laptop Key")

4\. Paste the content of your \*\*public key\*\*:

&#x20;  - Usually `\~/.ssh/id\_ed25519.pub` or `\~/.ssh/id\_rsa.pub`

5\. Click \*\*Save\*\*



\## Tips



\- Use Ed25519 keys when possible (more secure and faster)

\- You can add multiple keys

\- The key will be automatically injected into new VMs



\*\*Important:\*\* You cannot add or change the SSH key after the VM is created.



\---



\*\*Next:\*\* \[IPv6 Access Only](floating-ips.md)


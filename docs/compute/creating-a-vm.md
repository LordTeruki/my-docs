\# Creating a VM (Beta)



Follow these steps to launch your first virtual machine.



\## Step-by-Step Instructions



1\. Log in to \[https://beta.computus.io](https://beta.computus.io)

2\. In the left menu, go to \*\*Compute → Instances\*\*

3\. Click \*\*Launch Instance\*\* or \*\*Create VM\*\*



\### Required Settings:



\- \*\*Name\*\*: Give your VM a meaningful name

\- \*\*Image\*\*: Choose one of:

&#x20; - Ubuntu (latest)

&#x20; - Debian (latest)

&#x20; - Rocky Linux (latest)

\- \*\*Flavor\*\*:

&#x20; - Tiny

&#x20; - Small

&#x20; - Medium

\- \*\*SSH Key\*\*: Select the SSH key you previously uploaded (required)

\- \*\*Network\*\*: Select \*\*external net\*\* (this is the default — very important)

\- \*\*Security Group\*\*: Use the default one for now



4\. Click \*\*Launch\*\* / \*\*Create\*\*



After a few minutes, your VM should show as \*\*Active\*\* with a public \*\*IPv6\*\* address.



\## How to Connect



Use SSH with your private key:



```bash

ssh -i \~/.ssh/your\_private\_key user@your-ipv6-address


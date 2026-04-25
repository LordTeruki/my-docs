# Creating a VM (Beta)

Follow these steps to launch your first virtual machine.

## Step-by-Step Instructions

1. Log in to https://beta.computus.io
2. Go to Compute → Instances
3. Click Launch Instance

### Required Settings

Name: give your VM a meaningful name

Image:

* Ubuntu
* Debian
* Rocky Linux

Flavor:

* Tiny
* Small
* Medium

SSH Key: select your uploaded key (required)

Network: select external net (very important)

Security Group: use the default

4. Click Launch

After a few minutes, your VM will become Active with a public IPv6 address.

## How to Connect

ssh -i \~/.ssh/your\_private\_key ubuntu@your-ipv6-address


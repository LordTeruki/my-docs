# SSH Keys (Required)

You must upload at least one SSH public key before creating a VM.

## How to Add an SSH Key

1. Go to Access → SSH Keys
2. Click Create SSH Key
3. Give it a name
4. Paste your public key (~/.ssh/id_ed25519.pub or id_rsa.pub)
5. Click Save

## Tips

- Use Ed25519 when possible
- You can add multiple keys
- Keys are injected into new VMs automatically

Important: You cannot change the key after VM creation.
